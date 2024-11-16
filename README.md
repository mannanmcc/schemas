

Install protoc:
$ brew install protobuf
Generate protobuf
$ protoc -I=proto --go_out=build proto/rpc/order/*.proto
$ protoc -I=proto proto/rpc/order/*.proto --go-grpc_out=build