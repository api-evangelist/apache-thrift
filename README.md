# Apache Thrift (apache-thrift)
Apache Thrift is a software framework for scalable cross-language services development. It provides an interface definition language (IDL) and code generation engine for building RPC services across 20+ programming languages including Java, Python, C++, Go, and JavaScript.

**URL:** [https://thrift.apache.org/](https://thrift.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Code Generation, Cross-Language, IDL, RPC, Serialization, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Thrift IDL
The Thrift Interface Definition Language for defining data types and service interfaces in language-neutral .thrift files, with code generation for 20+ target languages.

**Human URL:** [https://thrift.apache.org/docs/idl.html](https://thrift.apache.org/docs/idl.html)

#### Tags:

 - IDL, Code Generation, RPC, Cross-Language

#### Properties

- [Documentation](https://thrift.apache.org/docs/idl.html)
- [Documentation](https://thrift.apache.org/docs/types.html)
- [JSONSchema](json-schema/thrift-idl.yml)

### Apache Thrift Server API
Server implementations for hosting Thrift services with TSimpleServer, TThreadedServer, TNonblockingServer, and multiple protocol/transport combinations.

**Human URL:** [https://thrift.apache.org/docs/concepts.html](https://thrift.apache.org/docs/concepts.html)

#### Tags:

 - Server, RPC, Protocol, Transport

#### Properties

- [Documentation](https://thrift.apache.org/docs/concepts.html)

## Common Properties

- [GitHubRepository](https://github.com/apache/thrift)
- [Documentation](https://thrift.apache.org/docs/)
- [Portal](https://thrift.apache.org/)
- [GettingStarted](https://thrift.apache.org/tutorial/)
- [ReleaseNotes](https://github.com/apache/thrift/releases)
- [TermsOfService](https://www.apache.org/licenses/)
- [Python Package](https://pypi.org/project/thrift/)
- [Java Maven Package](https://search.maven.org/search?q=org.apache.thrift)

## Features

| Name | Description |
|------|-------------|
| Cross-Language Code Generation | Generate client and server stubs for 20+ programming languages from a single IDL file. |
| Binary Serialization | Compact binary serialization (TCompactProtocol) for high-performance communication. |
| Multiple Transports | TSocket, TFramedTransport, TFileTransport, TZlibTransport, and TMemoryBuffer transports. |
| Multiple Protocols | TBinaryProtocol, TCompactProtocol, TJSONProtocol serialization formats. |
| Async Server Support | Non-blocking async server for high-throughput service deployments. |
| Versioned Schema Evolution | Optional and default fields enable backward-compatible schema evolution. |

## Use Cases

| Name | Description |
|------|-------------|
| Internal Microservices | High-performance binary RPC between internal microservices in polyglot environments. |
| Cross-Language APIs | Type-safe APIs that work identically across Java, Python, C++, and other languages. |
| Distributed Systems | Service mesh communication with efficient binary serialization. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Cassandra | Cassandra uses Thrift (legacy) for client communication. |
| Apache HBase | HBase Thrift gateway for non-Java clients. |
| Apache Hadoop | Hive Thrift server provides JDBC/ODBC access to Hive. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Thrift IDL Schema](json-schema/thrift-idl.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
