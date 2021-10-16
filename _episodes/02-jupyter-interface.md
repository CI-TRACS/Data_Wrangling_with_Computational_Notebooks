---
title: "Jupyter Notebook Interface"
teaching: 15
exercises: 0
questions:
- "How is the jupyter notebook interface setup"
objectives:
- "Describe the basics of the jupyter notebook interface"
- "Demonstrate the various basic cell types notebooks use"
- "Demonstrate how notebooks deal with code blocks and the concept of restarting the kernel"
keypoints:
- "A jupyter notebook is divided into cells that are either code, markdown, or raw"
- "Cells can be \"run\" leading to either the execution of code or formatting of markdown depending on the cell type"
- "Code cells can be rerun, but this should be avoided to prevent obscuring the notebooks workflow"
---

## Notebook Basics

When you load up the binder webpage linked in the previous lesson you should be presented with a site that looks something like the image below.

![Basic Binder Webpage](../fig/E2_1_basic_binder.png)

This site contains a variety of buttons to create various file types. However, for now we are going to click on the "Python 3" box beneath the Notebook label. This button is next to the arrow labeled "Create new Jupyter Notebook".

Once you click on it you will be presented with a new screen which will look something like the image below (note that the image has been cropped to reduce space). Here we have a blank cell ready to be used.

![New Notebook Page](../fig/E2_2_new_notebook.png)

This cell is a code cell that you can type in. For example if you type in some python code like `print("This is a code cell")` and then click the run button you will see the output appear beneath the cell.

### Cell Types

Cells are the base unit in Jupyter notebooks. A notebook is essentially just a collection of cells of different types. In Jupyter notebooks there are three primary types of cells:

- **Code** cells
  - Code cells treat everything typed inside them as code
  - When they are "run" they will run the code they find inside them
- **Markdown** cells
  - Markdown cells treat everything typed inside them as markdown
  - When they are "run" they will format the text inside them based on markdown
- **Raw** cells
  - These cells treat everything inside them as raw text
  - If you "run" these cells nothing will happen

If you double click the jupiter notebook called "02_insert_name" that can be found in the file browser side tab you will be presented with three different cells that each correspond to one cell type. You can select the top cell and then click the run button three times to run all three cells.

> ## Running Cells
>
> You can also run a selected cell by pressing <kbd>Shift</kbd>+<kbd>Return</kbd>
>
{: .callout}

![Notebook Cell Types](../fig/E2_3_cell_types.png)

### Editing Cells

You can edit cells after running them by clicking on the cell like normal text. However, for markdown cells you will need to double click on the cell area in order revert it back into a cell.

Markdown and raw cells can be edited and run repeatedly without much issue. However, when editing code blocks you have to be more careful.

When you run a code cell you are running that piece of code. Even if you delete or edit the code block after running it the changes it made will remain until the Kernel is restarted.

A good way to think about code cell execution in a notebook is that you are essentially copy pasting the code cell into a python console. The image below gives a visual example of this with the notebook cells on the left, and a python code that does the same set of commands on the right.

![Visual Code Cell](../fig/E2_4_running_code.png)

However, if we were to rerun two bottom cells containing the code `a = a + 2` and `print(a)` this would be reflected as a fifth and sixth command executed in the python console. You can see this reflected in the Python console below where the same commands have been issued in the same order.

> ## Rerunning Cells
>
> Rerunning code cells will erase the output of that code cell and update the counter next to the cell with the most recent time the cell was run. 
>
{: .callout}

![Rerunnig Cells](../fig/E2_5_rerunning_code.png)

Rerunning code cells is **not recommended** since it both obscures what the notebook's code cells are doing and can make it very difficult for anyone reading your notebook to accurately rerun your analysis.

### Jupyter Notebook Cheatsheet

The image below is a cheatsheet of some of the buttons not discussed in this episode that might be good to know for the future. Feel free to come back to it if you are confused later on.

![Notebook Cheatsheet](../fig/E2_6_cheatsheet.png)

More information on the jupyter notebook can be found at these sources:

- Source 1
- Source 2
- Source 3
