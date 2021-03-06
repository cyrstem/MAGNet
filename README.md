# MAGNet

This demonstrates an LSTM audio generation process using MAGNet, a spectral approach to audio analysis and generation with neural networks. The techniques included here were used as part of the Mezzanine Vs. MAGNet project featured as part of the Barbican's AI: More than Human exhibition

It represents ongoing work from researchers at Goldsmiths, University of London. MAGNet trains on the magnitude spectra of acoustic audio signals, and reproduces entirely new magnitude spectra that can be turned back in to sound using phase reconstruction - it's very high quality in terms of audio fidelity.

This repo provides a chance for people to train their own models with their own source audio and genreate new sounds. Both given projects are designed to be simple to understand and easy to run.

This repo contains two Jupyter notebooks. 

train-for-python contains a walkthrough of how to use tflearn to do this entirely in python. Phase reconstruction is done using griffin-lim

train-for-javascript contains a walkthrough of how use Keras to train a model, which can then be converted to be used in javascript projects in the browser using tensorflow.js. Example code for this is on the MIMIC platform https://mimicproject.com/code/b530ba9e-dfd9-0440-8358-86b6420b210d. Phase reconstruction is doing using a port of LWS, developed by the Goldsmiths for this purpose.


Contributions have been made by Mick Grierson, Leon Fedden, Sam Park-Wolfe, Jakub Fiala and Louis McCallum. 