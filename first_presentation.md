# Predicting from Brain Data

Note: this project is delivered in the first release, v1.0.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mtl-brainhack-school-2019/kongnorman_BrainDecoding/master)

### Context

My name is Norman Kong, and in the fall, I will be starting my undergraduate studies in software engineering at McGill University. For awhile now, I have been interested in ML, so when I joined the BrainHack school, my main focus was to gain some practical experience training models. In my opinion, one of the most interesting applications of ML is within the field of neuroscience, so I decided I wanted to try brain decoding, even if I have virtually no neuroscience background. 

Throughout this project, I am hoping to familiarize myself with data science tools such as nilearn, sci-kit learn, as well as open science tools such as Jupyter notebooks and binder.

### Goal

My goal is to create an accessible, extensive but easy to understand fMRI brain decoding tutorial for those who are new to the subject. I am hoping that this tutorial will be of high enough quality that it may be shared to the nilearn team, and hopefully help future scientists entering the field. 

This tutorial will differ from existing tutorials by including the basic foundations of fMRI analysis for those who have never worked with it before. The examples I have seen so far contain concise and simple code, but the underlying processes of these operations remain obscure. 

For example, here is a brain decoding tutorial from nilearn:

[![ex1.jpg](https://i.postimg.cc/x8bwgH1Y/ex1.jpg)](https://postimg.cc/8fNXz7vn)

The code is perfectly functional and documented, but I'm still left with plenty of questions. For example, why do we need a masker? Actually, *what is* a masker?!

That brings me to the documentation for `NiftiMasker()`:

[![ex2.jpg](https://i.postimg.cc/G9wZf24D/ex2.jpg)](https://postimg.cc/Mf5PMzbZ)

The first sentence from the documentation is: "Applying a mask to extract time-series from Niimg-like objects." I'm not really any closer to understanding what a mask is, but at least I learned something: that "Niimg-like objects" are a thing, and I also need to learn what those are! 

So really, I'm hoping that through this tutorial I can learn what these terms and concepts mean from the many resources online, learn how to use them, and then summerize this information all in one place. I hope this will serve as a future introductory resource for newcomers to the field.

To be clear, this is not to say I'm confused because the documentation/resources are bad, rather I am confused because I am ignorant. This project is a great way for me to learn more about the field of neuroscience within a computer science context.

![office_gif](https://media.giphy.com/media/R5kxSVfg1k0dG/giphy.gif)

### Materials

The main medium to share what I learn will be the Jupyter notebook. They are a suitable tool because they are interactive and editable. To increase accessibility, I am hoping to make this repository binder-compatible and available on NeuroLibre. 

### Main Steps


2. Find a high quality dataset that has already been extensively studied.
    - Haxby's 2001 block-design fMRI study investigated patterns of response evoked in ventral temporal cortex by faces and multiple categories of objects, such as chairs, shoes, etc. (https://science.sciencemag.org/content/293/5539/2425.long)
    - Haxby et al. made it available under the terms of the Creative Commons Attribution-Share Alike 3.0 license.

3. Compare several models to form our predictions.
    - Support Vector Machine 
    - k-Nearest Neighbours
    - Logistic Regression
    - Convolutional Neural Network 

4. Review results (see what worked, see what didn't, etc.)

### The Contents of this Repo

- _fMRI_crash_course.md_: A brief introduction to fMRI basics. 
- _ML_crash_course.ipynb_: A brief introduction to machine learning, and the models used in the analysis.
- _Brain_Decoding.ipynb_: The brain decoding itself. 
- _requirements.txt_: The necessary libraries to run the analysis. 

The intended order of which files to read is:

1. fMRI_crash_course.md 
2. ML_crash_course.ipynb 
3. Brain_Decoding.ipynb

### Open-Science Best Practices:
- Git/GitHub
- Python
- Jupyter notebooks
- binder (ish)

### Skills and technologies learned and applied:

- What fMRI data is and how it is interpreted by the computer
- What brain decoding is
- Basic machine learning models
- `plotly`
- `nilearn`
- `scikit-learn`
- Jupyter notebooks and nbextensions
- Python virtual environments

Here is a short introductory [video]() to get started!

TODO:
- add a visual for orders of complexity
- start logistic regression
- find way to make it binder compatible (NeuroLibre?)
- add license
- Inform the nilearn team about the confusion in the dataset on their tutorial. 

TODO: Special thanks to: @jvogel, @emdupre, @agahkarakuzu, @nnstikov, @pbellec
