# grpc-golang-server

protobuff are used for faster communications between consumers and providers.

To generate code form proto config 
 - protoc --proto_path=proto --go_out=plugins=grpc:proto proto\service.proto

Run the both client and Provider.

go run src/main.go - provider

go run src/client/main.go - client