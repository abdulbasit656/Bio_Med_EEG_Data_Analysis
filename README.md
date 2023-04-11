# Bio_Med_EEG_Data_Analysis

Biomedical Robotics 2022 Practical Activity

##EEG data analysis

Download the EEG files .set and .fdt from Teams
Load the EEG file (.set) on EEGLAB
Using the GUI, complete the following steps: a) Downsampling 250 Hz b) Filtering [1-80Hz] + Notch filter 50 Hz c) Epoching: Time locking event type: G interval: [-1 3]
Visual inspection for channels and epochs: Channel Data (scroll) a) Remove bad epochs from the plot b) Select bad channels and remove them using the GUI – Important: write down the channels you removed
Independent Component Analyses a) Run ICA (it takes some time…now it’s time to have a break!) b) Manual Check of the components and mark the “bad” ones Reject Data using ICA -> Reject components by map
Channels Interpolation On the GUI select “Interpolate Electrodes” and “Use specific channels of other dataset”
On the “clean” dataset Perform Average Reference
Run the spectra (Plot/Channels Spectra and Maps) on the 100% of the data adding one scalp map for each physiological frequency range (delta 1-4Hz, theta 4-8Hz, alpha 8-13Hz, beta 15-25Hz)
