# Serialization Frameworks
- Various data serialization frameworks include [Protobuf](ProtocolBuffers.md), [Thrift](Thrift.md), [Avro](Avro.md).

# Features
- [Interface Description Language (IDL)](Concepts/IDL.md)
- Performance (better than JSON/XML)
- Versioning (through field identifier)
- Binary Format

# Modeling Steps
- Write down a bunch of struct-like message formats in an [IDL-like language](Concepts/IDL.md).
- Run a tool to generate boilerplate code.
- Link against the boilerplate code when building the application.