# Project 0: Introduction and Fundamentals
## Titanic Survival Exploration (Optional)

## Project Overview
Welcome to the Machine Learning Engineer Nanodegree!

In this ***optional*** project, you will create decision functions that attempt to predict survival outcomes from the 1912 Titanic disaster based on each passenger?s features, such as sex and age. You will start with a simple algorithm and increase its complexity until you are able to accurately predict the outcomes for at least 80% of the passengers in the provided data. This project will introduce you to some of the concepts of machine learning as you start the Nanodegree program.

In addition, you'll make sure Python is installed with the necessary packages to complete this project. There are two Python libraries, `numpy` and `pandas`, that we'll use a bit here in this project. Don't worry about how these libraries work for now ? we'll get to them in more detail in later projects. This project will also familiarize you with the submission process for the projects that you will be completing as part of the Nanodegree program.

## Software Requirements
This project uses the following software and Python libraries:

- [Python 2.7](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [Jupyter Notebook](http://ipython.org/notebook.html)

If you already have Python 2.7 installed on your computer, then you can install `numpy`, `scikit-learn`, and Jupyter Notebook (formerly known as 'iPython') by using [pip](https://pip.pypa.io/en/stable/) on the command line. [This page](http://www.lfd.uci.edu/~gohlke/pythonlibs/) may also be of use for some packages for Windows users, if pip has trouble performing the installation. After installing pip, you can install all the packages with the following command:

`sudo pip install numpy pandas matplotlib jupyter scikit-learn`

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

## Starting the Project

For this assignment, you can find the `titanic_survival_exploration.zip` archive containing the necessary project files as a downloadable in the **Resources** section. *You may also visit our [Machine Learning projects GitHub](https://github.com/udacity/machine-learning) to have access to all of the projects available for this Nanodegree.*

This project contains three files:

- `Titanic_Survival_Exploration.ipynb`: This is the main file where you will be performing your work on the project.
- `titanic_data.csv`: The project dataset. You?ll load this data in the notebook.
- `titanic_visualizations.py`: This Python script contains helper functions that will visualize the data and survival outcomes.

To open up the Jupyter notebook, you will need to open the Command Prompt or PowerShell (Windows), or Terminal application (Mac, Linux). Use the `cd` command to navigate through the file structure of your computer to where you extracted the project files. For example, on Windows you might start with `cd C:\Users\username\Documents\` (substituting in the username) to get to the Documents folder. On Mac you might start with `cd ~/Documents/`. You can use the `dir` (Windows) or `ls` (Mac, Linux) command to list files and folders in your current directory; `cd ..` will move you up a directory if you get lost.

Once you?ve navigated to the folder containing the project files, you can use the command `jupyter notebook Titanic_Survival_Exploration.ipynb` to open up a browser window or tab to work with your notebook. Follow the instructions in the notebook and answer each question presented to successfully complete the project. A **README** file has also been provided with the project files which may contain additional necessary information or instruction for the project. 

## Submitting the Project

### Evaluation
Your project will be reviewed by a Udacity reviewer against the **<a href="https://review.udacity.com/#!/rubrics/147/view" target="_blank"> Titanic Survival Exploration project rubric</a>**. Be sure to review this rubric thoroughly and self-evaluate your project before submission. All criteria found in the rubric must be *meeting specifications* for you to pass.

### Submission Files
When you are ready to submit your project, collect the following files and compress them into a single archive for upload. Alternatively, you may supply the following files on your GitHub Repo in a folder named `titanic_survival_exploration` for ease of access:
 - The `Titanic_Survival_Exploration.ipynb` notebook file with all questions answered and all code cells executed and displaying output.
 - An **HTML** export of the project notebook with the name **report.html**. Instructions for exporting to HTML are at the bottom of the notebook; you may need to install the [mistune](https://pypi.python.org/pypi/mistune) package first, e.g. via `pip install mistune` in the terminal.

Once you have collected these files and reviewed the project rubric, proceed to the project submission page.

### I'm Ready!
When you're ready to submit your project, click on the **Submit Project** button at the bottom of this page.

If you are having any problems submitting your project or wish to check on the status of your submission, please email us at **machine-support@udacity.com** or visit us in the <a href="http://discussions.udacity.com" target="_blank">discussion forums</a>.

### What's Next?
You will get an email as soon as your reviewer has feedback for you. In the meantime, review your next project and feel free to get started on it or the courses supporting it!