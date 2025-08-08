# Text vs Binary message formats

|             | Text-Based format                                | Binary Format                                           |
|-------------|--------------------------------------------------|---------------------------------------------------------|
| Readability | Human Readable                                   | You’ll need tools like `protoc --decode` to inspect it. |
| Type        | Data-interchange format                          | Serialization frameworks                                |
| Purpose     | Preferred for open/public APIs (especially JSON) | Works great for service-to-service communication, APIs, and stored binary data      |

# Read more
- [JSON vs Protocol Buffer Simplified](https://sakshichahal53.medium.com/json-vs-protocol-buffer-simplified-dbd6b69ca528)
