[![GoDoc](https://godoc.org/github.com/jacobsa/reqtrace?status.svg)](https://godoc.org/github.com/jacobsa/reqtrace)

reqtrace is a package for simple request tracing. It requires nothing of its
user except:

 *  They must use [golang.org/x/net/context][context].
 *  They must add a single line to each function they want to be visible in
    traces.

[context]: http://godoc.org/golang.org/x/net/context

In particular, reqtrace is console-based and doesn't require an HTTP server.

**Warning**: This package is still barebones and in its early days. I reserve
the right to make backwards-incompatible changes to its API. But if it's useful
to you in your current form, have at it.
