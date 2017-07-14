# [Automatic Conversion Of Pop Music Into Chiptunes For 8-Bit Pixel Art](http://mac.citi.sinica.edu.tw/~yang/pub/su17icassp_8bit.pdf) [5]

> Shih-Yang Su, Cheng-Kai Chiu, Li Su, Yi-Hsuan Yang

**Using pitch detection and singing voice separation to find 8-bit equivalent track for popular songs**

First they used voice separation to separate the vocals from the instrumental. Then they used non-negative matrix factorization to do pitch detection on each track. They then mapped each pitch to its 8-bit counterpart, did some smoothing for aesthetics, and merged the tracks back together. The smoothing they use isn't found to make a large difference, but synthesizing in the time domain makes a large improvement in song quality.