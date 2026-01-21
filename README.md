**NOTE**: This project is a copy of https://github.com/microsoft/verified-storage/tree/main/pmemlog. It's main purpose is to illustrate the use of the [scip-callgraph reusable workflow](https://github.com/Beneficial-AI-Foundation/scip-callgraph/blob/main/.github/workflows/generate-callgraph.yml) to generate a graph.

# About

This directory contains the Verus code for a persistent-memory append-only
log

## Table of contents
1. [Setup](#setup-instructions)
2. [Verification](#verification)

### Setup instructions

Install Verus from `https://github.com/verus-lang/verus`.

### Verification

To verify the log, `cd` to the `pmemlog/` directory and run the following.
```
cd src
cargo verus verify
```
