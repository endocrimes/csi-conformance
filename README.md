# csi-conformance

csi-conformance is a work in progress testing harness for validating
implementations of the [Container Storage Interface][csi-spec].

It contains two tools:

- [csio](#todo): csio is a fake implementation of an orchestrator, that when
  given a socket for a csi plugin, will attempt to validate its interaction with
  the specification.
- [csip](#todo): csip is a fake implementation of a csi plugin that can be used
  to validate that an orchestrator interacts with it correclty. It supports
  being ran in host-only, control-only, and mixed modes.

  [csi-spec]: https://github.com/container-storage-interface/spec
