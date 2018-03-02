---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
exclude: true
---
### **Latest Announcements**
- On 09.03.2018 we will start at our usual time.
- You have a homework (HOMEWORK01) due **11.03.2018 23:59:59**

### **HOMEWORK**
Due Date: **11.03.2018 23:59:59**

Find the details of the homework and submission guideline in the following link:

- [HOMEWORK 01](/homeworks/HOMEWORK01){:target="blank"}

### **CLASS PRESENTATIONS**

 - [WEEK 2](https://docs.google.com/presentation/d/1XHhVwM71nb9gcPWDWLu55vNbjqsRi6tqHLK2eKbo4hw/edit?usp=sharing){:target="blank"}
 - [WEEK 1](https://docs.google.com/presentation/d/1d6ayhonXY4yacCzmG5Agm9LwzB_zbgRhjCfDPBQF5yQ/edit?usp=sharing){:target="blank"}

### **CLASSWORKS (QUESTIONS SOLVED ON THE BOARD)**
 - [Date: 02.03.2018](https://drive.google.com/open?id=193KpiWfQ2tXtS9bOAM1cFE-h6nWnRMGZ){:target="blank"}

### **About the Course**

- [Attendance and Grades](https://docs.google.com/spreadsheets/d/e/2PACX-1vTzWSFYwl88Ho8b1g-DZg9tzSbNYe97Qg-F9WxgcuMI0K-zNNv4BrYGlDIkyiK8NLa-uTZ3_bUKV2qv/pubhtml){:target="blank"}
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
