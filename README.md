# setup env
- Cài golang: https://golang.org/dl/
- Cài protocol buffer: https://github.com/google/protobuf/releases --> Giải nén vào C:\proto3
- Setup biến môi trường cho protocol buffer --> Thêm C:\proto3\bin vào PATH system variables

# setup dependencies
- Cài gRPC-Go: go get -u google.golang.org/grpc
- Cài protoc-gen-go: go get -u github.com/golang/protobuf/protoc-gen-go

# run project greet: Unary, server stream, client stream, bi-directioning API
- 1. Open terminal
- 2. Cài package: go get -u github.com/simplesteph/grpc-go-course/greet/greetpb
- 3. Run server: go run greet/greet_server/server.go
- 4. Run client: go run greet/greet_client/client.go

# run project calculator: Unary, server stream, client stream, bi-directioning API
- 1. Open terminal
- 2. Cài package: go get -u github.com/simplesteph/grpc-go-course/calculator/calculatorpb
- 3. Run server: go run calculator/calculator_server/server.go
- 4. Run client: go run calculator/calculator_client/client.go

# run project blog: CRUD APIS
- 1. Cài mongodb: https://www.mongodb.com/try/download/community
- 2. Cài mongo driver: go get -u go.mongodb.org/mongo-driver/mongo
- 3. Cài package: go get -u github.com/simplesteph/grpc-go-course/blog/blogpb
- 4. Run server: go run blog/blog_server/server.go
- 5. Run client: go run blog/blog_client/client.go
