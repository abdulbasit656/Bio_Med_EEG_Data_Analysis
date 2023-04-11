# Bio_Med_EEG_Data_Analysis

Biomedical Robotics 2022 Practical Activity

##EEG data analysis

1. Download the EEG files .set and .fdt from Teams
2. Load the EEG file (.set) on EEGLAB
3. Using the GUI, complete the following steps: a) Downsampling 250 Hz b) Filtering [1-80Hz] + Notch filter 50 Hz c) Epoching: Time locking event type: G interval: [-1 3]
4. Visual inspection for channels and epochs: Channel Data (scroll) a) Remove bad epochs from the plot b) Select bad channels and remove them using the GUI – Important: write down the channels you removed
5. Independent Component Analyses a) Run ICA (it takes some time…now it’s time to have a break!) b) Manual Check of the components and mark the “bad” ones Reject Data using ICA -> Reject components by map
6. Channels Interpolation On the GUI select “Interpolate Electrodes” and “Use specific channels of other dataset”
7. On the “clean” dataset Perform Average Reference
8. Run the spectra (Plot/Channels Spectra and Maps) on the 100% of the data adding one scalp map for each physiological frequency range (delta 1-4Hz, theta 4-8Hz, alpha 8-13Hz, beta 15-25Hz)
