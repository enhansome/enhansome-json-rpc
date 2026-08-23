# awesome-json-rpc with stars

Curated list of JSON-RPC resources.

## Contents

<!-- TOC -->

* [What is JSON-RPC?](#what-is-json-rpc)
* [Official](#official)
* [Libraries](#libraries)
* [Framework Integrations](#framework-integrations)
* [Tools](#tools)
* [Interface Description](#interface-description)
* [Uses of JSON-RPC](#uses-of-json-rpc)

<!-- /TOC -->

#### What is JSON-RPC?

JSON-RPC is a remote procedure call protocol used by microservices, IoT and cryptocurrencies to expose APIs. It is a very simple protocol, defining only a few data types and commands. JSON-RPC allows for notifications (data sent to the server that does not require a response) and for multiple calls to be sent to the server which may be answered out of order.

## Official

* [JSON-RPC - Wikipedia](https://en.wikipedia.org/wiki/JSON-RPC) - Informative JSON-RPC Wikipedia article.
* [JSON-RPC](https://www.jsonrpc.org/) - A stateless, light-weight remote procedure call (RPC) protocol.
* [JSON-RPC.info](https://json-rpc.info/) - Historical use cases of JSON-RPC.
* [JSON-RPC Google Group](https://groups.google.com/forum/#!forum/json-rpc) - Some useful historical conversations around JSON-RPC.

## Libraries

* Javascript
  * [Jayson](https://github.com/tedeh/jayson) ⭐ 726 | 🐛 1 | 🌐 JavaScript | 📅 2025-12-22 - Jayson is a simple but featureful JSON-RPC 2.0/1.0 client and server for node.js
  * [jsonrpc-bidirectional](https://github.com/bigstepinc/jsonrpc-bidirectional) ⭐ 113 | 🐛 4 | 🌐 JavaScript | 📅 2022-05-27 - Bidirectional RPC over WebSocket, Worker, WebRTC and HTTP with extensive plugin support.
  * [node-mole-rpc](https://github.com/koorchik/node-mole-rpc) ⭐ 63 | 🐛 13 | 🌐 JavaScript | 📅 2024-04-11 - Tiny transport agnostic JSON-RPC 2.0 client and server which can work everywhere. NodeJs, Browser, Electron. On any transport; Even custom.
    * [node-mole-rpc-transport-ws](https://github.com/koorchik/node-mole-rpc-transport-ws) ⭐ 4 | 🐛 3 | 🌐 JavaScript | 📅 2024-06-18 - WebSocket(ws) transport for Mole-RPC (JSON RPC library)

    * [node-mole-rpc-transport-mqtt](https://github.com/koorchik/node-mole-rpc-transport-mqtt) ⭐ 2 | 🐛 3 | 🌐 JavaScript | 📅 2024-11-19 - MQTT transport for Mole-RPC (JSON RPC library)

    * [node-mole-rpc-transport-webworker](https://github.com/koorchik/node-mole-rpc-transport-webworker) ⭐ 2 | 🐛 4 | 🌐 JavaScript | 📅 2023-01-09 - Easy way to communicate with webworker using Mole-RPC (JSON RPC library)

    * [node-mole-rpc-transport-eventemitter](https://github.com/koorchik/node-mole-rpc-transport-eventemitter) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2022-11-26 - Event Emitter Mole RPC (JSON RPC library) transport
  * [mqtt-json-rpc](https://github.com/rse/mqtt-json-rpc) ⭐ 40 | 🐛 3 | 🌐 TypeScript | 📅 2026-06-29 - JSON-RPC over mqtt
  * [pmrpc](https://github.com/statianzo/pmrpc) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2020-05-03 - JSON-RPC over html5 postMessage
  * [multi-transport-jsonrpc](https://www.npmjs.com/package/multitransport-jsonrpc) - Provides a JSON-RPC solution for both the traditional HTTP scenario as well as for persistent, raw TCP connections.

* Swift
  * [JSONRPCKit](https://github.com/bricklife/JSONRPCKit) ⚠️ Archived - A type-safe JSON-RPC 2.0 library purely written in Swift.

* .NET
  * [Microsoft/vs-streamjsonrpc](https://github.com/Microsoft/vs-streamjsonrpc) ⭐ 935 | 🐛 60 | 🌐 C# | 📅 2026-08-22 - The StreamJsonRpc library offers JSON-RPC 2.0 over any .NET Stream, WebSocket, or Pipe. With bonus support for request cancellation, client proxy generation, and more.
  * [JSON-RPC.NET](https://github.com/Astn/JSON-RPC.NET) ⭐ 328 | 🐛 21 | 🌐 C# | 📅 2024-03-12 - JSON-RPC.Net is a high performance Json-Rpc 2.0 server, leveraging the popular JSON.NET library. Host in ASP.NET, also supports sockets and pipes, oh my!
  * [JsonRpc.Router](https://github.com/edjCase/JsonRpc) ⭐ 145 | 🐛 10 | 🌐 C# | 📅 2025-03-18 - A .NetStandard 2.0 IRouter implementation for Json Rpc v2 requests for Microsoft.AspNetCore.Routing.

* Nim
  * [nim-json-rpc](https://github.com/status-im/nim-json-rpc) ⭐ 101 | 🐛 9 | 🌐 Nim | 📅 2026-08-19 - Nim library for implementing JSON-RPC clients and servers

* Golang
  * [hyperledger/burrow](https://github.com/hyperledger/burrow/tree/master/rpc) ⚠️ Archived - Burrow is a fully fledged blockchain node and smart contract execution engine, with an RPC service!
  * [osamingo/jsonrpc](https://github.com/osamingo/jsonrpc) ⭐ 193 | 🐛 6 | 🌐 Go | 📅 2025-03-28 - The jsonrpc package helps implement of JSON-RPC 2.0 in golang
  * [go-ethereum/rpc](https://godoc.org/github.com/ethereum/go-ethereum/rpc) - Package rpc implements bi-directional JSON-RPC 2.0 on multiple transports.

* Python
  * [pavlov99](https://github.com/pavlov99/json-rpc) ⭐ 490 | 🐛 24 | 🌐 Python | 📅 2025-03-17 - JSON-RPC 1/2 transport implementation. Supports python 2/3 and pypy.

* PHP
  * [EvilScott/junior](https://github.com/EvilScott/junior) ⭐ 40 | 🐛 1 | 🌐 PHP | 📅 2026-04-18 - PHP client/server library for JSON-RPC 2.0

* C
  * [cesanta/mjson](https://github.com/cesanta/mjson) ⭐ 466 | 🐛 26 | 🌐 C | 📅 2025-03-05 - C/C++ JSON parser, emitter, JSON-RPC engine for embedded systems

* Ruby
  * [helios-technologies/json-rpc](https://github.com/helios-technologies/json-rpc) ⭐ 12 | 🐛 1 | 🌐 Ruby | 📅 2011-07-27 - Implementation of JSON RPC 2.0 protocol. It allows you to create easily a json rpc server in pure Rack, in Rails, or asynchronous using Thin and EventMachine.

## Framework Integrations

* [Loopback JSON-RPC connector](https://loopback.io/doc/en/lb2/JSON-RPC-connector.html)
* [Django JSON-RPC](https://github.com/samuraisam/django-json-rpc) ⭐ 287 | 🐛 21 | 🌐 Python | 📅 2019-02-20

## Tools

* [ApEye.org](https://apeye.org) - APEye is a jQuery widget for issuing HTTP requests
* [JSON-RPC 2.0 Shell](http://software.dzhuvinov.com/json-rpc-2.0-shell.html) - Interactive RPC shell for rapid querying, testing and
  debugging of JSON-RPC 2.0 web services

### Interface Description

* [open-rpc/spec](https://github.com/open-rpc/spec) ⭐ 215 | 🐛 30 | 🌐 TypeScript | 📅 2026-02-25 - Specification for OpenRPC
* [open-rpc/generator-client](https://github.com/open-rpc/generator-client) ⭐ 98 | 🐛 23 | 🌐 TypeScript | 📅 2025-10-22 - Mono repo for the client generators for each target language
* [open-rpc/examples](https://github.com/open-rpc/examples) ⭐ 57 | 🐛 4 | 🌐 TypeScript | 📅 2025-11-18 - Collection of example open-rpc documents
* [open-rpc/meta-schema](https://github.com/open-rpc/meta-schema) ⭐ 34 | 🐛 14 | 🌐 Go | 📅 2026-02-04 - JSON Schema file representing the open-rpc specification.
* [open-rpc/editor-extensions-vscode](https://github.com/open-rpc/editor-extensions-vscode) ⭐ 12 | 🐛 17 | 🌐 TypeScript | 📅 2022-12-08 - A vscode extension to provide validation and auto-completion for open-rpc documents.
* [open-rpc/docs-react](https://github.com/open-rpc/docs-react) ⭐ 10 | 🐛 35 | 🌐 TypeScript | 📅 2021-08-03 - OpenRPC documentation as a react component.
* [open-rpc.org](https://open-rpc.org) - A standard, programming language-agnostic interface description for JSON-RPC 2.0 APIs.
* [open-rpc/playground](https://playground.open-rpc.org) - A play to play around with OpenRPC.
* [open-rpc/inspector](https://inspector.open-rpc.org) - OpenRPC Inspector is a simple tool to create, modify and execute JSON-RPC requests.

#### Uses of JSON-RPC

* [Dogecoin](https://github.com/dogecoin/dogecoin) ⭐ 15,258 | 🐛 305 | 🌐 C++ | 📅 2026-08-15 - Dogecoin is a cryptocurrency featuring a likeness of the Shiba Inu dog from the "Doge" Internet meme as its logo.
* [Monero](https://github.com/monero-project/monero) ⭐ 10,788 | 🐛 700 | 🌐 C++ | 📅 2026-08-23 - the secure, private, untraceable cryptocurrency.
* [Zcash](https://github.com/zcash/zcash) ⚠️ Archived - Zcash is a cryptocurrency aimed at using cryptography to provide enhanced privacy for its users compared to other cryptocurrencies such as Bitcoin.
* [Quorum](https://github.com/jpmorganchase/quorum) ⚠️ Archived - A permissioned implementation of Ethereum supporting data privacy.
* [Litecoin](https://github.com/litecoin-project/litecoin) ⭐ 4,600 | 🐛 104 | 🌐 C++ | 📅 2026-08-23 - Litecoin is a cryptocurrency that enables instant payments to anyone in the world and that can be efficiently mined with consumer-grade hardware.
* [Dash](https://github.com/dashpay/dash) ⭐ 1,541 | 🐛 240 | 🌐 C++ | 📅 2026-08-23 - Dash is Digital Cash You Can Spend Anywhere.
* [Microsoft SQL Tools Service](https://github.com/Microsoft/sqltoolsservice/) ⭐ 507 | 🐛 74 | 🌐 C# | 📅 2026-08-22 - SQL Query and Management over JSON-RPC.
* [Tarantool](https://github.com/tarantool/nginx_upstream_module) ⭐ 173 | 🐛 29 | 🌐 C | 📅 2021-03-02 - Get your data in RAM. Get compute close to data. Enjoy the performance. (Provides nginx upstream module to support JSON-RPC)
* [Ethereum Classic](https://github.com/ethereumproject/wiki/wiki/JSON-RPC) ⚠️ Archived - Ethereum Classic is an open-source, public, blockchain-based distributed computing platform featuring smart contract (scripting) functionality that was a result of the DAO fork.
* [Arm mbed IoT Platform](https://cloud.mbed.com/docs/current/connecting/json-rpc.html#protocol-translator-register) - Arm Mbed OS together with the Pelion IoT Platform provide a transformative device-to-data platform for connected IoT that empowers an intelligent enterprise.
* [Bitcoin](https://en.bitcoinwiki.org/wiki/JSON-RPC) -  Bitcoin is a decentralized cryptocurrency created in 2008 by the pseudonymous Satoshi Nakamoto.
* [Dokuwiki](https://www.dokuwiki.org/devel:jsonrpc) - DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database.
* [Ethereum](https://github.com/ethereum/wiki/wiki/JSON-RPC) - Ethereum is an open-source, public, blockchain-based distributed computing platform and operating system featuring smart contract (scripting) functionality.
* [FreeIPA](https://www.freeipa.org) - Manage Linux users and client hosts in your realm from one central location with CLI, Web UI or RPC access. Enable Single Sign On authentication for all your systems, services and applications.
* [Kodi](https://kodi.wiki/view/JSON-RPC_API) - Kodi is a free media player that is designed to look great on your big screen TV but is just as home on a small screen.
* [Microsoft Language Server](https://docs.microsoft.com/en-us/visualstudio/extensibility/language-server-protocol?view=vs-2017) - Underlying Language Server protocol for vscode
* [OpenDaylight](https://www.opendaylight.org/) - OpenDaylight (ODL) is a modular open platform for customizing and automating networks of any size and scale.
* [PPIO](https://www.pp.io) - A decentralized data storage and delivery platform for developers that value affordability, speed, and privacy.
* [Qtum](https://qtumproject.github.io/qtumjs-doc/) - Qtum is an open sourced public blockchain platform, leveraging the security of UTXO while enabling multiple virtual machines including EVM and the revolutionary x86 VM.
* [RANDOM.ORG](https://api.random.org/json-rpc/1/) - RANDOM.ORG offers true random numbers to anyone on the Internet. The randomness comes from atmospheric noise, which for many purposes is better than the pseudo-random number algorithms typically used in computer programs. People use RANDOM.ORG for holding drawings, lotteries and sweepstakes, to drive online games, for scientific applications and for art and music. The service has existed since 1998 and was built by Dr Mads Haahr of the School of Computer Science and Statistics at Trinity College, Dublin in Ireland. Today, RANDOM.ORG is operated by Randomness and Integrity Services Ltd.
* [Ripple](https://developers.ripple.com/get-started-with-the-rippled-api.html) - Ripple is a real-time gross settlement system, currency exchange and remittance network created by Ripple Labs Inc., a US-based technology company.
* [Visual Studio Language Server Extensions](https://code.visualstudio.com/api/language-extensions/language-server-extension-guide) - The Editor Extensions are build on the Language Server. It's Interface is over JSON-RPC.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._
