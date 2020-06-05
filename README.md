# go-message

[![GoDoc](https://godoc.org/github.com/STEFANOORLANDI/go-message?status.svg)](https://godoc.org/github.com/STEFANOORLANDI/go-message)
[![builds.sr.ht status](https://builds.sr.ht/~STEFANOORLANDI/go-message.svg)](https://builds.sr.ht/~STEFANOORLANDI/go-message?)
[![codecov](https://codecov.io/gh/STEFANOORLANDI/go-message/branch/master/graph/badge.svg)](https://codecov.io/gh/STEFANOORLANDI/go-message)

A Go library for the Internet Message Format. It implements:

* [RFC 5322]: Internet Message Format
* [RFC 2045], [RFC 2046] and [RFC 2047]: Multipurpose Internet Mail Extensions
* [RFC 2183]: Content-Disposition Header Field

## Features

* Streaming API
* Automatic encoding and charset handling (to decode all charsets, add
  `import _ "github.com/STEFANOORLANDI/go-message/charset"` to your application)
* A [`mail`](https://godoc.org/github.com/STEFANOORLANDI/go-message/mail) subpackage
  to read and write mail messages
* DKIM-friendly
* A [`textproto`](https://godoc.org/github.com/STEFANOORLANDI/go-message/textproto)
  subpackage that just implements the wire format

## License

MIT

[RFC 5322]: https://tools.ietf.org/html/rfc5322
[RFC 2045]: https://tools.ietf.org/html/rfc2045
[RFC 2046]: https://tools.ietf.org/html/rfc2046
[RFC 2047]: https://tools.ietf.org/html/rfc2047
[RFC 2183]: https://tools.ietf.org/html/rfc2183
