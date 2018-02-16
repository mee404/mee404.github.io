---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
exclude: true
---
### **Latest Announcements**
- Today (on February 16th, 2018) we met for the first time with the majority of the students taking this course.
- We did not cover a subject but we talked about the basic usages of Python and the methods about how one can interact with Python. There are three basic methods:
  - Bu simply using python terminal
  - Writing a python script and running it with python command
  - Jupyter Notebook
- See the homework given below. It will not be graded but you better perform the given tasks in this homework. Make sure that you finish homework before coming to next lecture
- Next week we will start the course subjects.
- I will start taking attendance. It is recommended that you don't miss any class.

### **HOMEWORK**

Your first homework will not be graded but it is very important for you to perform the given tasks below. Once you finish these tasks you will be ready to implement any task given as an exercise or as a homework.

- Go and sign up for a [GitHub](https://github.com){:target="blank"} account.
- You can use [Atom](https://atom.io){:target="blank"} for code editing. Atom is highly integrated with GitHub.
- Clone the [course repo](https://github.com/mee404/mee404.github.io){:target="blank"}  to your computer. If you regularly update the repo, you will be up-to-date and will have every necessary material and information about the course.
- Follow the following tutorials. Not just read but also implement the example python codes.
- Read the 'Exercises' section below. Perform the following given tasks:
  - Install Python version 2.7.x to your system
  - Make sure that you also have **virtualenv** and **pip** on your system.
  - Create a directory for the works related with this course.
  - Create virtual environment
  - By using pip install the following libraries:
    - Pillow
    - matplotlib
    - jupyter
  - Run jupyter in the course folder you cloned from github.
  - Read and run **Exercise 0** and **Exercise 1**

### **About the Course**
- [Tentative Syllabus](syllabus/){:target="blank"}

### **Tutorials**
- [Pillow Tutorial](/tutorials/pillow-tutorial/){:target="blank"}
- [Python Numpy Tutorial](/tutorials/python-numpy-tutorial/){:target="blank"}
- [iPython Tutorial](/tutorials/ipython-tutorial/){:target="blank"}

### **Exercises**

It is strongly recommended that you first finish the above tutorials. For convenience you are expected to install Python version 2.7.x on your sytem. Since the walkthrough for the installation is platform specific, you should refer to the official [Python Website](https://www.python.org){:target="blank"}. Once you're sure that you installed the correct python version on your system CD to correspnding directory for MEE404 class you created by using whichever name you want to use. Here I preferred MEE404 for convenience.
```sh
cd MEE404
```
It is very common to use virtual environments for specific tasks. It helps you to create and work on a virtual environment specifically tailored for one specific task. It includes a python instance and keeps the core installation isolated. This makes it possible to install and try different python packages without compromising the core installation. Running the following command will create a virtual environment hosted in **venv** directory. It is a common practice to name the directory as **venv**.

```sh
virtualenv --system-site-packages venv
```
Once you create virtual instance you can work on it by simply running the following command in the terminal.
```sh
source venv/bin/activate
```
In this class we will need [pillow](https://pillow.readthedocs.io/en/latest/installation.html){:target="blank"} library which should be installed separately. You can use **pip** to install Pillow.
```sh
pip install pillow
```
We will also extensively use matplotlib. If you dont have it installed on your system, you can also install it likewise.
```sh
pip install matplotlib
```
The exercises will be in iPython Notebook format. Hence you will also need Jupyter Notebook installation. It is also straightforward to install Jupyter Notebook.
```sh
pip install jupyter
```
See [iPython Tutorial](/tutorials/ipython-tutorial/){:target="blank"} for further details. The exercises will be in the exercises folder of [this](https://github.com/mee404/mee404.github.io){:target="blank"}  GitHub Repository. The repo will be updated regularly. To follow the updates visit this site occasionally. Assuming that you download the repo, just cd to the exercises directory and there run the following command.
```sh
jupyter notebook
```
Once you run the above command it will start a local server where you can reach, view and run ipynb files easily. It is strongly recommended that you get ipython jupyter up and running, but alternatively you can reach the exercises as static pages from the following links as well.

- [EXERCISE 0](/exercises/exercise00){:target="blank"}
- [EXERCISE 1](/exercises/exercise01){:target="blank"}
