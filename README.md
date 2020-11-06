# backoff

This package provides a couple strategies for backoff with support for cancellation.

The code is [from libbeat](https://github.com/elastic/beats/tree/master/libbeat/common/backoff), used under the [Apache License, Version 2.0](LICENSE). See [NOTICE](NOTICE) for details.

## Why use this package

You like the user interface of the utility in libbeat but don't want to introduce a dependency on libbeat.

(As of the creation of this fork, depending on libbeat is problematic due to transitive dependencies that don't play nice with `go get`.)

### Why not use this package

If including libbeat as a dependency works for you, you should do that instead.

## Maintenance

Pull Requests to keep the code in this package in sync with libbeat are welcome, so long as the updates are entirely under the Apache License, Version 2.0 and are properly attributed.

This package will follow semver with respect to the backoff code itself.
