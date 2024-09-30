# Jellyfish Plonk Prover Time and Memory Benchmarking

To run the benchmark, do the following:

```
set -e
cd plonk
RAYON_NUM_THREADS=N cargo bench --features test-srs
```

The benchmark file is in `./plonk/benches/bench.rs`. Please change the params as you like.