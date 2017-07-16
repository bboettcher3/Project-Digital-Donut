# [Towards High-Quality Sound Synthesis of the Guitar and String Instruments](https://pdfs.semanticscholar.org/a3b5/89e460d43fff6057a8d85db77a28d7b3c09e.pdf) [8]

> Matti Karjalainen, Vesa Välimäki, and Zoltán Jánosy

**Creating syntheized guitar and string sounds without sampling**

The researchers' goal was to create synthesized string sounds that aren't computationally intensive yet still are perceived as sounding real. They did this by creating 3 linear subsystems: excitation, string, and body. The body filter was the most computationally intensive, so they worked around this by having it as an input so that it wouldn't have to be computed for each note. The impulse response for each note's body response was stored elsewhere so that it could be easily looked up and not computed. Their results showed very similar to the actual guitar sound.