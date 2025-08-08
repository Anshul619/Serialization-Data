# Serialization Frameworks
- Various data serialization frameworks include [Protobuf](Frameworks/ProtocolBuffers.md), [Thrift](Frameworks/Thrift.md), [Avro](Frameworks/Avro.md).

# Features
- [Interface Description Language (IDL)](Frameworks/IDL.md)
- Performance (better than JSON/XML)
- Versioning (through field identifier)
- Binary Format

# Modeling Steps
- Write down a bunch of struct-like message formats in an [IDL-like language](Frameworks/IDL.md).
- Run a tool to generate boilerplate code.
- Link against the boilerplate code when building the application.

# Example Code

![](https://image.slidesharecdn.com/pbvsthriftvsavro-120917080012-phpapp02/75/thrift-vs-protocol-buffers-vs-avro-biased-comparison-23-2048.jpg)

# Read more
- [Thrift vs Protocol Buffers vs Avro - Biased Comparison](https://www.slideshare.net/IgorAnishchenko/pb-vs-thrift-vs-avro)