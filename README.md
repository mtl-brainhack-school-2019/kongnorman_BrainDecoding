# Predicting from Brain Data

This is an introductory brain decoding tutorial. 

### Context

My name is Norman Kong, and in the fall, I will be starting my undergraduate studies in software engineering at McGill University. For awhile now, I have been interested in ML, so when I joined the BrainHack school, my main focus was to gain some practical experience training models. In my opinion, one of the most interesting applications of ML is within the field of neuroscience, so I decided I wanted to try brain decoding, even if I have virtually no neuroscience background. 

Throughout this project, I am hoping to familiarize myself with data science tools such as nilearn and sci-kit learn, as well as open science tools such as Jupyter notebooks and binder.

### Goal

My goal is to create an accessible, extensive but easy to understand fMRI brain decoding tutorial for those who are new to the subject. I am hoping that this tutorial will be of high enough quality that it may be shared to the nilearn team, and hopefully help future scientists entering the field. 

This tutorial will differ from existing tutorials by including the basic foundations of fMRI analysis for those who have never worked with it before. The examples I have seen so far contain concise and simple code, but the underlying processes of these operations remain obscure. 

For example, here is a brain decoding tutorial from nilearn:

[![ex1.jpg](https://i.postimg.cc/x8bwgH1Y/ex1.jpg)](https://postimg.cc/8fNXz7vn)

The code is perfectly functional and documented, but I'm still left with plenty of questions. For example, why do we need a masker? Actually, *what is* a masker?!

That brings me to the documentation for `NiftiMasker()`:

[![ex2.jpg](https://i.postimg.cc/G9wZf24D/ex2.jpg)](https://postimg.cc/Mf5PMzbZ)

The first sentence from the documentation is: "Applying a mask to extract time-series from Niimg-like objects." I'm not really any closer to understanding what a mask is, but at least I learned something: that "Niimg-like objects" are a thing, and I also need to learn what those are! 

So really, I'm hoping that through this tutorial I can learn what these terms and concepts mean, learn how to use them, and then summerize this information all in one place. 

To be clear, this is not to say I'm confused because the documentation/resources are bad, rather I am confused because I am ignorant. This project is a great way for me to learn more about the field of neuroscience.

![giphy.gif](https://giphy.com/gifs/SAAMcPRfQpgyI/html5)

### Materials

The main medium to share what I learn will be the Jupyter notebook. To increase accessibility, this repository will be binder-compatible. 

### Main Steps

1. Learn what the heck fMRI imaging is and how fMRI data is stored.
    - Read!!!

2. Learn how fMRI data is analyzed.
    - Read!!!

3. Find a high quality, preprocessed dataset.
    - Haxby's 2001 dataset (https://science.sciencemag.org/content/293/5539/2425.long)

4. Compare several models to form our predictions.
    - Support Vector Machine 
    - k-Nearest Neighbours
    - Logistic Regression

5. Review results (see what worked, see what didn't, etc.)

### Pieces of the Project

- Haxby data set
- fMRI_crash_course.ipynb
- ML_Crash_Course.ipynb
- Discussion.ipynb
- requirements.txt


