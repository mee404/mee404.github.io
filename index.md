---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
exclude: true
---
### About the Course
- [Tentative Syllabus](syllabus/){:target="blank"}

### Tutorials
- [Pillow Tutorial](/tutorials/pillow-tutorial/){:target="blank"}
- [Python Numpy Tutorial](/tutorials/python-numpy-tutorial/){:target="blank"}
- [iPython Tutorial](/tutorials/ipython-tutorial/){:target="blank"}

###  Exercises

It is strongly recommended that you first finish the above tutorials. For convenience you are expected to install Python version 2.7.x on your sytem. Since the walkthrough for the installation is platform specific, you should refer to the official [Python Website](https://www.python.org){:target="blank"}. Once you're sure that you installed the correct python version on your system CD to correspnding directory for MEE404 class you created by using whichever name you want to use. Here I preferred MEE404 for convenience.
```sh
cd MEE404
```
It is very common to use virtual environments for specific tasks. It helps you to create and work on a virtual environment specifically tailored for one specific task. It includes a python instance and keeps the core installation isolated. This makes it possible to install and try different python packages without compromising the core installation. Running the following command will create a virtual environment hosted in **venv** directory. It is a common practice to name the directory as **venv**.

```sh
virtualenv --system-site-packages venv
```


- [Deneme](/exercises/knn.ipynb)
