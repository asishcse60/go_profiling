# go_profiling
This repository will help to identifying bottleneck of a go application's performance.

# Methods of profiling
1. Built-in Benchmarking (does not predefine profiles)
2. Runtime Profiling: runtime/pprof
3. Active web profiling: net/http/pprof

# Predefined profiles
1. CPU 
2. Heap/Memory
3. Block
4. Thread
5. Goroutine
6. Mutex

# All Benchmark Test Run Command
- go test -bench='.' [for linux do not need quote]