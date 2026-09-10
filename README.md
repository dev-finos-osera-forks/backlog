# OSERA backlog

The CVEs OSERA fixes on the lines it supports, in priority order, one GitHub issue each. Says what must be fixed, in what order and why. Never how: how a CVE gets fixed is the producer's call.

| File | What it holds |
|---|---|
| `supported-lines.csv` | The lines OSERA supports, one row each: Framework, Boot and Security versions, status, where the decision came from |
| `cve-backlog.json` | The order book. One entry per CVE and library at the version the line uses. Scores are the CVSS 3.1 base score as recorded at NVD (OSV where NVD has nothing, `cvss_version` says which). Priority and rules are the Risk Navigator's, quoted on every row. Order: CISA KEV first, then the priority band, then the score, then EPSS |
| `cve-backlog.md` | The same book as a readable table |
| `coordinates.csv` | Every library and version each supported line resolves to, the book's entries are the subset with a qualifying CVE. Read by the line manager to watch the whole line |
| `schema/` | What one entry must look like |
| `.github/ISSUE_TEMPLATE/cve.md` | The issue template, a person can use it by hand for a CVE that is not in the book yet |

## How the book moves

1. **A pull request.** ControlPlane rebuilds the book from the supported lines, the advisories, the scores and the Risk Navigator rules, and opens a pull request with the new `cve-backlog.json`. The `validate` check runs on it: every entry matches the schema, every line named is a supported line.
2. **A review and a merge.** Main is protected, the pull request needs approval.
3. **A tag.** An admin tags the merge commit with the book version, `v2026.09.09`. The tag is the act of publishing the book. Merging is not.
4. **One issue per CVE.** The `open-issues` workflow runs on the tag. For every CVE in the book it looks for an issue with that CVE id in the title anywhere in this organisation. If none is found: it opens one from the template, labelled with the priority band and the lines. If one is found: it leaves it alone, and comments if the priority changed. A CVE that left the book gets a comment on its open issue, never a close. The workflow never closes, reopens, assigns or deletes anything, and running it twice changes nothing.
5. **The producer takes the issue.** The producer moves it into the patch repository for that project (a fork under this organisation), and tracks the work there. The org project board follows the issue.
6. **The gate closes it.** When the patched release is published through the OSERA Exchange, the gate closes the issue with the published coordinates.

## Labels

`cve` on every issue from the book, `P0 / Act`, `P1 / Attend`, `P2 / Investigate` for the Risk Navigator priority, `kev` when the CVE is on the CISA Known Exploited Vulnerabilities list, and one label per supported line. The workflow creates them here. A patch repository that wants to keep them on a transferred issue needs the same labels.

## Where the rules come from

- The supported lines and the Wave 1 scope: the OSERA Board and https://github.com/finos-osera/risk-navigator/issues/7
- The prioritisation rules and the priority bands: https://github.com/finos-osera/risk-navigator/issues/7
- The end to end flow: https://github.com/finos-osera/operations-taskforce/issues/23
