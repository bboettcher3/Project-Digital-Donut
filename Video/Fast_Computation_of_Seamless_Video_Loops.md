# [Fast Computation of Seamless Video Loops](http://dl.acm.org/citation.cfm?id=2818061) [10]

> Jing Liao, Mark Finch, and Hugues Hoppe

**Turning any video clip into a perfect loop**

With the world pushing towards video, this aims to take small clips and automatically create a loop by smartly stitching the ends together. Using possion blending it can track each pixel to see when and how to blend it together. Breaks down the video to different components to allow threading and better performance. Current implementation takes a while to render and won't work if the video has drastic ends.