Saliency-AAASA
==============

Detecting Salient Objects via Automatic Adaptive Amplitude Spectrum Analysis.

Installation
============

1. Choose the data set that you want to test, then copy the stimulli of the data set to `./Dataset_Stimuli/`;
2. Build a new folder to reserve the saliency map results.(e.g., `./Dataset_SaliencyMaps/`);
3. Modify `./SHFT_dataset.m` to modify the variables `INPUTDATASET`, `EXTENSION` and `OUTPUTSM`;
4. Run `./SHFT_dataset.m` to generate the saliency maps on a given data set.
