# Brain Decoding Tutorial

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mtl-brainhack-school-2019/kongnorman_BrainDecoding/master)

### Summary

This repository is my project for the Montreal 2019 BrainHack school. It contains four documents that will help you get started with a basic brain decoding workflow. My project is an attempt to contribute to the lack of beginner-friendly resources in the fields of computer and neuroscience. 

### Project Definition

When I joined the BrainHack school, my focus was to gain practical experience in machine learning. That lead me to try brain decoding, even if I had little knowledge in the subject. I started with an introductory brain decoding tutorial online, but I was quickly lost in the scientific jargon and foreign concepts of neuroscience. There was concise and simple code, but the underlying processes of the operations remained obscure. However, I was undeterred. I simply decided that I would make my own tutorial. I knew that if I could explain what I had learned to others, it would mean that I understood the material myself. Thus, my tutorial became my project. It differs from existing tutorials because it includes the basic foundations of fMRI analysis and machine learning for newcomers to the field. My goal was to research the various terms and concepts from different resources, and then summarize them simply in one place. I hope this can serve as a beginner-friendly resource for people who were once in my shoes. 

### Learning Experience

The first step of the project was to learn all I could about machine learning, what fMRI imaging is and how its data is stored/manipulated. For this, I had to read from a lot of different sources, as well as ask a lot of questions to the knowledgeable teaching assistants. As I did my research, I took detailed notes. My next step was to find a dataset that would be appropriate for the tutorial. I ended up choosing the dataset from Haxby’s 2001 [study](http://www.sciencemag.org/cgi/pmidlookup?view=long&pmid=11577229) because it is easily accessible through the nilearn library. Finally, it was time to start creating the tutorial itself. After careful consideration, I decided that the best medium for this project would be the Jupyter notebook. Once I figured out which approach I would use (style, structure, etc.), I wrote the base of my tutorial. It then took many hours of editing and formatting in order to clarify and polish the content.

I learned a lot throughout the entire process. Here are the main elements that I got to learn about and use: 

- Basic machine learning models
- `plotly`
- `nilearn`
- `scikit-learn`
- Jupyter notebooks and `nbextensions`
- Python virtual environments
- What fMRI data is and how it is interpreted by the computer
- What brain decoding is

### Results

The deliverable for this project is this repository, which contains the tutorial. I have three separate notebooks to tackle the main components of the project: 

- _fMRI_crash_course.ipynb_: A high-level introduction to fMRI basics. It covers the bare minimum of what you need to know in neuroscience in order to get through the tutorial. 
- _ML_crash_course.ipynb_: A thorough introduction to some simple machine learning models and their implementation in sci-kit learn. 
- _Brain_Decoding.ipynb_: The brain decoding itself. It explains the control flow of the code, but the underlying theory of brain decoding is in the first two notebooks.  

Additionally, I included a _requirements.txt_ file to make this repository binder compatible. 

One of the main goals of this project was to create deliverables based on open-science practices. The very inspiration of the project was because I struggled to learn about something I was interested in due to the way in which it was communicated. So, in an attempt to bridge the gap between those who are new to the subject and those who are specialists, I created this tutorial. In order to make it as accessible as possible, I incorporated these open-science elements in my deliverables:  

- Git/GitHub: A popular platform to easily share coding projects.
- Python: An easy-to-learn open-source programming language.
- Jupyter notebooks: An open-source medium to share code transparently.
- binder (work in progress): A web service that allows you to share Git repositories so that they are highly reproducible.

Special thanks to: @jvogel, @emdupre, @agahkarakuzu, @nnstikov, @pbellec

Todo:
- find way to make it binder compatible (NeuroLibre?)
- add license