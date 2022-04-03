# zombiesplit gRPC API

This repository contains `zombiesplit.proto`, the Protocol Buffers v3 specification for the [zombiesplit](https://github.com/ashikun/zombiesplit) protocol.
This protocol allows clients to control and observe a run attempt on a `zsserver`.

**CAVEAT EMPTOR:** this protocol is _heavily experimental_ (at time of writing, it has not yet reached version 0.1!) and is subject to change.

## Usage

Feed this directly into your `protoc` or local equivalent.
For more sophisticated automated builds, consider using this repository as a Git submodule.

The `.proto` file is reasonably self-documenting, but documentation is in a constant state of improvement.
We welcome any help to clarify the documentation.

## Licence

Unlicense; see `LICENSE`.
