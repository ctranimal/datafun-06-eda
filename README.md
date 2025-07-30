# Ken McTran's Project 6 EDA Notebook

## Overview

Project 6 is an opportunity to create your own custom exploratory data analysis (EDA) project using
GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.


## Workflow:
    Repeatable workflows include the following:
    1. Follow best-practices for git-update-push to ensure workable code are regularly checked-in into cloud-based Github repository. Very brief summary: (i) create a GitHub account (ii) on a local Mac terminal, issue command `git clone https://github.com/ctranimal/datafun-06-eda ' to clone to local computer (iii) at regular interval, check-in stable, working code with helpful comments by issuing command `git add .` , `git commit -m comments` and `git push`
    2. python3 -m venv .venv  <!-- On Mac, this step create a local .venv directory to install tool into --> 
    ## On Mac, next 2 lines install needed tools (documented in requirements.txt ) into .venv environment
    3. python3 -m pip install --upgrade pip setuptools wheel
    4. python3 -m pip install -r requirements.txt
    5. 1. source .venv/bin/activate <!-- On Mac, this command would activate the environment -->
    6. At terminal, use the command "code ~/Repos/datafun-06-eda" to launch VS Code (previously installed on MAC) to open/edit/execute code related to this project.
    7. Within VS Code, open a Terminal windows, to run my written *.py code, issue the commands `python3 *.py`
   
## Data Sources.
1. For this project, I've chosen Seaborn's carcrashes. There are lots of car-crashes. It intriques me and I would like to dig further into the data: which preventable crashes can be prevented. Further details can be found at: https://github.com/mwaskom/seaborn-data/blob/master/README.md and https://www.kaggle.com/datasets/fivethirtyeight/fivethirtyeight-bad-drivers-dataset 