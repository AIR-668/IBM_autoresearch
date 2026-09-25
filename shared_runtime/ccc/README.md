## IBM CCC runtime foundation

This directory contains the Git-tracked CCC runtime definition for the
`IBM_autoresearch` fork.

The repository retains the upstream `master` branch name. For this fork,
`master` serves the project-foundation role, and the immutable
`exp-start` tag is the branch point for subsequent formal experiments.

The accepted foundation is anchored to upstream commit
`228791fb499afffb54b46200aca536f79142f117`.

The accepted CCC runtime identity is `9659b34fa770`, using
`localhost/ibm-autoresearch:cu128-9659b34fa770`. The large OCI archive, prepared dataset/tokenizer,
canonical execution logs, and temporary runtime caches remain outside Git
under the outer project root.

The fork's writable `origin` uses the CCC SSH alias `air-668`; upstream
remains a separate read-only reference.

The accepted unmodified CCC H100 baseline produced
`val_bpb=1.050213` with a fixed `300.0` second training
budget, `466` optimization steps, and `244.3M`
training tokens.

Exact hashes and baseline metrics are recorded in `runtime.lock`.
