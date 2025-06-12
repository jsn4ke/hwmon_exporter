# hwmon exporter

[![CircleCI](https://circleci.com/gh/prometheus/node_exporter/tree/master.svg?style=shield)][circleci]
![bsd workflow](https://github.com/prometheus/node_exporter/actions/workflows/bsd.yml/badge.svg)
![golangci-lint workflow](https://github.com/prometheus/node_exporter/actions/workflows/golangci-lint.yml/badge.svg)
[![Docker Repository on Quay](https://quay.io/repository/prometheus/node-exporter/status)][quay]
[![Docker Pulls](https://img.shields.io/docker/pulls/prom/node-exporter.svg?maxAge=604800)][hub]
[![Go Report Card](https://goreportcard.com/badge/github.com/prometheus/node_exporter)][goreportcard]

Prometheus exporter for hardware monitoring metrics exposed by \*NIX kernels, written
in Go with pluggable metric collectors.


## Installation and Usage

If you are new to Prometheus and `hwmon_exporter` there is a [simple step-by-step guide](https://prometheus.io/docs/guides/node-exporter/).

The `hwmon_exporter` listens on HTTP port 9200 by default. See the `--help` output for more options.


### Docker

## Collectors
