# Hephy Pkg

[![Build Status](https://travis-ci.org/deis/pkg.svg?branch=master)](https://travis-ci.org/deis/pkg)
[![Go Report Card](https://goreportcard.com/badge/github.com/deiscc/pkg)](https://goreportcard.com/report/github.com/deiscc/pkg)
[![GoDoc](https://godoc.org/github.com/deiscc/pkg?status.svg)](https://godoc.org/github.com/deiscc/pkg)

The Hephy Pkg project contains shared Go libraries that are used by
several Hephy projects.

## Usage

Add this project to your `vendor/` directory using Godeps or
[glide](https://github.com/Masterminds/glide):

```
$ glide get --import github.com/deiscc/pkg
```

(The `--import` flag will get any additional dependencies.)
