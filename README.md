# Introduction to LLMs Course Notebooks

Welcome to the **Introduction to LLMs** course repository! 

This repository contains Jupyter notebooks designed to help you learn the basics of Large Language Models through hands-on examples and exercises.

The notebooks are designed to accompany the Introduction to Large Language Models course which can be found here: 
https://learn.365datascience.com/courses/preview/intro-to-llms/
https://www.udemy.com/course/intro-to-large-language-models-llms/

## Installed Packages

These are the installed packages and versions used for this course. All were installed on a virtual environment (please see the section below to learn more about virtual environments and set up your own) using pip.

```
openai==0.28
config==0.5.1
langchain==0.0.297
pydantic==1.10.9
tiktoken==0.5.1
faiss-cpu==1.7.4
transformers==4.47.1
torch==2.5.1+cu118
datasets==3.2.0
evaluate==0.4.3
accelerate==1.2.1
```

## Updates

The world of data science and AI is constantly evolving — new techniques, models, and best practices are emerging all the time. So, while we do our best to keep everything up to date, sometimes the code in this repo may get updated before the accompanying video lessons. To make sure you're getting the most out of this course, we recommend you always use the latest code alongside the video lessons while we work on updating those. 

## Setting up a Virtual Environment

Virtual environments are a great way to manage different packages for different projects. Creating a virtual environment for this section of the course allows you to ensure you can use the correct packages to follow along, without affecting any other packages you already have installed. 

You'll also want to set up a Jupyter kernel in your virtual environment so you can run the Jupyter notebooks. 

Doing this is easy, just follow along below. 

Install virtualenv

```
pip install virtualenv
```

Create your virtual environment in a directory of your choice

```
virtualenv yourenvname # replace yourenvname with any name you like
``` 

Activate the virtual environment 

```
# on mac or linux
source myenv/bin/activate

# on windows
myenv\Scripts\activate
```

Install jupyter

```
pip install jupyter
pip install ipython
pip install ipykernel
```

```
ipython kernel install --user --name=myenv
python -m ipykernel install --user --name=myenv
```

Install the bash kernel

```
pip install bash_kernel
python -m bash_kernel.install
```

Start your jupyter notebook

```
jupyter notebook
```

Then when in the notebook, remember to change the kernel to "myenv". 

Make sure to then install any packages within this virtual environment. 


