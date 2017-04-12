[![GoDoc](https://godoc.org/github.com/docker/go-units?status.svg)](https://godoc.org/github.com/docker/go-units)

# Fork note

This was forked because RAMBytes() is not reversible - I needed a way to convert 1024-based bytes into strings that RAMBytes() would read so I could get back the same number on both ends.

# Introduction

go-units is a library to transform human friendly measurements into machine friendly values.

## Usage

See the [docs in godoc](https://godoc.org/github.com/docker/go-units) for examples and documentation.

## Copyright and license

Copyright © 2015 Docker, Inc.

go-units is licensed under the Apache License, Version 2.0.
See [LICENSE](LICENSE) for the full text of the license.
