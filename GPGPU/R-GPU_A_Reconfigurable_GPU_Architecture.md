# [R-GPU: A Reconfigurable GPU Architecture](http://dl.acm.org/citation.cfm?id=2890506) [24]

> Gert-Jan Van Den Braak and Henk Corporaal

**Add-on to GPU to allow for better performance and efficiency**

The main issue being tackled is GPGPU algorithms that have memory bandwidth issues, redundant memory loads, and other topical issues. R-GPU is almost best described as a networking system to control the flow of data among SM cores. Using well designed FIFO's they can control the scheduling and communication between cores. This currently is an experimental prototype on NVIDIA's Fermi architecture.