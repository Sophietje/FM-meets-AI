---
tags:
  - neural-networks
  - tool
  - satisfiability-checking
  - verification
  - verification-for-ML
Publication:
  - https://link.springer.com/chapter/10.1007/978-3-031-65630-9_13
  - https://link.springer.com/chapter/10.1007/978-3-030-25540-4_26
Repository:
  - https://github.com/NeuralNetworkVerification/Marabou
Note created on: 2026-08-06
---
- Checks whether provided properties, expressed as (non-) linear constraints, hold for a specific neural network. Will return a counterexample if not.
- These constraints typically represent a verification query over a neural network
- User can provide constraints manually or pass in a neural network file which is processed by a parser (ONNX, Nnet, protobuf format)