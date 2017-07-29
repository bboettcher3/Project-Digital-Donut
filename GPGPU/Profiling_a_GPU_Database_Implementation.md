# [Profiling a GPU database implementation: a holistic view of GPU resource utilization on TPC-H queries](http://dl.acm.org/citation.cfm?id=3076119) [6]

> Emily Furst, Mark Oskin, and Bill Howe

**Databases are not inherently ment for parallelism**

This was an attempt to see exactly how much a GPU is used when trying to implement a GPGPU database. With their profiling tools they built, they found that only 5% of the time was used running on the GPU and most was transferring data. The main takeaway is a GPU based database bottleneck currently is not the GPU, but the memory transfer speed.