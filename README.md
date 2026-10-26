# Paras Mahajan

Computer Engineering student (graduating 2027) building low-latency C++ systems.
Targeting systems / low-latency / HFT engineering roles.

## Projects

| Project | What it is | Headline number |
|---|---|---|
| [SPSC Ring Buffer](https://github.com/paras-mahajann/spsc-ring-buffer) | Lock-free single-producer/single-consumer queue | ~10x faster than a mutex queue |
| [Pool Allocator](https://github.com/paras-mahajann/custom_pool_allocator) | Intrusive free-list allocator, placement new | ~19x faster than new/delete (3.4 vs 64.5 ns) |
| [ITCH Parser](https://github.com/paras-mahajann/market-data-parser) | Big-endian binary market-data parser | 12.6 ns/message, ~81M msgs/s |
| [Order Book](https://github.com/paras-mahajann/order-book) | Price-time priority matching engine | best bid/ask in ~9 ns |
| [Latency-Aware Backtester](https://github.com/paras-mahajann/Latency-Aware_Backtester) | Event-driven simulator modelling feed, compute and order latency | at 3 µs total latency, half the naive edge disappears |

All projects: C++20, CMake, Catch2 tests, Google Benchmark, GitHub Actions CI.

## Stack
C++20 · CMake · Catch2 · Google Benchmark · GitHub Actions · MSVC / GCC

## Contact
mahajanparas912@gmail.com
