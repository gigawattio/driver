# driver

[![Documentation](https://godoc.org/github.com/gigawattio/driver?status.svg)](https://godoc.org/github.com/gigawattio/driver)
[![Build Status](https://travis-ci.org/gigawattio/driver.svg?branch=master)](https://travis-ci.org/gigawattio/driver)
[![Report Card](https://goreportcard.com/badge/github.com/gigawattio/driver)](https://goreportcard.com/report/github.com/gigawattio/driver)

### About

This package includes both abstract interfaces and concrete implementations for relational databases.

Created by [Jay Taylor](http://jaytaylor.com/) and used by [Gigawatt](http://gigawatt.io/).

### What's inclduded

* Abstract DB drver interface
* [Gorm](http://github.com/jinzhu/gorm) DB implementation (supports Postgres, MySQL, SQLite, and more)

* Abstract queue driver interface
* Kafka queue driver implementation

### Requirements

* Go version 1.6 or newer
* Locally running postgres database for running the unit-tests.

### Running the test suite

    go test ./...

#### License

Permissive MIT license, see the [LICENSE](LICENSE) file for more information.
