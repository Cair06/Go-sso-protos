after creating gen/go/sso/ dir, adn after proto/sso/sso.proto file:

- protoc -I proto proto/sso/sso.proto --go_out=./gen/go --go_opt=paths=source_relative --go-grpc_out=./gen/go/ --go-grpc_opt=paths=source_relative

for future if we have new version

- git tag v0.0.1 (.2,.3, ...)