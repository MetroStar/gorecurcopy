# gorecurcopy

[![Build Status](https://travis-ci.org/MetroStar/gorecurcopy.svg?branch=master)](https://travis-ci.org/MetroStar/gorecurcopy)
[![GoDoc](https://godoc.org/github.com/MetroStar/gorecurcopy?status.svg)](https://godoc.org/github.com/MetroStar/gorecurcopy)
[![Go Report Card](https://goreportcard.com/badge/github.com/MetroStar/gorecurcopy)](https://goreportcard.com/report/github.com/MetroStar/gorecurcopy)
[![Version](https://img.shields.io/github/tag/MetroStar/gorecurcopy)](https://github.com/MetroStar/gorecurcopy/releases)



`gorecurcopy` copies directories recursively without external dependencies. Compatible with OSX, Linux, and Windows.

Example:

```go
import (
	"github.com/MetroStar/gorecurcopy"
)

...

err := gorecurcopy.CopyDirectory("directory", "new_directory")
```
