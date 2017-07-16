# [Recurrent Neural Networks For Drum Transcription](http://www.cp.jku.at/research/papers/Vogl_etal_ISMIR_2016.pdf) [7]

> Richard Vogl, Matthias Dorfer, Peter Knees

**Transcribing percussive sounds from any given track**

Using 4 different types of RNN's, kick, snare, and hi-hats were able to be transcribed. One of the interesting aspects of this paper was the use of a time shifted RNN. There was a short delay between the input and output neurons, which allowed both past and future samples to be used to train the neural net, but still allowing for real-time audio processing (given a small delay). The neural net was implemented in Python using the Lasagne and Theano libraries.
