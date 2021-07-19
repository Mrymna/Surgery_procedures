# 4x16 probe configuration with Intan 64 amplifier


To be able to make sense of the data from the probe, we need to reordered the channels so that the channels from a shanks are grouped together from the highest to the lowest recording site on the shank. This is needed for visualisation (when looking at the oscilloscope) and for spike extraction.

The ordering of the channels is a 2 step process. 

1. Determine the "Neuronexus" channel order that you would like to have. You should order them by shank number, from the top to the bottom.
2. You then need to find the "Intan" channel that correspond to the "Neuronexus" channel. 

## Order of the channels on the Omnetic connector of the probe

https://www.neuronexus.com/files/probemapping/64-channel/H64LP-Maps.pdf

The website does not have the order of channels for the 4x16 probjes.


## Order of the channels in the Intan amplifier

https://intantech.com/files/Intan_Recording_Controller_user_guide.pdf


