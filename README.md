# larson test for sized deallocation

Simple test modifications for sized deallocations.

Sized deallocations have fast path on some allocators. This may make significant number of application calls to have a size information as part of deallocation call. Therefore, it may be worth for any allocator to tune sized deallocation to be as fast as possible, in addition to libc-malloc/free paths.

Original test [here](https://github.com/daanx/mimalloc-bench/tree/master/bench/larson)

Test driver for memory allocators
Author: Paul Larson, palarson@microsoft.com
