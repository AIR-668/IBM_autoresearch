## autoresearch/sep25-ccc-h100

This formal experiment reproduces the upstream autonomous `autoresearch`
workflow on IBM CCC using one NVIDIA H100 80GB HBM3.

The Git branch starts exactly from immutable `exp-start` at
`e5c0b2a11bdb6935585fcef81ccd4490b777e258`.

The scientific objective follows the unchanged upstream `program.md`:
autonomously modify only `train.py`, run fixed-budget experiments, evaluate
`val_bpb`, keep improvements, and discard regressions.

CCC platform adaptation is limited to runtime/container execution and
external evidence capture. The evaluation harness is frozen to the accepted
`prepare.py` hash `4f2ba9cbb8ba8c4a3d35be405a913e2f3be3af9aea103ed52ef7b2a662058150`.
