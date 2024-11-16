

Install protoc:
$ brew install protobuf
Generate protobuf
$ protoc --proto_path=proto --go_out=build/go --go_opt=paths=source_relative proto/rpc/order/*.proto
$ protoc --proto_path=proto --go-grpc_out=build/go --go-grpc_opt=paths=source_relative proto/rpc/order/*.proto