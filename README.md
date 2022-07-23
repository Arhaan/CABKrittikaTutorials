# Tutorials
Set of Jupyter Notebooks, along with datafiles, to get started with Scientific Computing in Astronomy  

***

## Jupyter Setup
While Jupyter runs code in many programming languages, Python is a requirement (Python 3.3 or greater, or Python 2.7) for installing the classic Jupyter Notebook.  

<details>
  <summary>Think you might have installed all this before?</summary>
  
  You can run `jupyter notebook` in your terminal (or command prompt on Windows). If this opens a browser window then you probably have the required software. In the browser window, try making a new ipython notebook and in there add the following code:
```python
  import numpy as np
  import pandas as pd
  import matplotlib
```
and see if it runs. If it does then you are good to go for these tutorials. You might still want to do a conda installation if you are not very sure about how you installed the packages, because in the projects we might need to install a few more packages (by packages we mean numpy, pandas etc.).
</details>

<details>
<summary>Windows</summary>
  
Follow the youtube video: [Installing MiniConda on Windows](https://www.youtube.com/watch?v=-H_onyfW9VE)

The video mentions this, but repeating since this is very important, remember to check the "Add MiniConda3 to my PATH environment variable" box (if some warning is shown regarding this, ignore it).  

Open command prompt (Press Windows button and type ‘cmd’) (opening powershell is also fine)

Type `conda install jupyter numpy scipy matplotlib pandas` into the window and hit enter.

This should install some more required packages, type `y` whenever the terminal tells you to. 

At this point you have installed everything that you need.

Enter the following command to start a notebook, and you can start playing around.
```bash  
jupyter notebook  
```  
</details>

<details>
<summary>MacOS</summary>
  
Our first step is to download the installer

Use the following links depending on your mac

- M1 : [Miniconda3 macOS Apple M1 64-bit pkg](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.pkg)
- Intel: [Miniconda3 macOS Intel x86 64-bit pkg](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.pkg)

The download of the installer should be quick, it’s < 100 mb in size

Once the download finishes, click on the installer to open it. Keep following the onscreen instructions to download miniconda.

Once the installation is finished, open a terminal (if you already had one open, close it and reopen the terminal)

You might see the word `(base)` written on the left or the right end of your line, that is fine.

Type `conda install jupyter numpy scipy matplotlib pandas` into the terminal and hit enter.

This should install some more required packages, type `y` whenever the terminal tells you to.

Celebrate, since now you can start your journey of doing astronomy with python.

In the terminal type `jupyter notebook` and that should start a jupyter notebook, a tool that you’ll learn to live in the coming few days.
</details>
  
<details>
<summary>Linux distribution (includes Ubuntu)</summary>
  
#### Installing Jupyter - Using Conda or Miniconda
Install Anaconda (it has most of the packages we need) from [here.](https://docs.anaconda.com/anaconda/install/linux/ "Installing Anaconda on Linux") (Read the instructions carefully)  
Open terminal (Press CTRL + ALT + T)  
Enter the following command to run  
```bash  
jupyter notebook  
```  

#### Installing Jupyter - Using python-pip (Try this only if you are comfortable with terminal)
Python is usually pre-installed in Linux distribution.  
If you are using Ubuntu 16.04 then the pre-installed python versions are 2.7.12 and 3.5.2.  
To check your python version, type 'python3' in terminal. If it doesn't work, 'python'.  
1. Confirm that your python version is 3.6+.  
If not, install python from https://www.python.org/ftp/python/3.8.2/Python-3.8.2.tar.xz  
or use the following command in terminal  
```bash  
sudo apt install python3.8;  
```  
2. Install pip using  
```bash  
sudo apt install python3-pip;  
```  
3. Install jupyter and other important packages using  
```bash  
pip3 install bs4 requests jupyter scipy astropy matplotlib;  
```  
4. Enter the following command to run notebook  
```bash  
jupyter notebook;  
```  
</details>
***

## [How to use Jupyter notebooks](./How%20to%20use%20Jupyter%20Notebooks#using-jupyter-notebooks )

1. ### [Opening the Notebooks](./How%20to%20use%20Jupyter%20Notebooks#opening-the-notebook )
2. ### [Jupyter Notebook Dashboard](./How%20to%20use%20Jupyter%20Notebooks#jupyter-notebook-dashboard )
3. ### [Creating a new notebook document](./How%20to%20use%20Jupyter%20Notebooks#creating-a-new-notebook-document )
4. ### [Overview of the Notebook UI](./How%20to%20use%20Jupyter%20Notebooks#overview-of-the-notebook-ui )
5. ### [Cell types](./How%20to%20use%20Jupyter%20Notebooks#cell-types )
6. ### [Modal Editor](./How%20to%20use%20Jupyter%20Notebooks#modal-editor )
    1. #### [Edit Mode](./How%20to%20use%20Jupyter%20Notebooks#edit-mode )
    2. #### [Command Mode](./How%20to%20use%20Jupyter%20Notebooks#command-mode )
    3. #### [Running Code](./How%20to%20use%20Jupyter%20Notebooks#running-code )
    4. #### [Keyboard Navigation](./How%20to%20use%20Jupyter%20Notebooks#keyboard-navigation )
    5. #### [Mouse Navigation](./How%20to%20use%20Jupyter%20Notebooks#mouse-navigation )
    6. #### [Cheat Sheet](./How%20to%20use%20Jupyter%20Notebooks#cheat-sheet-for-menu-bar-and-tool-bar )

***

## [Tutorial 1 : Basics of Python](./Tutorial_01)

* Basic syntax, and syntax for loops, conditional statements, and opening simple files, (lists, tuples and dictionaries)
* Parse a file and make a list containing the number of moons for each planet.

***

## [Tutorial 2 : Introduction to NumPy](./Tutorial_02)

* Numpy arrays, indexing, slicing.
* Parse file as above using numpy (np.where, for example).
* Beehive Cluster.

***

## [Tutorial 3 : Functions in Python](./Tutorial_03)

* Defining functions.
* Hubble Law, Number density of galaxies.

***

## [Tutorial 4 : Introduction to Matplotlib (Matplotlib I)](./Tutorial_04)

* Simple Plotting. Labels, colors, title, grid
* GW astronomy

***
