---
title: "Introduction"
teaching: 10
exercises: 0
questions:
- "Why are jupyter notebooks useful for cleaning and wrangling data?"
objectives:
- "Describe how jupyter notebooks provide a method of documenting the steps invovlved in cleaning and wrangling data"
keypoints:
- "Notebooks help connect the code for cleaning and wrangling data to the documentation explaining what is being done and why."
---

### Why should I care about this?

If you have ever worked with a set of data in an Excel spreadsheet, Google sheet or CSV file you have probably had to modify that data in some manner to use it. You probably have needed to add or remove columns and rows or do some summations or different arithmetic functions to the data. Excel and G-sheets work just fine for simple data. But what do you do when you have thousands and millions of rows of data? Or what if you have a bunch of the same type of dataset and your want to apply the same steps to each dataset or repeat this in the future? Manually doing this work doesn't scale nor is what you did reproducible or easily shareable with others.

Jupyter notebooks provide a solution to this problem, allowing you to scale, automate, document, and reproduce parts of or your entire analysis. They also provide a method by which you can test newer sections of your analysis as you move from having some initial data to an analysis product.

Here you will learn the basics of utilizing jupyter notebooks by using Python and a library called Pandas ([Link to Pandas Website](https://pandas.pydata.org/)). The Pandas library helps provide various bells and whistles for both cleaning and analyzing your data. However, since it is built on top of Python a basic understanding of the Python ([Link to Python Website](https://www.python.org/)) programming language is required. Through these tools you will learn how to analyze a raw dataset by cleaning it up and formatting it so that it can be used for further analysis or other workflows.

### What this lesson will **not** teach you

- How to write basic python code
- How to set up a notebook environment
- How to run other programming languages e.g. R in jupyter notebooks

> ## Notebook Programming Languages
>
> Jupyter notebooks can contain various programming languages with R or Julia being possibilities.
>
{: .callout}

### Lesson Structure

The structure for this lesson will require participants to run a jupyter notebook. In order to reduce the time required to get Jupyter notebooks setup and running we will be utilizing Binder ([Link to Binder Website](https://mybinder.org/)). Binder allows us to run a jupyter notebook using a predefined environment and github repository right from our browser. For this lesson we have already setup a binder notebook that links to the github repository for this lesson. There will also be link at the top of each episode to the Binder website for this lesson.

[Link to Binder notebook for this Lesson](https://github.com/CI-TRACS/Data_Wrangling_with_Computational_Notebooks)

{% include links.md %}
