# Supported projects

Generated 2026-09-29T20:25:04Z. Written by the line manager reconciler.

The latest patch view: every library at the latest upstream patch release, the view the work follows. Every library and version the exchange maintains, ordered by library and then by version. A library that sits on more than one line is one row, with every line it belongs to named. For reporting only.

## Lines

| line_id | ecosystem | anchor | status | CVE_in_scope | CVE_fixed | CVE_fixed_% | CVE_out_of_scope | CVE_in_progress | CVE_left | CVE_not_remediable |
|---|---|---|---|---|---|---|---|---|---|---|
| spring-boot-2.7.x | maven | `org.springframework.boot:spring-boot-dependencies@2.7.18` | not fixed | 72 | 0 | 0% | 197 | 0 | 72 | 0 |
| spring-framework-5.3.x | maven | `org.springframework:spring-framework-bom@5.3.39` | not fixed | 19 | 0 | 0% | 24 | 0 | 19 | 0 |
| spring-security-5.7.x | maven | `org.springframework.security:spring-security-bom@5.7.11` | not fixed | 20 | 0 | 0% | 43 | 0 | 20 | 0 |
| dev-1.0.x | maven | `org.finos.osera.dev:dev-bom@2.0.0` | not fixed | 4 | 0 | 0% | 4 | 0 | 4 | 0 |

## Libraries

44 libraries across 4 line(s).

| name | version | lines | why_listed | status | CVE_in_scope | CVE_fixed | CVE_fixed_% | CVE_out_of_scope | CVE_in_progress | CVE_left | CVE_not_remediable | patched_as | consumed | consumption_readiness | chain | files | evidence | signatures | document | producer | verdict | fork | tag | upload | tagger |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| args4j:args4j | 2.33 | dev-1.0.x | listed by the BOM at 2.33 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| ch.qos.logback:logback-core | 1.2.13 | spring-boot-2.7.x | listed by the BOM at 1.2.12 | open | 1 | 0 | 0% | 5 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.beust:jcommander | 1.82 | dev-1.0.x | listed by the BOM at 1.82 | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.fasterxml.jackson.core:jackson-core | 2.13.5 | spring-boot-2.7.x, spring-security-5.7.x | listed by the BOM of spring-boot-2.7.x at 2.13.5 (com.fasterxml.jackson:jackson-bom@2.13.5) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.fasterxml.jackson.core:jackson-databind | 2.13.5 | spring-boot-2.7.x, spring-security-5.7.x | listed by the BOM of spring-boot-2.7.x at 2.13.5 (com.fasterxml.jackson:jackson-bom@2.13.5) | open | 3 | 0 | 0% | 5 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.fasterxml.jackson.dataformat:jackson-dataformat-toml | 2.13.5 | spring-boot-2.7.x | listed by the BOM at 2.13.5 (com.fasterxml.jackson:jackson-bom@2.13.5) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| io.projectreactor.netty:reactor-netty | 1.0.48 | spring-boot-2.7.x | listed by the BOM at 1.0.39 (io.projectreactor:reactor-bom@2020.0.38) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| io.projectreactor.netty:reactor-netty-http | 1.0.48 | spring-boot-2.7.x | listed by the BOM at 1.0.39 (io.projectreactor:reactor-bom@2020.0.38) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| net.sf.jopt-simple:jopt-simple | 5.0.4 | dev-1.0.x, spring-boot-2.7.x | listed by the BOM of dev-1.0.x at 5.0.4 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.logging.log4j:log4j-1.2-api | 2.17.2 | spring-boot-2.7.x | listed by the BOM at 2.17.2 (org.apache.logging.log4j:log4j-bom@2.17.2) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.logging.log4j:log4j-core | 2.17.2 | spring-boot-2.7.x | listed by the BOM at 2.17.2 (org.apache.logging.log4j:log4j-bom@2.17.2) | open | 1 | 0 | 0% | 2 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.logging.log4j:log4j-layout-template-json | 2.17.2 | spring-boot-2.7.x | listed by the BOM at 2.17.2 (org.apache.logging.log4j:log4j-bom@2.17.2) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.eclipse.jetty:jetty-http | 9.4.58.v20250814 | spring-boot-2.7.x | listed by the BOM at 9.4.53.v20231009 (org.eclipse.jetty:jetty-bom@9.4.53.v20231009) | open | 1 | 0 | 0% | 1 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.eclipse.jetty:jetty-jaspi | 9.4.58.v20250814 | spring-boot-2.7.x | listed by the BOM at 9.4.53.v20231009 (org.eclipse.jetty:jetty-bom@9.4.53.v20231009) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.eclipse.jetty:jetty-security | 9.4.58.v20250814 | spring-boot-2.7.x | listed by the BOM at 9.4.53.v20231009 (org.eclipse.jetty:jetty-bom@9.4.53.v20231009) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.hibernate:hibernate-core | 5.6.15.Final | spring-boot-2.7.x | listed by the BOM at 5.6.15.Final | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot-devtools | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot-loader | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot-starter-actuator | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-commons | 2.7.18 | spring-boot-2.7.x, spring-security-5.7.x | listed by the BOM of spring-boot-2.7.x at 2.7.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 1 | 0 | 0% | 2 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-keyvalue | 2.7.18 | spring-boot-2.7.x | listed by the BOM at 2.7.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-mongodb | 3.4.18 | spring-boot-2.7.x | listed by the BOM at 3.4.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 1 | 0 | 0% | 1 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-rest-core | 3.7.18 | spring-boot-2.7.x | listed by the BOM at 3.7.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 2 | 0 | 0% | 2 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.graphql:spring-graphql | 1.0.6 | spring-boot-2.7.x | listed by the BOM at 1.0.6 | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.hateoas:spring-hateoas | 1.5.6 | spring-boot-2.7.x | listed by the BOM at 1.5.6 | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.integration:spring-integration-file | 5.5.20 | spring-boot-2.7.x | listed by the BOM at 5.5.20 (org.springframework.integration:spring-integration-bom@5.5.20) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.kafka:spring-kafka | 2.8.11 | spring-boot-2.7.x | listed by the BOM at 2.8.11 | open | 4 | 0 | 0% | 0 | 0 | 4 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.ldap:spring-ldap-core | 2.4.4 | spring-boot-2.7.x, spring-security-5.7.x | listed by the BOM of spring-boot-2.7.x at 2.4.1 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.security:spring-security-core | 5.7.11 | spring-boot-2.7.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework.security@5.7.11) | open | 1 | 0 | 0% | 2 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.security:spring-security-crypto | 5.7.11 | spring-boot-2.7.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework.security@5.7.11) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.security:spring-security-saml2-service-provider | 5.7.11 | spring-boot-2.7.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework.security@5.7.11) | open | 1 | 0 | 0% | 2 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.security:spring-security-web | 5.7.11 | spring-boot-2.7.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework.security@5.7.11) | open | 4 | 0 | 0% | 0 | 0 | 4 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.ws:spring-ws-core | 3.1.8 | spring-boot-2.7.x | listed by the BOM at 3.1.8 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.ws:spring-ws-security | 3.1.8 | spring-boot-2.7.x | listed by the BOM at 3.1.8 | open | 1 | 0 | 0% | 4 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.ws:spring-xml | 3.1.8 | spring-boot-2.7.x | listed by the BOM at 3.1.8 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-core | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-expression | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 3 | 0 | 0% | 1 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-jms | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-web | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 1 | 0 | 0% | 1 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-webflux | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 5 | 0 | 0% | 10 | 0 | 5 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-webmvc | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 6 | 0 | 0% | 9 | 0 | 6 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-websocket | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 1 | 0 | 0% | 1 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.yaml:snakeyaml | 1.30 | spring-boot-2.7.x | listed by the BOM at 1.30 | open | 6 | 0 | 0% | 1 | 0 | 6 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |

## Libraries promoted, not in the backlog

1 library, 1 patched version(s).

| name | base_version | reason | lines | same group on | patched_as | consumed | consumption_readiness | chain | files | evidence | signatures | document | producer | verdict | fork | tag | upload | tagger |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| org.yaml:snakeyaml | 1.33 | in the dependency graph of spring-boot-2.7.x at 1.30, uploaded on 1.33 | spring-boot-2.7.x |  | 1.33.1-osera-00001 | 1.33.1-osera-00001 | not ready, evidence chain incomplete: producer, verdict, signatures, VEX document | broken | OK | OK | NOK (no registry entry to take the signing key from) | NOK (the vulnerability document's signature: no registry entry to take the signing key from) | NOK (producer controlplane-dev is not in the approved producers registry) | NOK (the verdict names producer cp-osera-dev, the evidence names controlplane-dev) | OK | OK | not checked (no registry entry to compare the upload account with) | not checked (no registry entry to compare the tag pusher with) |
