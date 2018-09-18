---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Tentative Sylabus
permalink: /exercises/
---
### **Exercises**

It is strongly recommended that you first finish the tutorials. I will be using Python version 2.7 , hence for convenience, you are expected to install Python version 2.7 on your sytem. The walkthrough for the installation is platform specific, you should refer to the official [Python Website](https://www.python.org){:target="blank"}. Once you're sure that you installed the correct python version on your system CD to correspnding directory for MEE404 class you created by using whichever name you want to use. Here I preferred MEE404 for convenience.
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

It is also possible to stop virtual environment with the following command

```sh
deactivate
```

In this class we will need [pillow](https://pillow.readthedocs.io/en/latest/installation.html){:target="blank"} library which should be installed separately. You can use **pip** to install Pillow.

```sh
pip install pillow
```

We will also extensively use matplotlib and numpy. Numpy comes with some installations but to ensure you have both matplotlib and numpy it is convenient to run pip for these libraries as well. 

```sh
pip install matplotlib
pip install matplotlib
```

Jupyter  is another common way to interpret with python scripts easily. You can edit, modify and run python scripts within your browser. Contemporary works, especially on machine learning etc., are mostly displayed in jupyter environment. I strongly recommend you to install and play with this environment. 

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
