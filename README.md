# Introduction to LLMs Course Notebooks

Welcome to the **Introduction to LLMs** course repository! 

This repository contains Jupyter notebooks designed to help you learn the basics of Large Language Models through hands-on examples and exercises.

The notebooks are designed to accompany the Introduction to Large Language Models course which can be found here: 

https://learn.365datascience.com/courses/preview/intro-to-llms/

https://www.udemy.com/course/intro-to-large-language-models-llms/

## Installed Packages

These are the installed packages and versions used for this course. All were installed in a conda environment (see below for how I created this). 

python=3.11

```
openai==0.28 
config==0.5.1 
langchain==0.0.297 
pydantic==1.10.9 
tiktoken==0.5.1 
faiss-cpu==1.7.4 
transformers==4.47.1 
torch==2.5.1 
datasets==3.2.0 
evaluate==0.4.3 
accelerate==1.2.1 
ipywidgets==8.1.5 
matplotlib==3.10.0 
seaborn==0.13.2 
clean-text==0.6.0 
scikit-learn==1.6.0 
sentencepiece==0.2.0 
pandas==2.0.0
```

## Updates

The world of AI is constantly evolving with new techniques and models emerging all the time. So, while we do our best to keep everything up to date, sometimes the code in this repo may get updated before the accompanying video lessons. To make sure you're getting the most out of this course, we recommend you always use the latest code here alongside the video lessons, while we work on updating the videos. 

## Conda Environment

Virtual environments are a great way to manage different packages for different projects. Creating a virtual environment for this section of the course allows you to ensure you can use the correct packages to follow along, without affecting any other packages you already have installed. 

```
conda create –name llms_course_env python=3.11
conda activate llms_course_env
pip install openai==0.28 config==0.5.1 langchain==0.0.297 pydantic==1.10.9 tiktoken==0.5.1 faiss-cpu==1.7.4 transformers==4.47.1 torch==2.5.1 datasets==3.2.0 evaluate==0.4.3 accelerate==1.2.1 ipywidgets==8.1.5 matplotlib==3.10.0 seaborn==0.13.2 clean-text==0.6.0 scikit-learn==1.6.0 sentencepiece==0.2.0 pandas==2.0.0
pip install ipykernel jupyterlab notebook
python -m ipykernel install --user --name=llms_course_env
```

Then when in the notebook, remember to check the kernel is set to "llms_course_env". 
