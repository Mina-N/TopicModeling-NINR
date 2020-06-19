# TopicModeling-NINR

## Overview
This repository contains implementations of the algorithm Latent Dirichlet Allocation in Python and R. It builds off the work of (1) Alaz Sengul, a 2019 Software Engineering Intern within the Office of Program Planning, Analysis, and Evaluation at the National Institutes of Health and (2) Nathan Moore, a Data Scientist at the Office of the Director. 

This repository currently contains six branches:
1. master
2. alaz
3. awardedNINR19_iter1
4. awardedNINR19_compPythonR_iter2
5. awardedNINR19_noSA_iter3
6. awardedNIA19_iter1

Select any of the six branches to read more about them in their respective README files. The master branch serves as a foundation for understanding the other five. 

## Research Questions
1. Who is the decision-maker? **National Institute of Nursing Research (NINR) leadership, policy analysts, communications, and other staff**

2. What is the decision being improved? **Which research grant applications align with NINR's historically funded research areas and how well do they align? Which grants do not align with NINR's historically funded research areas? Of these two groups, which topics are associated with each group and which grants are grouped with each topic?**

3. What is the value of an improved decision? **Affirmation of the current "hands on" approach for program officer assignments, less time binning grant applications into research categories, more accurate and nuanced clasifications of grants, more precise alignment of NINR's research portfolios and Strategic Plan with applicant interests**

## Pre-Installation Instructions
* Install the package manager pip on your local machine.

* Install an IDE that supports R and/or Python (I use RStudio and PyCharm).

## Installation Instructions for a Windows Machine
1. Clone the web URL of this repository into a directory of your choice on your local machine:
- Run 'git clone [URL]' on the command prompt, where [URL] is the URL of this repository.

2. Create a folder named "data" at the head of your directory. Place your Excel spreadsheets containing awarded and/or not awarded research grants in your newly created data folder.

3. To run the R code, navigate to the R directory and open up the Rmd file in your favorite IDE (such as RStudio). 

4. To run the Python code, navigate to the Python directory. Then, create a virtual environment in this directory:
* Run 'py -m venv env' on the command prompt to create a virtual environment that supports Python 3 development. This command will create a directory named 'env'.
* To activate the virtual environment, run '.\env\scripts\activate' on the command prompt.
* Once the virtual environment is activated, run 'pip install -r requirements.txt' to install the Python libraries that this repository depends on.
* You're all set! Now run 'jupyter notebook' to activate the IPython Notebook.




