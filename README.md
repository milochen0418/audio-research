# Setup environment
## Install anaconda
You can use anaconda in different system  
## Use conda to setup environment
$ conda env list     
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

# File list
## audio_record_test.ipynb
The file show how to record data from microphone to output.wav  
After testing, this code is working on Mac OS   
