[<img width=900 src="https://github.com/YashBangera7/FDSA-DSCI-633-Fall2021/blob/main/images/image1.jpg">](https://github.com/YashBangera7/FDSA-DSCI-633-Fall2021/blob/main/README.md)   


## Python Basics

### 0. Learn Python basics on [Codecademy](https://www.codecademy.com/learn/learn-python) (free version), [w3schools](https://www.w3schools.com/python/), and the [tutorial from the textbook](http://www.cse.msu.edu/~ptan/dmbook/tutorials/tutorial1/tutorial1.html)
 - Skip this step if you already know how to code in Python.
 - If you are seeking for more practices, [https://www.w3resource.com/python-exercises/](https://www.w3resource.com/python-exercises/) has plenty of exercises.

### 1. Install Python on your local machine.

 - Install [conda](https://docs.conda.io/en/latest/miniconda.html) with Python 3.8+.
 
### 2. Install required packages.
 - Open terminal.
 ```
 conda install scikit-learn
 conda install pandas
 ```
 
### 3. (Optional) Install an IDE.
 - [Pycharm](https://www.jetbrains.com/pycharm/) community version.
 
## Jupyter Notebook Basics

#### 0. Learn the basics of Jupyter Notebook on [TutorialsPoint](https://www.tutorialspoint.com/jupyter/jupyter_notebook_introduction.htm) as well as check the tutorial by George Seif on this [article] ( https://towardsdatascience.com/a-beginners-tutorial-to-jupyter-notebooks-1b2f8705888a)

#### 1. Also, check the youtube tutorials like: 

##### 1.1 Python for beginners: https://www.youtube.com/watch?v=k5A92NDg8RQ

##### 1.2 Python Machine Learning Tutorial: https://www.youtube.com/watch?v=7eh4d6sabA0 

>**_NOTE:_** : This tutorial is if you want to learn how to create and work with a basic ML pipeline. If you want, you could watch. It is not really necessary! 
  
## Github Basics

### 0. Install [Git](https://git-scm.com/downloads) and create your [Github](https://github.com/) account.
 - Skip this step if you already have one.

### 1. Create a new PRIVATE repository called **FDSA-DSCI-633-Fall2021** under your Github account.
 - (1) Click on the **new** button:
 ![](https://github.com/YashBangera7/FDSA-DSCI-633-Fall2021/blob/main/images/image2.PNG)
 
 - (2) Initiate the new private repo:
 ![](https://github.com/YashBangera7/FDSA-DSCI-633-Fall2021/blob/main/images/image3.PNG)

 - (3) Click on Settings:
 ![](https://github.com/YashBangera7/FDSA-DSCI-633-Fall2021/blob/main/images/image4.PNG)

 - (4) Click on Manage Access:
 ![](https://github.com/YashBangera7/FDSA-DSCI-633-Fall2021/blob/main/images/image5.PNG)
 
 - (5) Invite the instructor and the TA as collaborators (GitHub ID: **uberize, YashBangera7**):
 ![](https://github.com/YashBangera7/FDSA-DSCI-633-Fall2021/blob/main/images/image6.PNG)

### 2. Clone the **DSCI-633** repo to your local machine.
 ![](https://github.com/YashBangera7/FDSA-DSCI-633-Fall2021/blob/main/images/image7.PNG)
 ```
 git clone THE-COPIED-URL
 ```

### 3. Save username and token in git.
 - Create your personal access token on [this page](https://github.com/settings/tokens)
 - Copy the generated token.
 - In terminal:
 ```
 git config --global credential.helper manager
 ```
 - When running this command, the first time you pull or push from the remote repository, you'll get asked about the username and your token (NOT Password!). Afterwards, for consequent communications with the remote repository you don't have to provide the username and password.

### 4. Working with a github repo.
 - (1) Go to the local directory of the **FDSA-DSCI-633-Fall2021** repo.
 - (2) Pull from Github so that the content on your local machine is updated with the remote server of Github:
 ```
 FDSA-DSCI-633-Fall2021> git pull
 ```
 - (3) Work on your local machine (add/remove/edit files under FDSA-DSCI-633-Fall2021/).
 - (4) Commit to the remote server of Github (upload local changes).
 ```
 FDSA-DSCI-633-Fall2021> git add .
 FDSA-DSCI-633-Fall2021> git commit -m "YOUR COMMIT MESSAGE"
 FDSA-DSCI-633-Fall2021> git push
 ```
 
 ### 5. Add your information to [Google sheet](https://docs.google.com/spreadsheets/d/1q7tw0On2aCCHZEuJ8KAYOgad2yPxS8U1aWb81jsrU0k/edit?usp=sharing)
 - Add your github repo url (along with your RIT identifier and Github ID) to the Google sheet.
 - Make a self-evaluation on your current knowledge/expertise in coding, Python, and machine learning. This information will ONLY be used to decide your study group.
