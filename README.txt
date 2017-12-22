------------------------------ README ------------------------------------
The program is written on a Windows machine.
Language used : Python 2.7.6

Classes used from the '20news-bydate' dataset: 
1. alt.atheism, 
2. misc.forsale, 
3. sci.electronics, 
4. talk.politics.misc, 
5. talk.religion.misc

Libraries used:
1. stop-words(pip install stop-words) for preprocessing
2. numpy
3. re

Compile instructions:
1. Open command line. Switch to the directory containing classify.py
2. Implement the file using command python classify.py

The program asks for the location of training and test folders.

Result: Accuracy = 0.813589897775
It means that our model rightly classifies the text 81.35% of the time.

