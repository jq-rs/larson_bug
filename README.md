# larson test for sized deallocation

Simple test modifications for sized deallocations as they have a fast path on some allocators.

This is just a prototype benchmark done really quickly with help of coffee. Not production level in any way, no guarantees for anything and no plans to develop this further. It could be generalized by using C++14 sized delete API (thanks for the idea mjp41!).

This repository is archived.

Original test [here](https://github.com/daanx/mimalloc-bench/tree/master/bench/larson)

Test driver for memory allocators
Author: Paul Larson, palarson@microsoft.com
