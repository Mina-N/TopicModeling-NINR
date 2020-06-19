# TopicModeling-NINR

## Overview
You are currently on the 'awardedNIA19_iter1' branch. This branch was created off of the 'awardedNINR19_noSA_iter3' branch. It has been modified to create topic models from grant applications for the National Institute of Aging in 2019.

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

