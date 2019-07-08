# dh2019-dv-toolkit
Tutorial notes for the DH2019 AVinDH workshop

# Image Analysis with Deep Learning

[Taylor Arnold](https://statsmaths.github.io), Assistant Professor of Statistics, [@statsmaths](https://twitter.com/statsmaths)

[Lauren Tilton](https://laurentilton.com), Assistant Professor of Digital Humanities, [@nolauren](https://twitter.com/nolauren)

This repository contains notes, code, and data for the DH2019 AVinDH workshop
on 8 July 2019 in Utrecht. Feel free to use/share/adopt these notes for other courses.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a> This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

---

## Code of Conduct

Our workshop is dedicated to providing a harassment-free experience
for everyone. We do not tolerate harassment of participants in any form.
If someone makes you or anyone else feel unsafe or unwelcome, please report it as
soon as possible. Harassment and other code of conduct violations reduce the value
of our event for everyone. We want you to be happy at our event. People like you
make our event a better place.

In order for this tutorial to be successful, we ask that participants take note
of the following guidelines throughout the session:

- Being open minded including leaving room for exploration and creativity.
- Please try stay at the same point with us in the tutorial. If you are
finished with a section ahead of time, you are more than welcome to hack away at our
code. We find that staying together through the tutorial works best for everyone
involved.

## Description

This workshop is broken into two parts. In this first we provide an overview of
how images are represented in programming languages and the specific challenges
that undergird the computational analysis of visual materials. In the second
part, we show how automatic feature extraction can be used to address some of
these challenges. We show how the distant viewing toolkit is being developed to
assist in this process.

## Method

Generally, for workshops that are half-day or longer we tend to require that
participants follow along with the code and methods as they are presented. We
make sure that everyone is able to run each line of code and debug issues as
they arise. When giving an hour-long (or less) workshop, this ideal method is
unmanagable and we typically run the workshop as a live demo, giving the code
to participants to follow along afterwards.

Today we have an intermediate amount of time (about 1h45) and will trying a
hybrid approach. If you would like to setup the code on your laptop and run the
code yourself, that great. We will spend some time at the start of the
session to get you ready to go. If you are more comfortable just listening,
following along with a neighbor, or run into issues that we can't debug in
real-time, that is just fine too!

Our schedule for today is:

- Part 1: Basics of Image Process in Python
- Part 2: Deep Learning for Images
- Part 3: Building a Recommendation System
- Part 4: Moving Images and the Distant Viewing Toolkit

For those who would like a deeper dive into image analysis in Python, please
check out the notes we have from our week-long workshop at
[HILT2019](https://github.com/statsmaths/hilt2019-image-analysis).

## Materials

The materials for today's workshop can be found in the following file:

- [dh2019-dv-toolkit.zip](https://www.distantviewing.org/dh2019-dv-toolkit.zip)

The code is also available in this GitHub repository, but the data files are
too large to store using git.

## Software

We will be using the Python programming language for the workshop, as well as
several third-party packages. All of it is free and open source. Here is the
link to the Anaconda version of Python that we suggest you use:

- [Anaconda Python 3.7](https://www.anaconda.com/)

If you would like to follow along during the workshop, we suggest trying to
install this software ahead of the workshop as it can take a bit of time to
fully install.

Anaconda Python comes with many of the modules needed for general purpose
data science work. **For today, you should be able to work with just the
default libraries.**

You will need to install several others if you want to
apply these techniques to your own dataset. The way that you install these is
slightly different depending on your platform.

- **macOS** / **linux**: open up a terminal window and type `which conda`.
If should print out a path with "anaconda3" in the name.
- **windows**: anaconda python should have installed a program called
Anaconda Prompt. Open this and type the commands below into the prompt.

You can then install the libraries with the following (run each line one at a
time):

```
conda install keras
conda install opencv
conda install tensorflow

pip install keras-retinanet
pip install dvt
```

Once that is done, you should be able to follow along with most of the tutorial.

## References

A very limited set of materials about image analysis that either directly
address humanities applications or are particularly accesible and interesting to
a general audience. Please suggest additional references as we would like to
expand this list as widely as possible.

- Arnold, Taylor, and Lauren Tilton. *Humanities Data in R*. New York: Springer, 2015.
[link](https://link.springer.com/book/10.1007%2F978-3-319-20702-5).
- Arnold, Taylor, and Lauren Tilton. "Distant viewing: analyzing large visual corpora"
*Digital Scholarship in the Humanities*. [link](https://doi.org/10.1093/digitalsh/fqz013)
- Olga Russakovsky, Jia Deng, Hao Su, Jonathan Krause, Sanjeev Satheesh, Sean Ma, Zhiheng Huang,
Andrej Karpathy, Aditya Khosla, Michael Bernstein, Alexander C. Berg and Li Fei-Fei.
"ImageNet Large Scale Visual Recognition Challenge". IJCV, 2015. [link](https://arxiv.org/pdf/1409.0575v1.pdf)
- Wevers, Melvin, and Thomas Smits. "The visual digital turn: Using neural networks to study historical images"
*Digital Scholarship in the Humanities*. [link](https://doi.org/10.1093/llc/fqy085)
