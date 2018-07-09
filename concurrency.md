### Atomic

Best Practice:
- Use std::atomic, instead volatile
- Use default memory order, instead memory_order_acquire/release/consume/seq_acq
- Use mutex, instead atomic

Reference
- [std::memory_order](https://en.cppreference.com/w/cpp/atomic/memory_order#Sequentially-consistent_ordering)
- [C++ atomics and memory ordering](https://bartoszmilewski.com/2008/12/01/c-atomics-and-memory-ordering/)

