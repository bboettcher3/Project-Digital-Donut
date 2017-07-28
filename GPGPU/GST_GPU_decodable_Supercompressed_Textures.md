# [GST: GPU-decodeable Supercompressed Textures](http://dl.acm.org/citation.cfm?id=2982439) [9]

> Pavel Krajcevski, Srihari Pratapa, and Dinesh Manocha

**Large 4K videos compression via GPGPU**

The big issue GST is trying to tackle is these large 4K 360-degree 60fps videos people want streamed. The way JPEG and other older compressions work don't scale with CPUs for these large textures. The other main thing is this is all done at the endpoint device. The big drawback is the extra memory needed while its decoding which may be an issue if resources are scarce.
