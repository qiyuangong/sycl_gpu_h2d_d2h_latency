# sycl_gpu_h2d_d2h_latency


## Benchmark script from oneAPI GPU Optimization Guide

```bash
icpx -fsycl sycl_prepare_bench.cpp
```

Without `prepare_for_device_copy`.

```bash
./a.out
```

With `prepare_for_device_copy`.

```bash
./a.out -l
```

## Benchmark script from one time copy


## Reference

[Optimizing Data Transfers
](https://www.intel.com/content/www/us/en/docs/oneapi/optimization-guide-gpu/2025-0/optimizing-data-transfers.html)
