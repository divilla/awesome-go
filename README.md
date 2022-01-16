# awesome-go
A curated list of awesome Go frameworks, libraries and software

* [GolangRepo](https://golangrepo.com)

## README.md GitHub guide

* [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

* [GitHub Flavored Markdown Spec](https://github.github.com/gfm/https://github.github.com/gfm)

* [UTF-8 Symbols](https://www.w3schools.com/charsets/ref_utf_symbols.asp)

## Web frameworks

* [Gin Web Framework](https://github.com/gin-gonic/gin) - features a martini-like API with performance that is up to 40 times faster thanks to [httprouter](https://github.com/julienschmidt/httprouter). If you need performance and good productivity, you will love Gin.  
&#9733; 53.1k &#9830; **2021-11-24** &#9830; [gin-gonic.com](https://gin-gonic.com)

* [Beego](https://github.com/beego/beego) - high-performance web framework used for rapid development of enterprise application in Go, including RESTful APIs, web apps and backend services. It is inspired by Tornado, Sinatra and Flask. beego has some Go-specific features such as interfaces and struct embedding.  
&#9733; 27.2k &#9830; **2020-12-14** &#9830; [beego.me](http://beego.me)

* [Iris Web Framework](https://github.com/kataras/iris) - fastest HTTP/2 Go Web Framework. AWS Lambda, gRPC, MVC, Unique Router, Websockets, Sessions, Test suite, Dependency Injection and more. A true successor of expressjs and laravel.  
&#9733; 21.4k &#9830; **2021-12-02** &#9830; [iris-go.com](https://iris-go.com)

* [echo](https://github.com/labstack/echo) - high performance, minimalist Go web frameworkHigh performance, minimalist Go web framework.  
&#9733; 21.1k &#9830; **2022-01-11** &#9830; [echo.labstack.com](https://echo.labstack.com)

* [Fiber](https://github.com/gofiber/fiber) - Express inspired web framework built on top of [fasthttp](https://github.com/valyala/fasthttp), the fastest HTTP engine for Go. Designed to ease things up for fast development with zero memory allocation and performance in mind.  
&#9733; 16.4k &#9830; **2021-12-31** &#9830; [gofiber.io](https://gofiber.io)

* [Kratos](https://github.com/go-kratos/kratos) - microservice-oriented governance framework implemented by golang, which offers convenient capabilities to help you quickly build a bulletproof application from scratch.  
&#9733; 15.5k &#9830; **2022-01-05** &#9830; [go-kratos.dev](https://go-kratos.dev/)

* [go-zero](https://github.com/zeromicro/go-zero) - web and rpc framework written in Go. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.  
&#9733; 12.6k &#9830; **2022-01-08** &#9830; [go-zero.dev](https://go-zero.dev)

* [Micro](https://github.com/micro/micro) - addresses the key requirements for building services in the cloud. It leverages the microservices architecture pattern and provides a set of services which act as the building blocks of a platform. Micro deals with the complexity of distributed systems and provides simpler programmable abstractions to build on. [Micro Services](https://github.com/micro/services) - Programmable real world Micro services.  
&#9733; 10.7k &#9830; **2022-01-14** &#9830; [micro.mu](https://micro.mu)

## Middleware & framework integrations

* [echo-swagger](https://github.com/swaggo/echo-swagger) - echo middleware to automatically generate RESTful API documentation with Swagger 2.0

## Microservices frameworks

* [Go kit](https://github.com/go-kit/kit) - **programming toolkit** for building microservices (or elegant monoliths) in Go. We solve common problems in distributed systems and application architecture, so you can focus on delivering business value.

* [Go Micro](https://github.com/asim/go-micro) - provides the core requirements for distributed systems development including RPC and Event driven communication.
  The **Micro** philosophy is sane defaults with a pluggable architecture.
  We provide defaults to get you started quickly but everything can be easily swapped out.

## Enterprise frameworks & toolkits

* [Go Util](https://github.com/gookit/goutil) - utils: string, array/slice, map, format, CLI, ENV, filesystem, testing and more.  
&#9733; 464 &#9830; [github.com/gookit/goutil](https://pkg.go.dev/github.com/gookit/goutil)

* [Config](https://github.com/gookit/config) - config manager (load,get,set). support JSON, YAML, TOML, INI, HCL, ENV and Flags. Multi file load, data override merge, parse ENV var.  
&#9733; 304 &#9830; [github.com/gookit/config](https://pgk.go.dev/github.com/gookit/config)

* [Events](https://github.com/gookit/event) - Lightweight event manager and dispatcher   
&#9733; 189 &#9830; [github.com/gookit/event](https://pgk.go.dev/github.com/gookit/event)

* [Filter](https://github.com/gookit/filter) - provides filtering, sanitizing, and conversion of Golang data.  
&#9733; 48 &#9830; [godoc.org/github.com/gookit/filter](https://godoc.org/github.com/gookit/filter)

* [securecookie](https://github.com/gorilla/securecookie) - encodes and decodes authenticated and optionally encrypted cookie values for Go web applications.  
&#9733; 555 - &#9830; [www.gorillatoolkit.org/pkg/securecookie](http://www.gorillatoolkit.org/pkg/securecookie)


## Testing & Benchmarking

* [Testify](https://github.com/stretchr/testify) - is set of packages that assist in testing code.
  The `assert` package provides assert functions.
  The `require` package provides same global functions as the `assert` package, but instead of returning a boolean result they terminate current test.
  The `mock` package provides a mechanism for easily writing mock objects that can be used in place of real objects when writing test code.
  The `suite` package provides functionality that you might be used to from more common object oriented languages.  With it, you can build a testing suite as a struct, build setup/teardown methods and testing methods on your struct, and run them with 'go test' as per normal.

* [bombardier](https://github.com/codesenberg/bombardier) - is an HTTP(S) benchmarking tool. It is written in Go programming language and uses excellent [fasthttp](https://github.com/valyala/fasthttp)
  instead of Go's default http library, because of its lightning fast performance.
  With `bombardier v1.1` and higher you can now use `net/http` client if you need to test HTTP/2.x services or want to use a more RFC-compliant HTTP client.

## HTML template engines

* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine for Go. Optimized for speed, zero memory allocations in hot paths. Up to 20x faster than html/template. Inspired by the [Mako templates](http://www.makotemplates.org/) philosophy.  
&#9733; 2.3k

* [pongo2](https://github.com/flosch/pongo2) - Django-syntax like templating-language ([official website](https://www.schlachter.tech/solutions/pongo2-template-engine/)).  
&#9733; 2.1k &#9830; [www.schlachter.tech/pongo2](https://www.schlachter.tech/pongo2)

* [plush](https://github.com/gobuffalo/plush) - The powerful template system that Go needs.  
&#9733; 681

* [amber](https://github.com/eknkc/amber) - elegant templating engine for Go Programming Language It is inspired from HAML and Jade.  
&#9733; 886 &#9830; **Unmaintained**

* [Blocks](https://github.com/kataras/blocks) - simple, Go-idiomatic view engine based on html/template with some extra features.  
&#9733; 27

## HTML utilities

* [html](https://pkg.go.dev/golang.org/x/net/html) - implements an HTML5-compliant tokenizer and parser.

* [htmlquery](https://github.com/antchfx/htmlquery) - is an XPath query package for HTML,
  lets you extract data or evaluate from HTML documents by an XPath expression.
  Built-in the query object caching feature based on [LRU](https://godoc.org/github.com/golang/groupcache/lru),
  this feature will caching the recently used XPATH query string.
  Enable query caching can avoid re-compile XPath expression each query.

* [goquery](https://github.com/PuerkitoBio/goquery) - brings a syntax and a set of features similar to [jQuery](https://jquery.com) to the Go language. It is based on Go's net/html package and the CSS Selector library [cascadia](https://github.com/andybalholm/cascadia). Since the net/html parser returns nodes, and not a full-featured DOM tree, jQuery's stateful manipulation functions (like height(), css(), detach()) have been left off.

* [cascadia](https://github.com/andybalholm/cascadia) - CSS selectors Go library

## Email utilities

* [Hermes](https://github.com/matcornic/hermes) - Hermes is the Go port of the great [mailgen](https://github.com/eladnava/mailgen) engine for Node.js. Check their work, it's awesome! It's a package that generates clean, responsive HTML e-mails for sending transactional e-mails (welcome e-mails, reset password e-mails, receipt e-mails and so on), and associated plain text fallback.

## Crawlers, scrapers, spiders

* [Colly](https://github.com/gocolly/colly) - Lightning Fast and Elegant Scraping Framework for Gophers. With Colly you can easily extract structured data from websites, which can be used for a wide range of applications, like data mining, data processing or archiving.

## JSON parsers & validators

* [jsoniter](https://github.com/json-iterator/go) - high-performance 100% compatible drop-in replacement of "encoding/json".  
&#9733; 10k

* [easyjson](https://github.com/mailru/easyjson) - fast and easy way to marshal/unmarshal Go structs to/from JSON without the use of reflection. Ability to customize the generated code by providing options not available with the standard encoding/json package, such as generating "snake_case" names or enabling omitempty behavior by default.  
&#9733; 3.5k

* [fastjson](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection. Outperforms [GJSON](https://github.com/tidwall/gjson) when accessing multiple unrelated fields.  
&#9733; 1.4k

* [GJSON](https://github.com/tidwall/gjson) - provides a fast and simple way to get values from a json document. It has features such as one line retrieval, dot notation paths, iteration, and parsing json lines.  
&#9733; 9.3k

* [SJSON](https://github.com/tidwall/sjson) - provides a very fast and simple way to set a value in a json document.  
&#9733; 1.5k

* [Pretty](https://github.com/tidwall/pretty) - provides fast methods for formatting JSON for human readability, or to compact JSON for smaller payloads.

## Data structures

* [skipmap](https://github.com/zhangyunhao116/skipmap) - high-performance, scalable concurrent sorted map based on skip-list. Up to 10x faster than sync.Map in the typical pattern.

* [concurrent map](https://github.com/orcaman/concurrent-map) - a thread-safe concurrent map for go

* [golang-lru](https://github.com/hashicorp/golang-lru) - provides the lru package which implements a fixed-size thread safe LRU cache. (Hashicorp)

## Embedded DB & Caching

* [BadgerDB](https://github.com/dgraph-io/badger) - an embeddable, persistent and fast key-value (KV) database written in pure Go. Fastest read speed. Supports TTL. Supports concurrent ACID transactions with serializable snapshot isolation (SSI) guarantees. (2021 - reference)  
&#9733; 10.3k &#9830; **2021-10-07** &#9830; [blog.dgraph.io/post/badger](https://blog.dgraph.io/post/badger/)

* [immudb](https://github.com/codenotary/immudb) - immutable database based on zero trust, SQL and Key-Value, tamperproof, data change history  
&#9733; 6.8k &#9830; **2022-01-12**  &#9830; [docs.immudb.io/master](https://docs.immudb.io/master/)

* [BBolt](https://github.com/etcd-io/bbolt) - an embedded key/value database for Go.  
&#9733; 5.1k &#9830; **2021-06-17** &#9830; [go.etcd.io/bbolt](https://go.etcd.io/bbolt)

* [tiedot](https://github.com/HouzuoGuo/tiedot) - document database engine that uses JSON as document notation; it has a powerful query processor that supports advanced set operations; it can be embedded into your program, or run a stand-alone server using HTTP (2017)  
&#9733; 2.7k &#9830; **2021-05-93**

* [column](https://github.com/kelindar/column) - high-performance, columnar, in-memory storage engine that supports fast querying, update and iteration with zero-allocations, bitmap indexing, TTL, transactions and streaming messages. (2021 - reference)
&#9733; 856 &#9830; **2022-01-01** &#9830; [blog.dgraph.io/post/badger](https://blog.dgraph.io/post/badger/)

* [IceFireDB](https://github.com/IceFireDB/IceFireDB) - distributed disk storage database based on Raft and Redis protocol.  
&#9733; 724 &#9830; **2022-01-13** &#9830; [www.icefiredb.com](https://www.icefiredb.com/)

* [CCache](https://github.com/karlseguin/ccache) - LRU Cache, written in Go, focused on supporting high concurrency. Supports: Hashed buckets, Layered Cache & TTL.  
&#9733; 877 &#9830; **2021-02-06**

* [GhostDB](https://github.com/jakekgrog/GhostDB) - distributed, in-memory, general purpose key-value data store that delivers microsecond performance at any scale. Supports persistance and point in time recovery.  
&#9733; 712 &#9830; **2021-03-10** &#9830; [www.ghostdbcache.com](http://www.ghostdbcache.com/)

* [uhaha](https://github.com/tidwall/uhaha) - framework for building highly available Raft-based data applications in Go. Small footprint, TLS and Auth password support. Multiple examples to help jumpstart integration, including a Key-value DB, a Timeseries DB, and a Ticket Service. (2021 - not mature)  
&#9733; 364 &#9830; **2021-10-07**

## Database migration

* [migrate](https://github.com/golang-migrate/migrate) - database migrations. CLI and Golang library.

## Message brokers

* [Mist](https://github.com/nanopack/mist) - distributed, tag-based pub-sub service for modern web applications and container-driven cloud.

* [yarpc](https://github.com/yarpc/yarpc-go) - message passing platform for Go

* [Event](https://github.com/gookit/event) - lightweight event manager and dispatcher

* [relay](https://github.com/armon/relay) - framework for simple message passing using an AMQP broker

## Functional programming helpers

* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.

* [singleflight](https://pkg.go.dev/golang.org/x/sync/singleflight) - provides a duplicate function call suppression mechanism.

## Maps & slices helpers

* [gofp](https://github.com/rbrahul/gofp) - A lodash like powerful utility library for Golang.

* [objx](https://github.com/stretchr/objx) - package for dealing with maps, slices, JSON and other data.

## RESTful API Server builders & generators

* [apig](https://github.com/shimastripe/apig) - RESTful API server generator.
  **Input**: Model definitions based on [gorm](https://github.com/jinzhu/gorm) annotated struct
  **Output**: RESTful JSON API server using [gin](https://github.com/gin-gonic/gin) including tests and documents.

* [REST Layer](https://github.com/rs/rest-layer) - is an API framework heavily inspired by the excellent [Python Eve](http://python-eve.org). It helps you create a comprehensive, customizable, and secure REST (graph) API on top of pluggable [backend storages](#main-storage-handlers) with no boiler plate code so you can focus on your business logic.

* [DBCore (ALPHA)](https://github.com/eatonphil/dbcore) - code generator build around database schemas and an API specification. Included with DBCore are templates for generating a Go REST API and React UI.

## SQL Builders

* [gosql](https://github.com/rushteam/gosql) - orm and sql builder

* [dbr](https://github.com/mailru/dbr) - query builder and other additions to Go's database/sql for super fast performance and convenience.

* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - db driver and query builder (reference)

* [fuckdb](https://github.com/hantmac/fuckdb) - generates a go compatible struct type with the required column names, data types, and annotations just fill in the database information in the web UI. Making go web develop very easy by saving a lot of time writing structure.fuckdbis based/inspired by the work of Seth Shelnutt's db2struct, and Db2Struct is based/inspired by the work of ChimeraCoder's gojson package gojson.

* [DBQ](https://github.com/rocketlaunchr/dbq) - lightweight Dapper like db driver for PostgreSQl and MySQL

* [MaxMind DB Reader](https://github.com/oschwald/maxminddb-golang) - MaxMind DB Reader for Go

## Validators

* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - idiomatic Go (golang) validation package. Supports configurable and extensible validation rules (validators) using normal language constructs instead of error-prone struct tags.

* [govalidator](https://github.com/asaskevich/govalidator) - package of validators and sanitizers for strings, numerics, slices and structs.

## Web servers

* [Caddy](https://github.com/caddyserver/caddy) - powerful, enterprise-ready, open source web server with automatic HTTPS written in Go

## WebSocket

* [Gorilla WebSocket](https://github.com/gorilla/websocket) - Go implementation of the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol.

* [recws](https://github.com/recws-org/recws) - reconnecting WebSocket is a websocket client based on gorilla/websocket that will automatically reconnect if the connection is dropped and keeps the connection alive - thread safe!

## Computer vision & recognition

* [gocv](https://github.com/hybridgroup/gocv) - package provides Go language bindings for the [OpenCV 4](http://opencv.org/) computer vision library.

## Blockchain

* [Tendermint](https://github.com/tendermint/tendermint) - Byzantine Fault Tolerant (BFT) middleware that takes a state transition machine - written in any programming language - and securely replicates it on many machines. Or Blockchain, for short.

* [blackholeDB](https://github.com/bregydoc/blackholeDB) - conceptual Key-Value distributed Database. HoleDB uses IPFS as decentralized filesystem, and BadgerDB as store for local key value pairs. (work in progress)

* [go-orbit-db](https://github.com/berty/go-orbit-db) - distributed peer-to-peer database on IPFS. This project intends to provide a fully compatible port of the JavaScript version in Go.

## Tools

* [nightingale](https://github.com/didi/nightingale) - Distributed and High-Performance Monitoring System. Prometheus enterprise UI  
&#9733; 3.5k - &#9830; [n9e.github.io](https://n9e.github.io/)

* [golangci-lint](https://github.com/golangci/golangci-lint) - fast Go linters runner. It runs linters in parallel, uses caching, supports yaml config, has integrations with all major IDE and has dozens of linters included.

## Other

* [Consul](https://github.com/hashicorp/consul) - distributed, highly available, and data center aware solution to connect and configure applications across dynamic, distributed infrastructure.

* [laitos](https://github.com/HouzuoGuo/laitos) - top geek's chindogu - personal assistant over satellite/telephone/SMS/chatbot, plus web infrastructure servers (web & mail, ad-free DNS, web proxy, SNMP, etc)

* [make-test](https://github.com/iconmobile-dev/go-interview/tree/master/make) - creates great testing display

* [Regex Cheat-sheet](https://yourbasic.org/golang/regexp-cheat-sheet/)

* [Git In Practice](https://github.com/MikeMcQuaid/GitInPractice) - opinionated, intermediate/advanced-level Git book

## Gist

* [Mutex vs Channel in concurrent map](https://gist.github.com/cyfdecyf/4562635)

## Architecture

* [The Twelve-Factor App](https://12factor.net/) - methodology for building software-as-a-service apps

## gRPC

* [gRPC-Go](https://github.com/grpc/grpc-go) - The [Go](https://golang.org/) implementation of [gRPC](https://grpc.io/): A high performance, open source, general RPC framework that puts mobile and HTTP/2 first. For more information see the
* [Go gRPC docs](https://grpc.io/docs/languages/go), or jump directly into the [quick start](https://grpc.io/docs/languages/go/quickstart).

## Node.js

* [joi](https://github.com/sideway/joi) - the most powerful data validation library for **JavaScript** & **Node.js**

* [Ultimate SAAS template](https://github.com/gmpetrov/ultimate-saas-ts) - quickstart a SAAS business
