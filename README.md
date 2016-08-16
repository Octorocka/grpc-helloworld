# Introduction

It's the gRPC hello world application. The example code is from [grpc/grpc](https://github.com/grpc/grpc/tree/master/examples/python/helloworld).

## Usage

Start gRPC server.

```
docker run -d -p 50051:50051 tobegit3hub/grpc-helloworld
```

Start gRPC client.

```
./greeter_client.py
```
