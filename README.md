# Week-1

ELE361L Course Week-1 Repo

# Welcome to ELE361L & github :octocat:

In this course we will be using Github Classroom to manage course files & assignments. So it is important you feel familiar to using it. Look for any resource around web to learn some common Github terms like repository, commit, push, branch, markdown, etc. You can begin from having a look at Github's documentation. 

## 📚  Resources 

* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)

# Your First Task (Week-1 Task)

Your first task is quite easy. **Create** a new markdown file named "**Week-1.md**". Then **edit** this file so that 
1. it has **H1 heading** titled "**Week-1 Lab Assignment**", 
2. it has this sentence "I have read and understood information on __ELE361L__ web-site" where ELE361L is a hyperlink to ele361l.github.io, and finally  
3. it contains your PC's **system properties** like **processor info**, **RAM**, **operating system version**. You can use system properties if you are on a Windows machine to obtain tihs info. Here are my settings:
```
Processor	Intel(R) Core(TM) i3-1005G1 CPU @ 1.20GHz   1.19 GHz
Installed RAM	8.00 GB (7.80 GB usable)
Edition	Windows 10 Education
Version	21H2
```

Complete your task accordingly using 
* **Github interface** or 
* cloning the repo to your local PC first then commit your changes and lastly push it if you know how to use **Git**.

# Your Second Task (Week-2 PreLab Task)
This task will install all necessary components, those we will be using throughout the course into your computer. 

## Installation
First, go to the GitHub page that contains your assignments. **Download** the zip file or **clone** the repo into your system. After that extract it if necessary, then change into the folder.  

We will be using **conda** to install tools necessary for the rest of the course. I prefer installing **miniconda** which is faster and it includes less packages. If you have conda (miniconda or anaconda) already installed you may skip conda installation section, jump into create an environment. 

Installation depends on the operating system you use. So, follow one of the following sections depending on your system. Installation steps for Linux and Mac users are nearly the same. 

### Windows
Install miniforge for Windows from this [address](https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-Windows-x86_64.exe). This will install base environment with Python 3.9. For Windows, double click on the downloaded installer executable and follow the prompts. By default, this will install miniforge to your user directory at C:\Users\USERNAME\miniforge3 (if you choose install only for me, **preferred**) or C:\ProgramData\miniforge3 (in case you choose install for all users) and add a "Miniforge Prompt" entry to your start menu. Running the "Miniforge Prompt" should bring up a console window where your base conda environment is activated and you can use the conda command. 

So, first start a **miniforge prompt**, this will bring up a console with (base) at the beginning. Create an environment using command below. This will install lots of packets in verbose mode. So you will see lots of messages in your terminal. It will take a few minutes to finish, depending on your speed and your PC configuration (3-4 minutes in my case). 

    conda config --append channels conda-forge
    conda create --name ELE361L --file requirements.txt

### Linux and MacOS
Run `./install.sh`. This will download and install miniforge, create an environment, then install all necessary packages for you. Mac users should install **Homebrew** to use wget. wget can be installed with `homebrew install wget`. 

# Good Luck!
Need help, feel free to reach me at ytregitim@gmail.com. 

Wish you good luck and a good semester!
