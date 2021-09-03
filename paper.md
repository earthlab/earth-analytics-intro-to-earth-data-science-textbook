
---
title: 'Get Started with Open and Reproducible Data Science for Earth and Environmental Data: The Introductory Earth Analytics Online Textbook'
tags:
  - Python
  - data science
  - earth analytics
  - earth data science
  - environmental data science
  - spatial data
  - github
  - git
  - bash
authors:
  - name: Leah A. Wasser
    orcid: 0000-0002-8177-6550
    affiliation: "1, 2, 3"
  - name: Jenny Palomino
    orcid: 0000-0003-4879-9299
    affiliation: "4"
  - name: Nathan Korinek
    orcid: 0000-0002-8177-6550
    affiliation: "1, 2"
  - name: Max Joseph
    orcid: 0000-0002-7745-9990
    affiliation: "5"
affiliations:
 - name: Earth Lab, University of Colorado - Boulder
   index: 1
 - name: CIRES, University of Colorado - Boulder
   index: 2
 - name: pyOpenSci
   index: 3
 - name: Google
   index: 4
 - name: <<<Max's spot>>>>
   index: 5

date: 3 September 2021
bibliography: paper.bib

---

# Summary
As science becomes increasingly data-driven there is a growing demand for skills at the intersection of science and data science in both industry and academia. However, it can be overwhelming for those with little or no background in scientific programing or data science to develop these skills. Many scientists "learn by doing" using search engines and sites such as StackOverflow to troubleshoot issues while working with their data. While this approach to learning allows a scientist to process their data, they often miss learning core concepts such such as version control, reproducibility, interdisciplinary communication and collaboration approaches and best coding practices. Strong knowledge in these core  will in the long run empower scientists with the ability to apply skills to different data types and applications more effectively and efficiently. The Introduction to Earth and Environmental Data Science textbook provides an initial stepping stone for a scientist or science-engaged person to begin learning technical open reproducible science skills. Earth and environmental data science (EDS), also known as earth analytics, refers skills at the intersection of science and data science and includes: 1. technical open reproducible data science skills; 2. understanding of different data types and structures (including spatial, hierarchical, tabular); 3. data collection methods and associated quality issues that are important to consider in data processing and 4. scientific domain knowledge needed to make processing decisions that inform science questions. As defined we also include soft skills such as science communication and interdisciplinary collaboration that are critical in today's growing space of interdisciplinary team science.

This online textbook, which is a companion to the introductory "Bootcamp" course [@palomino_jenny_2021_5418486] in the Earth Data Analytics Professional Program run by the Earth Lab Education Initiative at the University of Colorado, Boulder; it assumes no prior technical skills or knowledge. Users who are not engaged in our program can chose to [complete the Bootcamp course content asynchronously using the online course](https://www.earthdatascience.org/courses/earth-analytics-bootcamp/). Instructors can repurpose textbook content to use as modules in their existing courses. The textbook begins by introducing foundational principles of open reproducible science including reproducibility best practices and clean code approaches. It also teaches the basics of Bash, Git, and GitHub for both individual and collaborative use. Finally it covers an introduction to basic data types (spatial, tabular) and associated Python data structures including Pandas [@jeff_reback_2021_5203279] DataFrames, Numpy [@Harris_2020] Arrays, Xarray [@stephan_hoyer_2021_5130718] objects for larger raster data processing and GeoPandas [@kelsey_jordahl_2021_4569086] GeoDataFrames). All lessons are framed in a scientific context using real world examples and activities which ensures a fusion of both data science with science concepts in each chapter. All tools taught in the textbook are free and open source. Lessons are also supported by EarthPy [@Wasser2019], an open source Python package that makes it easier to download teaching data subsets consistently to a users home (or other) directory and to perform spatial operations. To ensure concepts taught are current, the textbook is updated each year. For example in 2020 and 2021 we updated lessons to new GitHub authentication protocols and to use Xarray for raster data processing. Lessons are further tested by a Continuous Integration workflow that builds and pushes the lessons to our earthdatascience.org learning portal repository for final review and publication. The earthdatascience.org learning portal receives over 200,000 unique monthly users and has served millions of users across the world since its 2018 launch. The textbook has been developed, refined and used for three years and has been vetted through our courses by over 100 students in our courses and summer programs.

# The Need and Story Behind The Textbook
While there are many lessons and tutorials online including those by the Carpentries (e.g. Intro to Git  [@madicken_munk_2019_3264950], navigating where to start learning EDS and knowing what skills to learn first as they apply to a science domain can still be challenging for a beginner given the many different tools available. Further, most existing resources do not connect fundamental knowledge of scientific data structures (raster, vector, text, tabular) and with associated Python data structures
(Xarray objects, Numpy Arrays, GeoDataFrames, DataFrames) and scientific applications that are required to build a strong foundation in EDS. The Introductory EDS textbook begins with introducing readers to the significance and core concepts associated with open reproducible science. It has an entire section dedicated to data types and another for Python data structures. It also guides a new user through setting up a local environment [@wasser_leah_2021_5228300] on their computer using the conda-forge channel and conda to manage packages which can be a hurdle in and of itself particularly when using Python. The textbook is supported by the curated and tested Earth Analytics Python Environment [@leah_wasser_2021_4657501] which can be installed on a local computer.

# The Story of the Online Textbook
Our Earth Lab Education Initiative developed the professional graduate program in Earth Data Analytics with beginning users in mind given the growing demand for these skills. Many professionals are returning to school to gain the technical skills that may have been missed during their undergraduate and graduate students. Further undergraduates are completing their degrees without these skills and in turn seeking programs and courses such as ours. Our program is tailored to both graduate and undergraduate students. We teach using a blended online and in-person classroom approach supported by active learning principles where students are immersed in EDS challenges and learn technical skills as they address those challenges programmatically. To ensure broader access to our content, we publish lessons online to facilitate and democratize access to these skills.

Data topics in the textbook include fundamental introductions to formats including .csv files, spatial shapefiles and raster file formats. The textbook also introduces Jupyter Notebooks which enable reproducibility by connecting code, data inputs and outputs. Finally it introduces best practices for organizing and managing data and code in projects using strategic and expressive file naming, clean code best practices, documentation and version control to track changes and collaborate with others. Lessons include interactive coding examples which can be completed using a free-to-use platform such as Google Colab or their local environment installation.

# Acknowledgements
We acknowledge contributions from many who have contributed to our textbook via edits and content suggestions and updates. These people include students in the Earth Data Analytics program who catch issues with the lessons, Martha Morrisey and Will Norris and others for work and feedback on some of the lessons. We also acknowledge Joseph Tucillo and Gina Li for contributing to our lesson development CI build and workflow. We would also like to acknowledge our textbook reviewers <!insert names here> for providing us with helpful feedback that improved the lesson content.

# References
