## Experiment contract

- Experiment identity: `autoresearch/sep25-ccc-h100`
- Branch point: `exp-start`
- Branch-point commit: `e5c0b2a11bdb6935585fcef81ccd4490b777e258`
- Accepted CCC runtime hash: `9659b34fa770`
- Accepted OCI SHA256: `16256cdd00a61aaddb953b0043bf6c91d07cc0af7facd01d5df78b069830ed14`
- Accepted data manifest SHA256: `8c3f9e218e528dd9808d1cb55d9ec25828577e2220db539d4922a6b8c35bbf66`
- Reference baseline val_bpb: `1.050213`
- GPU: one `NVIDIA H100 80GB HBM3`
- Agent-editable scientific file: `train.py` only
- Fixed evaluation/data harness: `prepare.py`
- New dependencies are forbidden
- `results.tsv` remains untracked as required by upstream
- Per-run full stdout/stderr is copied to the external canonical run-log tree
- Human stops the autonomous loop manually; the agent does not pause between experiments
