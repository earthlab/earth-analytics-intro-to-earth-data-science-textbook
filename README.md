# Earth Analytics - Intro to Earth Data Science Textbook Materials

[![DOI](https://zenodo.org/badge/205400714.svg)](https://doi.org/10.5281/zenodo.3382162)

The Introduction to Earth Data Science textbook is an introductory-level,
online textbook created by instructors in the Earth Analytics Education
Initiative at Earth Lab (University of Colorado - Boulder). The textbook supports
courses in the Professional Graduate Certificate in <a href="https://www.colorado.edu/earthlab/earth-data-analytics-foundations-professional-certificate" target="_blank">Earth Data Analytics - Foundations at CU Boulder</a> which reaches professional students in addition to undergraduate
and graduate students at CU.

This introductory online textbook provides core scientific programming skills
required to efficiently work with a suite of earth systems data in the Python
programming language. It also covers Bash, Git/Github.com, and Jupyter Notebook
for implementing open reproducible science workflows.


## Analytics As Of August 2021
This repository contains the rendered Markdown and .html files used to build the
course. The textbook is available online at the
<a href="https://www.earthdatascience.org/courses/intro-to-earth-data-science/" target="_blank">EarthDataScience.org learning portal</a> which has served over 5
million users since its 2018 launch. The textbook has been vetted by over XX
students who who have participated in our courses, workshops and trainings.

## Repository Structure

The repo is structured as follows:

* `_posts/courses/intro-to-earth-data-science`: This directory contains the markdown files needed to build the web pages hosted on earthdatascience.org using Jekyll & GitHub Pages
* `_site/courses/intro-to-earth-data-science/images`: This directory contains images needed to build the lessons.

Lessons found in this repository are compiled and tested using a continuous
integration build that uses the Earth Lab [docker environment](https://github.com/earthlab/r-python-eds-lessons-env).
