# Further Reading 

This is a list with material for further study.

It contains links for:

1. [Reproducible Science](#reproducible-science)
1. [Programming](#programming)
1. [Scientific Python](#scientific-python)
1. [Git and GitHub](#git-and-github)
1. [Linux and Linux Command Line](#linux-and-linux-command-line)
1. [Containers](#containers)
1. [General Material](#general-material)
1. [Books](#books)

----

## Reproducible Science
	
The following links, are focusing on Reproducible Research

### [Reproducible Science Curriculum](https://reproducible-science-curriculum.github.io/rr-jupyter-workshop/)

This is the curriculum, on which the workshop was based on.

- [Introduction](https://github.com/Reproducible-Science-Curriculum/introduction-RR-Jupyter)
- [Organization](https://github.com/Reproducible-Science-Curriculum/organization-RR-Jupyter)
  - The main documents are under the [_episodes folder.](https://github.com/Reproducible-Science-Curriculum/organization-RR-Jupyter/tree/gh-pages/_episodes)
- [Data Exploration](https://github.com/Reproducible-Science-Curriculum/data-exploration-RR-Jupyter)
- [Automation](https://github.com/Reproducible-Science-Curriculum/automation-RR-Jupyter)
- [Publication & Sharing](https://github.com/Reproducible-Science-Curriculum/publication-RR-Jupyter)

### iDigBio, Reproducible Science Workshop

This workshop is also based on the Reproducible Science Curriculum. However, it is using an older version of the program based on R. The "theoretical" topics are still the same though.

- [Workshop Website](https://reproducible-science-curriculum.github.io/2015-06-01-reproducible-science-idigbio/)
- Recordings of Sessions: 
  - Day 1: [Part 1](http://idigbio.adobeconnect.com/p45n2kdth1j/), [Part 2](http://idigbio.adobeconnect.com/p8vfk4queh1/), [Part 3](http://idigbio.adobeconnect.com/p2nreqf99s9/), [Part 4](http://idigbio.adobeconnect.com/p156843vs2o/)
  - Day 2: [Part 1](http://idigbio.adobeconnect.com/p3lsgjahmxq/), [Part 2](http://idigbio.adobeconnect.com/p9gp7rkpwsc/), [Part 3](http://idigbio.adobeconnect.com/p8hlvslbntu/), [Part 4](http://idigbio.adobeconnect.com/p4ypgv95881/)
- [Workshop Wiki](https://www.idigbio.org/wiki/index.php/Reproducible_Science_Workshop)

### Reproducible Research: Walking the Walk

This is a hands-on tutorial, that took place on SciPy 2014. It includes examples of using Docker to create the same environment, and Dexy to automate document creation. All the material is available online, and there is also a recording for the whole duration of the workshop.

- [Website](https://reproducible-research.github.io/scipy-tutorial-2014/)
- [GitHub repo](https://github.com/reproducible-research/scipy-tutorial-2014)
- YouTube Recordings: [Part 1](https://www.youtube.com/watch?v=EzX7MN_bzqg), [Part 2](https://www.youtube.com/watch?v=HCyHn_by3N0)

### Reproducible Research -- YouTube playlist

A number of presentation regarding Reproducible Research

- [YouTube Playlist](https://www.youtube.com/playlist?list=PLbbGaMTX2ihUH22kImmLkTz-9KfQ0g_4g)


## Programming

An introduction to programming using Python
- [How to Think Like a Computer Scientist](https://interactivepython.org/runestone/static/thinkcspy/index.html)
  

Programming Exercises:

- Advent of Code: [2015](http://adventofcode.com/2015), [2016](http://adventofcode.com/2016)
  - Advent of code is a website that contain programming challenges. You will get an input and then a form to put your output to be checked automatically. 


- [The cryptopals crypto challenges](https://cryptopals.com/)
  - More advanced programming challenges, focusing on security topics


## Scientific Python

Also a number of great videos and tutorials, for Python and generally for Data Science, can be found at the Enthough and PyData channels on YouTube:
	
- [PyData](https://www.youtube.com/user/PyDataTV/feed)
- [Enthough](https://www.youtube.com/user/EnthoughtMedia/feed)

For example:

- [IPython and Jupyter in Depth](https://www.youtube.com/watch?v=VQBZ2MqWBZI)

## Git and GitHub

To learn more about Git/Github you can check the following. 

### Git for Scientists: A Tutorial

An introduction to Git, structured specifically for scientists.

It uses [tryGit](https://try.github.io/levels/1/challenges/1), so you can follow along, even if you don't have Git installed on your system.

- [Website](http://nyuccl.org/pages/GitTutorial/)

### Atlassian Git Tutorial

A longer tutorial on git, from Atlassian. The examples use Bitbucket, and not GitHub. However the commands are the same

- [Website](https://www.atlassian.com/git/tutorials)


### Udacity Git Course

A free course on Git, from Udacity.

- [Course Website](https://www.udacity.com/course/version-control-with-git--ud123#)


### ProGit

The standard textbook to get more familiar with Git and Github

- [Book Website](https://git-scm.com/book/en/v2)


## Linux and Linux Command Line

### Introduction to Linux, edX course

A complete (free) course that will provide you with a good working knowledge of the Linux system and basic command line operations

- [Course Website](https://www.edx.org/course/introduction-linux-linuxfoundationx-lfs101x-1#!)

## Containers

Here are some resources regarding the use of general containers ([Docker](https://www.docker.com/)), or some containers specialized in scientific computing ([Singularity](http://singularity.lbl.gov/))

### Docker

Docker is platform based on container virtualization. To try Docker, you can either install it from the [Docker Website](https://www.docker.com/) or use the [Play with Docker Website](http://labs.play-with-docker.com/). Play with Docker, provides access to a testing virtual machine with docker installed. The machine is destroyed after a few hours. You can use it to follow the workshops presented here.

#### Introduction to Docker

A very good workshop from Jérôme Petazzoni, on PyCon2016, showing the basic Docker fuctionalitites. 

- [YouTube Video](https://www.youtube.com/watch?v=ZVaRK10HBjo)

#### Advanced Docker Workshop

An advanced workshop, from Jérôme Petazzoni, on PyCon2017

- [YouTube Video](https://www.youtube.com/watch?v=EuzoEaE6Cqs)
- [Slides](http://view.dckr.info:8080/#1)

#### Lecture on Container Virtualization

This is a single lecture, getting into more details on container virtualization

- [Lecture Video](https://www.youtube.com/watch?v=nanHh0t4ssE&list=PLE6LEE8y2Jp_z8pkiuvHo7Vz-eQEKsk-I&index=33)


### Singularity

Singularity containers are containers specialized for HPC and scientific usecases. They are similar to Docker, but more optimized to this usecase.

#### Singularity: Scientific containers for mobility of compute

An article explaining what singularity containers are and their basic usage.

- [Article Link](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0177459)


#### Singularity: Containers for Science, Reproducibility, and HPC
  
A youtube presentation of Singularity containers

- [YouTube Video](https://www.youtube.com/watch?v=DA87Ba2dpNM)


## General Material

- [A Quick Guide to Software Licensing for the Scientist-Programmer](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002598)
- [Choose A Licence](https://choosealicense.com/)
  - [Licenses](https://choosealicense.com/licenses/)
  - [Detailed Overview](https://choosealicense.com/appendix/)
- [DataTau](http://www.datatau.com/): A website with general news regarding Data Science.
- [Good Enough Practices in Scientific Computing](https://arxiv.org/abs/1609.00037)
- [Best Practices in Scientific Computing](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001745)
- [Opening Science](http://book.openingscience.org/)


## Books

Some general (non-technical) book recommendations:

- [Who Moved My Cheese, by Dr Spencer Johnson](https://www.goodreads.com/book/show/4894.Who_Moved_My_Cheese_):
  A book that teaches you how to deal with constant changes
  
- [The Dip, by Seth Godin](https://www.goodreads.com/book/show/324748.The_Dip):
  Thought about when to quit and when to stay.
  
- [So Good They Can’t Ignore You, by Cal Newport](http://calnewport.com/books/so-good/):
  On why it's more important to focus on building your skills, and why "Following your passion" is not a good advice.

- [Deep Work, by Cal Newport](http://calnewport.com/books/deep-work/):
  By the same author, recommendations for how to work more focused and why that is important.
  
- [Thinking, Fast and Slow](https://www.goodreads.com/book/show/11468377-thinking-fast-and-slow):
  A lot of information on how we think and behave.
  
- [How to Read a Book](https://www.goodreads.com/book/show/567610.How_to_Read_a_Book):
  Self explanatory title.
  
- [Incerto, by Nassim Nicholas Taleb](http://www.fooledbyrandomness.com/):
  A philosophical and practical essay on uncertainty. It is not a "Data Science" book, but it might be the most critical book that you read, regarding Data Science.


---

----

# Revised Agenda

Due to the issues with the Jupyter Notebooks, (and the lack of time), we'll focus more on the other parts of the workshop, that are not so heavily dependent on Jupyter.

## 16:00 -- 16:15

Discussion on the Forensic Exercise (Organization Exercise 01 [html](notebooks/02_organization_exercise_01.html))

## 16:15 -- 16:45

Project Organization

## 16:45 -- 17:15

Organization Exercise 02 [html](notebooks/03_organization_exercise_02.html)

## 17:15 -- 18:15

Publication & Sharing Exercise [html](notebooks/06_publication_and_sharing.html)




---

# Workshop Agenda

[![Join the chat at https://gitter.im/ssgoe2017/Lobby](https://badges.gitter.im/ssgoe2017/Lobby.svg)](https://gitter.im/ssgoe2017/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[Etherpad Link](https://etherpad.gwdg.de/p/ssgoe2017)

## S21 Introduction, 11:30 -- 12:30

This would be the introductory session for concept of Reproducible Research

- The slides of the introduction are available [here](./pdfs/S21_Introduction.pdf)
- To follow allong, during the Jupyter section, you need to 
  follow the instructions from here [Workshop Preperation](notebooks/00_preperation.html).
- [Introduction to Jupyter](https://reproducible-science-curriculum.github.io/introduction-RR-Jupyter/slides/Jupyter_Intro_Background.slides.html#/)
- [Working with Notebooks](https://reproducible-science-curriculum.github.io/introduction-RR-Jupyter/slides/Workshop%20slides%20-%20using%20the%20notebooks.slides.html#/)
- Now, for the remaining time open (from your Jupyter Browser), the notebook `01_navigation.ipynb` and read / evaluate all of it's cells
  
## S22 Organization & Data Exploration 14:00 -- 15:30
  
In this part we'll talk about how to better organize a project. Your first (practical) task is to follow the instructions from the Organization Exercise 01.

  
  - The slides of the organization lecture can be found [here](./pdfs/S22_Organization.pdf)
- Organization Exercise 01 [html](notebooks/02_organization_exercise_01.html) / [ipynb](notebooks/02_organization_exercise_01.ipynb)
- Organization Exercise 02 [html](notebooks/03_organization_exercise_02.html) / [ipynb](notebooks/03_organization_exercise_02.ipynb)
- Data Exploration [html](notebooks/04_data_exploration.html) / [ipynb](notebooks/04_data_exploration.ipynb)

## S23 Automation, 16:00 -- 17:30

Here, we'll automate the analysis from the previous step by implementing functions

- Automation Exercise [html](notebooks/05_automation.html) / [ipynb](notebooks/05_automation.ipynb)

## S24 Publication & Sharing, 17:30 -- 18:30

Here we'll see how to export a notebook, share it, and publish our results.

- Publication & Sharing Exercise [html](notebooks/06_publication_and_sharing.html) / [ipynb](notebooks/06_publication_and_sharing.ipynb)

# References

The majority of the material, is based on the [Reproducible Science Curriculum](https://github.com/Reproducible-Science-Curriculum), which was in turn based on [Data Carpentry](http://www.datacarpentry.org/) material for reproducible research.
	
# Disclaimer

The opinions expressed in this article are the committer's own and do not necessarily reflect the views of GWDG.
