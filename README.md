# Tutorial Publication-Ready Figures

Plotting data is a fundamental part of research in almost every discipline. It’s also critical for communicating our research and creating engagement with it, especially because people often decide to read a manuscript based on the figures. Python is a powerful plotting tool but, with so many options and settings, it can be time consuming to work out how to make effective and attractive plots. 

This workshop is your cheat sheet for using the Python packages matplotlib and Seaborn to make static plots. The examples focus on plotting numeric and categorical data in x/y space, but many of the methods demonstrated apply to other kinds of plots. The workshop is interactive and uses Jupyter Notebooks. 

We assume some previous experience with Python but you’ll be able to do this workshop if you have imported a module, printed a statement, and made a basic plot. Detailed setup instructions will be provided prior to the workshop, along with a link to the course material. If you’re looking for a way to level-up your data visualizations and increase engagement with your research, then this workshop is for you.

***
# Setup Instructions

*Registrations for the November 2021 live session are now full*

Get set up before the live session:

- If you have your own computer and can install software, then follow the Anaconda Setup instructions below. This is the recommended setup.

- If you are using a shared computer that you can not install software on, then you can interact with this tutorial on-line using Binder. See the bottom of this page for a link and instructions. 

***
## Anaconda Instructions (Recommended)
 
To run this tutorial, you will need an environment that contains all of the required packages. If you are familiar with setting up your own environment, then go ahead with your usual approach. Otherwise, use the following steps.

Download this tutorial from GitHub using the green 'code' button and unzip to somewhere that is easy to find, such as your Documents folder.
 
Download and instal [Anaconda individual edition](https://www.anaconda.com/products/individual) if you don't already have it. When prompted, accept the default installation settings.

In Windows open the anaconda prompt or in macOS open a terminal. Use the prompt/terminal to navigate to where you have saved this tutorial (hint: use _cd \<path_to_the_tutoral\>_ to change directory)
 
In the tutorial folder, you will find an environment.yml file (hint: use _ls_ in MacOS or _dir_ in Windows to list files in your current directory). We will use this file to create an environment that will run the tutorial. Execute the following command in the prompt/terminal to create the environment (hint: do not include the $ sign):
 
    $ conda env create -f environment.yml
 
You will see a lot of text scroll past in the the prompt/terminal and may need to respond y + ENTER at some point. The environment is automatically named figtut (short for figure tutorial). Once it has built, we need to activate the environment by executing:
 
    $ conda activate figtut
 
\(figtut\) should now appear on the far left of your current line in the prompt/terminal window. Now you are inside the right environment, you can execute the following command to launch a browser window containing Juypter notebook:
 
    $ jupyter notebook
 
Now you can open the tutorial notebooks and use them. 

When you are finished with Juypter Notebook, you can close the browser window and go back to the prompt/terminal to kill the process with CTRL + C.
 
When you come back to the tutorial at a later date, you will probably have to activate the figtut environment again before launching Juypter Notebook.
 
**Other useful commands**
 
Print a list of your conda environments
  
    $ conda env list
 
Print a list of what is inside your active environment
  
    $ conda list

To install an additional package into the active environment

    $ pip install <PackageName>

***
## Binder Instructions (Backup)

 Click the Binder icon below and wait for it to load. The first time you do this, Binder can take up to 10 minutes to load. 
 
 When Binder has loaded, it will open the tutorial in Jupyter Lab. You can edit and run the code there. You can also save your work and have it retained during that Binder session. However, once you close your browser, any saved work will be lost. 


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ICWallis/tutorial-publication-ready-figures/main)
 
