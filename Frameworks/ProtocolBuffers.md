# Protocol Buffers
- [Protocol Buffers (Protobuf)](https://protobuf.dev/) are Google’s language-neutral, platform-neutral, extensible mechanism for serializing structured data – think XML, but smaller, faster, and simpler.
- You define how you want your data to be structured once, then you can use special generated source code to easily write and read your structured data to and from a variety of data streams and using a variety of languages.

# Real world usages of Protocol Buffers
- gPRC - To define the contracts, gRPC uses a declarative language called [Protocol Buffers (Protobuf)](https://protobuf.dev/).
- Google
- ActiveMQ uses protobuf for message store

# Example Implementation

## Protocol Definition - IDL

````
edition = "2023";

message Person {
  string name = 1;
  int32 id = 2;
  string email = 3;
}
````

##  Using a generated class to persist data

````
// Java code
Person john = Person.newBuilder()
    .setId(1234)
    .setName("John Doe")
    .setEmail("jdoe@example.com")
    .build();
output = new FileOutputStream(args[0]);
john.writeTo(output);
````

### Using a generated class to parse persisted data.


````
// C++ code
Person john;
fstream input(argv[1],
    ios::in | ios::binary);
john.ParseFromIstream(&input);
id = john.id();
name = john.name();
email = john.email();
```