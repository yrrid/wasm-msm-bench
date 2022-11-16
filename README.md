## Benchmarking Utility

The repo contains Yrrid's benchmarking utility from our WASM MSM submission.
The utility was develed by Sougata Bhattacharya and Antony Suresh.

## Usage

Open two browser windows/tabs to the CoreWeave instance.  In one window run:

```
./evaluate.sh
```

Once the evaluator is up and running and waiting for connections, in the second window, run:

```
cd bench
./bench.sh
```

On occassion, the bench utility will silently quit -- we're not sure why.  Re-running it seems
to resolve the issue.