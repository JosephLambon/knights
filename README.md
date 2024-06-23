# Knights
>### (CS50AI) Week 1, Coursework 1

## Contents
1. [Project Synopsis](#project_synopsis)
2. [Project Resources](#project_resources)
3. [Setup and Usage](#setup)


## <a id='project_synopsis'> Project Synopsis </a>
The specification of this project can be found <a href="https://cs50.harvard.edu/ai/2024/projects/1/knights/">here</a>.


The aim was to practice utilising Propositional Logic, and demonstrate the significance of Knowledge Engineering. This included implementing First Order Logic, as well as Inference Rules such as De Morgan's Law.
## <a id='project_resources'> Project Resources </a>
* [Python](https://www.python.org/)


## <a id='setup'> Setup and Usage </a>
#### [NOTE: Any lines of code included are intended for the command line]

### 1. Install prerequisites
a. Install [Python](https://www.python.org/) </br>
b. Install [virtualenv](https://virtualenv.pypa.io/en/latest/)
``` 
 pip install virtualenv
```
### 2. Setup virtual environment
* Create virtual environment </br>
```
# Run this line on the command line
# Replace 'env_name' with whatever your desired env's name is.

virtualenv env_name
```
* Start virtual environment
```
# This will activate your virtualenv.

source env_name/bin/activate
```
* Install required packages
```
# Running this in your command line will install all listed packages to your activated virtual environment

pip install -r requirements. txt
```
### 3. Change directory
* Change into the 'Tasks' folder.

### 4. Run script
```
# This will run the script, drawing conclusions for each puzzle based on the knowledge bases provided.

python knights.py
```
