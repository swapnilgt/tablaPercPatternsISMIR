# Introduction
This repository contains the code for running the pattern search experiments as mentioned in the article titled **Discovery of syllabic percussion patterns in tabla solo recordings** published in [ISMIR 2015](http://ismir2015.uma.es/program_and_papers_ismir2015.html). Here we will explain the necessary steps and configurations that you can do to run the code for pattern search results. To understand the variables related to the code mentioned below, refer to the [paper](http://repositori.upf.edu/handle/10230/25697?show=full).

# Prerequisites
Following are the prerequisites that you woould need to run the code:
  * [matplotlib](http://matplotlib.org/)
  * [numpy](http://www.numpy.org/)
  * [scipy](https://www.scipy.org/)
  
# Code and Data
Here we explain the steps to run the code and the data needed for that.
## config
This file is present in the location `rlcs/config`.This file consists of the information about the basic config that would enable us to run the experiments using the code. This file has the following variables:
  1. **sylbSimFolder**: This is the folder where
  2. **transFolder**: Folder where we have the results for the automatic transcriptions of the data.
  3. **lblDir**: Directories having the files relevant to different audio files in the dataset. These files are with the extension `.lab` and contain the syllables in the composition with each syllable listed on a new line.
  4. **onsDir**: Directories having the files relevant to different audio files in the dataset. These files are with the extension `.csv` and contain the time stamp of each syllable in the composition(corresponding to the file in **lblDir**) with each timeStamp listed on a new line.
  5. **resultDir**: The result where you want to dump the result of the pattern search experiments. 

