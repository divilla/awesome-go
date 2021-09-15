# awesome-go
A curated list of awesome Go frameworks, libraries and software

## README.md GitHub guide

* [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

* [GitHub Flavored Markdown Spec](https://github.github.com/gfm/https://github.github.com/gfm)

## Web frameworks

* [echo](https://github.com/labstack/echo) - high performance, minimalist Go web frameworkHigh performance, minimalist Go web framework.

* [Gin Web Framework](https://github.com/gin-gonic/gin) - features a martini-like API with performance that is up to 40 times faster thanks to [httprouter](https://github.com/julienschmidt/httprouter).
  If you need performance and good productivity, you will love Gin.

* [Iris Web Framework](https://github.com/kataras/iris) - fastest HTTP/2 Go Web Framework.
  AWS Lambda, gRPC, MVC, Unique Router, Websockets, Sessions, Test suite, Dependency Injection and more.
  A true successor of expressjs and laravel.

## Microservices frameworks

* [Go kit](https://github.com/go-kit/kit) - **programming toolkit** for building microservices (or elegant monoliths) in Go.
  We solve common problems in distributed systems and application architecture, so you can focus on delivering business value.

* [Go Micro](https://github.com/asim/go-micro) - provides the core requirements for distributed systems development including RPC and Event driven communication.
  The **Micro** philosophy is sane defaults with a pluggable architecture.
  We provide defaults to get you started quickly but everything can be easily swapped out.

## Testing & Benchmarking

* [Testify](https://github.com/stretchr/testify) - is set of packages that assist in testing code.
  The `assert` package provides assert functions.
  The `require` package provides same global functions as the `assert` package, but instead of returning a boolean result they terminate current test.
  The `mock` package provides a mechanism for easily writing mock objects that can be used in place of real objects when writing test code.
  The `suite` package provides functionality that you might be used to from more common object oriented languages.  With it, you can build a testing suite as a struct, build setup/teardown methods and testing methods on your struct, and run them with 'go test' as per normal.

* [bombardier](https://github.com/codesenberg/bombardier) - is an HTTP(S) benchmarking tool. It is written in Go programming language and uses excellent [fasthttp](https://github.com/valyala/fasthttp)
  instead of Go's default http library, because of its lightning fast performance.
  With `bombardier v1.1` and higher you can now use `net/http` client if you need to test HTTP/2.x services or want to use a more RFC-compliant HTTP client.

## gRPC

* [gRPC-Go](https://github.com/grpc/grpc-go) - The [Go](https://golang.org/) implementation of [gRPC](https://grpc.io/): A high performance, open source, general
  RPC framework that puts mobile and HTTP/2 first. For more information see the
  [Go gRPC docs](https://grpc.io/docs/languages/go), or jump directly into the [quick start](https://grpc.io/docs/languages/go/quickstart).

## HTML templating engines

* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine for Go. Optimized for speed, zero memory allocations in hot paths. Up to 20x faster than html/template. Inspired by the [Mako templates](http://www.makotemplates.org/) philosophy.

* [amber](https://github.com/eknkc/amber) - elegant templating engine for Go Programming Language It is inspired from HAML and Jade.

* [Blocks](https://github.com/kataras/blocks) - simple, Go-idiomatic view engine based on html/template with some extra features.

* [pongo2](https://github.com/flosch/pongo2) - Django-syntax like templating-language ([official website](https://www.schlachter.tech/solutions/pongo2-template-engine/)).

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

* [fastjson](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go.
  No custom structs, no code generation, no reflection. Outperforms [GJSON](https://github.com/tidwall/gjson) when accessing multiple unrelated fields.

* [GJSON](https://github.com/tidwall/gjson) - provides a fast and simple way to get values from a json document. It has features such as one line retrieval, dot notation paths, iteration, and parsing json lines.

* [SJSON](https://github.com/tidwall/sjson) - provides a very fast and simple way to set a value in a json document.

* [Pretty](https://github.com/tidwall/pretty) - provides fast methods for formatting JSON for human readability, or to compact JSON for smaller payloads.

* [joi](https://github.com/sideway/joi) - The most powerful data validation library for **JavaScript** & **Node.js**

## Caching

* [CCache](https://github.com/karlseguin/ccache) - LRU Cache, written in Go, focused on supporting high concurrency.
  Supports: Buckets, Layered Cache & TTL.

## Functional programming helpers

* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.

* [singleflight](https://pkg.go.dev/golang.org/x/sync/singleflight) - provides a duplicate function call suppression mechanism.

## Maps & slices helpers

* [gofp](https://github.com/rbrahul/gofp) - A lodash like powerful utility library for Golang.

## RESTful API Server builders & generators

* [apig](https://github.com/shimastripe/apig) - RESTful API server generator.
  **Input**: Model definitions based on [gorm](https://github.com/jinzhu/gorm) annotated struct
  **Output**: RESTful JSON API server using [gin](https://github.com/gin-gonic/gin) including tests and documents.

* [REST Layer](https://github.com/rs/rest-layer) - is an API framework heavily inspired by the excellent [Python Eve](http://python-eve.org). 
  It helps you create a comprehensive, customizable, and secure REST (graph) API on top of pluggable [backend storages](#main-storage-handlers) 
  with no boiler plate code so you can focus on your business logic.

## Web servers

* [Caddy](https://github.com/caddyserver/caddy) - powerful, enterprise-ready, open source web server with automatic HTTPS written in Go

## Computer vision & recognition

* [gocv](https://github.com/hybridgroup/gocv) - The GoCV package provides Go language bindings for the [OpenCV 4](http://opencv.org/) computer vision library.
  
## Other

* [Regex Cheat-sheet](https://yourbasic.org/golang/regexp-cheat-sheet/)