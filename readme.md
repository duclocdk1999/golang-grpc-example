protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative \
    helloworld/helloworld.proto

protoc --go_out=chat --go_opt=paths=source_relative --go-grpc_out=chat --go-grpc_opt=paths=source_relative chat.proto

protoc --go-grpc_out=chat --go-grpc_opt=paths=source_relative chat.proto