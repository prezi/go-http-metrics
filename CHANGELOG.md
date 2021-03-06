# Changelog

## [Unreleased]

## [0.4.0] - 2019-03-27

### Breaking changes

- The Recorder methods now receive a context argument.

### Added

- OpenCensus recorder implementation.

## [0.3.0] - 2019-03-24

### Added

- Inflight requests metric per handler.

## [0.2.0] - 2019-03-22

### Added

- Metrics of HTTP response size in bytes.
- Make the label names of Prometheus recorder configurable.

## [0.1.0] - 2019-03-18

### Added

- Gorestful compatible middleware.
- Httprouter compatible middleware.
- Negroni compatible middleware.
- Option to group by status codes.
- Predefined handler label.
- URL infered handler label.
- Middleware.
- HTTP latency requests.
- Prometheus recorder.

[unreleased]: https://github.com/slok/go-http-metrics/compare/v0.4.0...HEAD
[0.4.0]: https://github.com/slok/go-http-metrics/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/slok/go-http-metrics/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/slok/go-http-metrics/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/slok/go-http-metrics/releases/tag/v0.1.0
