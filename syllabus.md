# Introduction to Python Programming for Data Analysis

```{note}  
This is a beta version of the course syllabus, intended to give an idea of the scope and topics I would like to cover as well as the approach. 
```

## Acknowledgment 

## Course Information
Fall 2023; 3 credit hours 

## Prerequisites
Some introductory stats, research design, motor control and biomechanics courses will be helpful **[Note from Romeo: "If this is a 300-level introduction course, then students would have some stats and research design in 2nd year, and will also have completed intro to biomechanics and motor behaviour in 2nd year." Jean mentioned possible 2nd year course.]**. No prior programming experience is expected or required.

## Links to Other Courses
Completion of this course will help prepare you for the following courses:
- Introduction to Computational Modeling 
- KIN 419: Laboratory Investigations in Neuromechanical Kinesiology

## Instructors
**Professor**: [Hyosub Kim](https://osf.io/y75ud/wiki/home/)  
**Email**: [hyosub@udel.edu](mailto:hyosub@udel.edu)  
**Office Hours**: TBD  

**Teaching Assistant**: My very good TA   
**Email**: TBD   
**Office Hours**: TBD   

## Communication
We will use (Canvas, Microsoft Teams, Edstem...?) to facilitate discussion outside of class. 

## Course Structure
Classes will utilize a mixed format of lectures, videos, class discussions, labs, and student presentations in order to foster an interactive and engaged learning experience. A link to the current schedule can be found here (create link) and will be updated as we go. 

Need to really think about this. Some ideas and things to consider:
- 3 credit hour course
- Meet 2 days/week for 1.5 hrs per session?
- Split meetings into 1 lecture, 1 tutorial/lab per week 
- Notes on UBC's CS 0.5 ([Dawson et al 2018](https://www.cs.ubc.ca/~meghana/sigcse_2018_dawson.pdf)):
    - For 4 credit hr course, split into one 80-minute lecture and one 50-minute tutorial per week
    - "In each content module students are assigned pre-class work consisting of reading custom course materials, solving problems using the new concepts, and writing and submitting a brief summary of what they learned and at least one question about the module or how it relates to the rest of the course."
    - "In lecture we use Just-In-Time teaching [15] and deliver short mini-lectures to address the questions raised by students in their pre-class work. Students spend the majority of lecture time working in small groups to solve problems on a worksheet package; we usually interject with one or two 5-10 minute mini-lectures and/or wrap-up discussion that focuses on key problems from the worksheets. Completed worksheet packages are collected in the following lecture, graded for completion, and returned electronically."
    - "In tutorials, students work in small groups on weekly homework assignments with TA support. They also complete weekly peer review assignments that require them to solve a problem, assess three of their peers’ solutions, and complete a self-assessment of their own solution."


## Course Overview
This course provides hands-on experience with learning to program in Python. Students will learn how to think algorithmically in order to process, visualize, and analyze data related to all types of research questions. Through a combination of tutorials, problem sets, and a final project, students will learn some of the most important tools and techniques in the Python data science ecosystem. This course will be especially useful for undergraduate students interested in getting actively involved in research at UBC. In addition, this course provides a strong background for future advanced undergraduate and graduate work in computational approaches to kinesiology, including modeling. However, even for students who do not plan to do scientific research in the future, this course will still provide a solid foundation in core computing and data science skills that will serve them well whether going into industry, healthcare, or another technical field.

## Learning Objectives

The course is designed to achieve three primary goals:

1. You will learn to write programs in a high-level programming language (i.e., Python).
2. You will learn to process, visualize, and analyze data using some of the most powerful (and popular) tools in data science (e.g., pandas, NumPy, Jupyter).
3. You will learn to approach and solve novel problems in a logical, step-wise (algorithmic) manner.
4. You will learn to effectively visualize and present the results of your data analyses.
5. You will leave the class well-prepared to advance your programming and data analysis skills, whether in advanced undergraduate or graduate courses (e.g., statistics, modeling, machine learning, etc.), academic research, or industry. 

Major course themes:

- Core programming skills
- Data exploration and visualization
- Data analysis

Here are specific topics related to Python and scientific computing we will cover in this course: 

- Why programming/Python/data science?
- What is a computer program?
- Variables and assignment
- Data types and conversion
- Lists
- Dictionaries
- Conditional statements and control flow
- For loops
- Functions
- File I/O (input & output)
- Scientific computing using NumPy
- Data visualization with Matplotlib and Seaborn
- Structuring data with Pandas

We will actively apply the core programming skills you learn throughout the course to explore and better understand research-related questions and examples (**[Note: some of these are pie-in-the-sky ideas that will likely not make the cut.]**):
- Work with Romeo and Jean (and others) on good 'example use' cases and datasets (interleave with concepts from Romeo's lab/methods course KIN 419)
- EMG: reflex responses
- Postural responses
- From JS: introduce derivates and integrals for discretized values
    - Students experiment with position, velocity, acceleration traces (JS)
- Some linear algebra?
    - Change between coordinate systems within a sports science context (JS)

- Exploratory data analysis
- Working with repeated measures data
- Data processing and dealing with outliers
- Statistical inference using Python 
  - Bayes' Theorem
  - Regression (introduce vector and matrix notation here?)
- Working with behavioral data
  - Kinematics (e.g., reach trajectories)
  - Reaction times
  - Signal Detection Theory
  - Psychophysical functions
  - Sensorimotor adaptation
- Signal processing
  - Time vs frequency domain representations
  - Sampling
  - Filtering (consider using Paul Gribble's iPhone and heartrate exercise)

## Textbook
The current website is an online textbook developed by your course instructor, leveraging the wonderful world of open source educational materials (see [acknowledgments in the Intro](intro.md)). You will refer to this website for reading, lecture slides, videos, and other exercises. Links to other helpful websites and resources will also be provided here. 

## Computing Environment
The course will rely on a online computing environment called Jupyter. Each student will have their own JupyterHub instance and can connect to this from a variety of devices over the internet. The address of the class JupyterHub is here (create link). You will log in with your normal UBC credentials.

## Learning Assessment
Much of the work you do for the course will, for good reason, require lots of programming. We will mostly be using Jupyter notebooks for assignments and labs that you will turn in for grading. [Using Jupyter tools to assess student learning](https://jupyter4edu.github.io/jupyter-edu-book/getting-going.html). 

The grade in the course will be determined by the following categories:

### Class Participation (xx% of grade)??
Attendance and participation is critical for success in this course as it takes a hands-on, practical approach to programming and data analysis. 

### Labs (xx% of grade)
The main part of the course will consist of several labs. These labs will explore key concepts in kinesiological research, with a focus on the brain-behavior relationship, and will consist of multiple exercises.  Most of this work will take place in the Jupyterhub.

### Homework (xx% of grade)
Programming is a skill, and, like any skill, requires consistent practice. As such, you will receive regular programming assignments meant to solidify the conceptual knowledge gained through readings, videos, and lectures. 

Thoughts:
- Skills-based notebooks or DataCamp exercises (must be prior to each session - unlimited opportunities to get right)
- More involved problem set each week/module (see Gribble course, NYU course)

### Final Project (xx% of grade)

## University Policies

UBC provides resources to support student learning and to maintain healthy lifestyles but recognizes that sometimes crises arise and so there are additional resources to access including those for survivors of sexual violence. UBC values respect for the person and ideas of all members of the academic community. Harassment and discrimination are not tolerated nor is suppression of academic freedom. UBC provides appropriate accommodation for students with disabilities and for religious observances. UBC values academic honesty and students are expected to acknowledge the ideas generated by others and to uphold the highest academic standards in all of their actions.  

Details of the policies and how to access support are available on [the UBC Senate website](https://senate.ubc.ca/policies-resources-support-student-success/).

## Other Course Policies

## Learning Resources


