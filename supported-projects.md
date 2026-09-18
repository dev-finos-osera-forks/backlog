# Supported projects

Generated 2026-09-18T14:18:21Z. Written by the line manager reconciler.

Every library and version the exchange maintains, ordered by library and then by version. A library that sits on more than one line is one row, with every line it belongs to named. For reporting only.

## Lines

| line_id | ecosystem | anchor | status | CVE_in_scope | CVE_out_of_scope | CVE_in_progress | CVE_fixed | CVE_left | CVE_not_remediable |
|---|---|---|---|---|---|---|---|---|---|
| spring-boot-2.7.x | maven | `org.springframework.boot:spring-boot-dependencies@2.7.18` | in progress | 137 | 152 | 0 | 5 | 132 | 0 |
| spring-framework-5.3.x | maven | `org.springframework:spring-framework-bom@5.3.39` | not fixed | 19 | 24 | 0 | 0 | 19 | 0 |
| spring-security-5.7.x | maven | `org.springframework.security:spring-security-bom@5.7.11` | not fixed | 27 | 41 | 0 | 0 | 27 | 0 |
| dev-1.0.x | maven | `org.finos.osera.dev:dev-bom@2.0.0` | in progress | 4 | 4 | 4 | 0 | 0 | 0 |

## Libraries

54 libraries across 4 line(s).

| name | version | lines | status | CVE_in_scope | CVE_out_of_scope | CVE_in_progress | CVE_fixed | CVE_left | CVE_not_remediable | patched_as | chain | consumption_readiness |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| args4j:args4j | 2.33 | dev-1.0.x | in progress | 1 | 0 | 1 | 0 | 0 | 0 |  |  | patch in progress |
| ch.qos.logback:logback-classic | 1.2.12 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| ch.qos.logback:logback-core | 1.2.12 | spring-boot-2.7.x | open | 3 | 5 | 0 | 0 | 3 | 0 |  |  | not claimed |
| com.beust:jcommander | 1.82 | dev-1.0.x | in progress | 2 | 0 | 2 | 0 | 0 | 0 |  |  | patch in progress |
| com.fasterxml.jackson.core:jackson-core | 2.13.0 | spring-security-5.7.x | open | 2 | 0 | 0 | 0 | 2 | 0 |  |  | not claimed |
| com.fasterxml.jackson.core:jackson-core | 2.13.5 | spring-boot-2.7.x | open | 2 | 0 | 0 | 1 | 1 | 0 | 2.13.5.1-osera-00001 | complete | ready |
| com.fasterxml.jackson.core:jackson-databind | 2.13.0 | spring-security-5.7.x | open | 7 | 2 | 0 | 0 | 7 | 0 |  |  | not claimed |
| com.fasterxml.jackson.core:jackson-databind | 2.13.5 | spring-boot-2.7.x | open | 3 | 2 | 0 | 0 | 3 | 0 |  |  | not claimed |
| io.netty:netty-codec | 4.1.101.Final | spring-boot-2.7.x | open | 3 | 0 | 0 | 0 | 3 | 0 |  |  | not claimed |
| io.netty:netty-codec-dns | 4.1.101.Final | spring-boot-2.7.x | open | 1 | 1 | 0 | 0 | 1 | 0 |  |  | not claimed |
| io.netty:netty-codec-http | 4.1.101.Final | spring-boot-2.7.x | open | 16 | 3 | 0 | 0 | 16 | 0 |  |  | not claimed |
| io.netty:netty-codec-http2 | 4.1.101.Final | spring-boot-2.7.x | open | 5 | 3 | 0 | 0 | 5 | 0 |  |  | not claimed |
| io.netty:netty-handler | 4.1.101.Final | spring-boot-2.7.x | open | 6 | 0 | 0 | 0 | 6 | 0 |  |  | not claimed |
| io.netty:netty-handler-proxy | 4.1.101.Final | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| io.netty:netty-resolver-dns | 4.1.101.Final | spring-boot-2.7.x | open | 3 | 0 | 0 | 0 | 3 | 0 |  |  | not claimed |
| io.projectreactor.netty:reactor-netty-http | 1.0.39 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| net.sf.jopt-simple:jopt-simple | 5.0.4 | dev-1.0.x | in progress | 1 | 0 | 1 | 0 | 0 | 0 |  |  | patch in progress |
| org.apache.logging.log4j:log4j-core | 2.17.2 | spring-boot-2.7.x | open | 1 | 2 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.apache.tomcat.embed:tomcat-embed-core | 9.0.83 | spring-boot-2.7.x | open | 34 | 2 | 0 | 0 | 34 | 0 |  |  | not claimed |
| org.apache.tomcat.embed:tomcat-embed-websocket | 9.0.83 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.eclipse.jetty:jetty-http | 9.4.53.v20231009 | spring-boot-2.7.x | open | 2 | 1 | 0 | 0 | 2 | 0 |  |  | not claimed |
| org.eclipse.jetty:jetty-security | 9.4.53.v20231009 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.eclipse.jetty:jetty-server | 9.4.53.v20231009 | spring-boot-2.7.x | open | 2 | 1 | 0 | 0 | 2 | 0 |  |  | not claimed |
| org.eclipse.jetty:jetty-servlets | 9.4.53.v20231009 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.hibernate:hibernate-core | 5.6.15.Final | spring-boot-2.7.x | fixed | 1 | 0 | 0 | 1 | 0 | 0 | 5.6.15.Final-osera-00001 | complete | ready |
| org.springframework.boot:spring-boot | 2.7.18 | spring-boot-2.7.x | open | 2 | 0 | 0 | 0 | 2 | 0 |  |  | not claimed |
| org.springframework.boot:spring-boot-devtools | 2.7.18 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.boot:spring-boot-loader | 2.7.18 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.boot:spring-boot-starter-actuator | 2.7.18 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.data:spring-data-commons | 2.7.14 | spring-security-5.7.x | open | 1 | 2 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.data:spring-data-commons | 2.7.18 | spring-boot-2.7.x | open | 1 | 2 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.data:spring-data-keyvalue | 2.7.18 | spring-boot-2.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.data:spring-data-mongodb | 3.4.18 | spring-boot-2.7.x | fixed | 1 | 1 | 0 | 1 | 0 | 0 | 3.4.18.1-osera-00001 | complete | ready |
| org.springframework.data:spring-data-rest-core | 3.7.18 | spring-boot-2.7.x | open | 2 | 2 | 0 | 0 | 2 | 0 |  |  | not claimed |
| org.springframework.graphql:spring-graphql | 1.0.6 | spring-boot-2.7.x | open | 2 | 0 | 0 | 0 | 2 | 0 |  |  | not claimed |
| org.springframework.hateoas:spring-hateoas | 1.5.6 | spring-boot-2.7.x | open | 2 | 0 | 0 | 0 | 2 | 0 |  |  | not claimed |
| org.springframework.ldap:spring-ldap-core | 2.4.1 | spring-boot-2.7.x, spring-security-5.7.x | open | 1 | 1 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.security:spring-security-core | 5.7.11 | spring-boot-2.7.x, spring-security-5.7.x | open | 1 | 2 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.security:spring-security-crypto | 5.7.11 | spring-boot-2.7.x, spring-security-5.7.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.security:spring-security-saml2-service-provider | 5.7.11 | spring-boot-2.7.x, spring-security-5.7.x | open | 1 | 2 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework.security:spring-security-web | 5.7.11 | spring-boot-2.7.x, spring-security-5.7.x | open | 4 | 0 | 0 | 0 | 4 | 0 |  |  | not claimed |
| org.springframework.ws:spring-ws-core | 3.1.8 | spring-boot-2.7.x | fixed | 1 | 0 | 0 | 1 | 0 | 0 | 3.1.8.1-osera-00002 | complete | ready |
| org.springframework.ws:spring-xml | 3.1.8 | spring-boot-2.7.x | fixed | 1 | 0 | 0 | 1 | 0 | 0 | 3.1.8.1-osera-00002 | complete | ready |
| org.springframework:spring-core | 5.3.29 | spring-security-5.7.x | open | 2 | 0 | 0 | 0 | 2 | 0 |  |  | not claimed |
| org.springframework:spring-core | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | open | 2 | 0 | 0 | 0 | 2 | 0 |  |  | not claimed |
| org.springframework:spring-expression | 5.3.29 | spring-security-5.7.x | open | 3 | 2 | 0 | 0 | 3 | 0 |  |  | not claimed |
| org.springframework:spring-expression | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | open | 3 | 1 | 0 | 0 | 3 | 0 |  |  | not claimed |
| org.springframework:spring-jms | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | open | 1 | 0 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework:spring-web | 5.3.29 | spring-security-5.7.x | open | 4 | 2 | 0 | 0 | 4 | 0 |  |  | not claimed |
| org.springframework:spring-web | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | open | 1 | 1 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.springframework:spring-webflux | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | open | 5 | 10 | 0 | 0 | 5 | 0 |  |  | not claimed |
| org.springframework:spring-webmvc | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | open | 6 | 9 | 0 | 0 | 6 | 0 |  |  | not claimed |
| org.springframework:spring-websocket | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | open | 1 | 1 | 0 | 0 | 1 | 0 |  |  | not claimed |
| org.yaml:snakeyaml | 1.30 | spring-boot-2.7.x | open | 6 | 1 | 0 | 0 | 6 | 0 |  |  | not claimed |
