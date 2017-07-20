# [Natural Sounding Artificial Reverberation](http://www.ece.rochester.edu/~zduan/teaching/ece472/reading/Schroeder_1962.pdf) [4]

> M. R. SCHROEDER

**Reverb explained mathematically and techniques to make it sound realistic**

Reverb done in the simplest form with a simple feedback loop creates a fequency response much like a comb filter. This created an unpleasant signal, so the goal is to create a frequency response with unity gain. This is done by mixing the delayed and undelayed sound with gains of (-g) and (1-g^2) respectively. This creates a frequency reponse with a constant value of 1, so that the unpleasantness is gone. Further techniques to mimic real reverb are discussed, but are shown to be indiscernable from the main technique that was just discussed.