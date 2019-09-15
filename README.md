# Setup environment
## Install anaconda
You can use anaconda in different system  
## Use conda to setup environment
$ conda env list     
$ conda env remove -n audio-research  
$ conda create -n audio-research python=3.6  
$ conda activiate audio-research  
## install jupyter notebook
$ conda install -n audio-research jupyter    
After install finishing, The way to open jupyter is   
$ jupyter notebook   
## install related package 
$ conda install -n audio-research pyaudio   
$ conda install -n audio-research numpy  
$ conda install -n audio-research matplotlib  
$ conda install -n audio-research pyqtgraph  
$ conda install -n audio-research scipy  

# File list  
## audio_record_and_play_test.ipynb  
This is most simple example for you to record file and play file.  
This code should be running well on your OS in jupyter notebook.  

## audio_spectrum_analyzer.ipynb
The first cell in this file is the implementation of Waveform Viewer.  
The second cell in this file is the impelemntation of Audio Spectrum Analyzer.  
I just justify the code in first cell to become the code in second cell.  
That's my method to make a audio spectrum analyzer in jupyter notebook.    

## audio_spectrum_qt.py  
It is  qt app for audio_spectrum.  
But resize window will be dead because I don't write code to process the  
conflict between UI and data processing.   
