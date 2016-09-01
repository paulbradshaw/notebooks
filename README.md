# Notebooks in Python, R and JavaScript

Notebooks are a way to share code in a way that's much more accessible than code alone. There are ways to create notebooks in R, Python and JavaScript. This repo contains documentation and examples of all of these.

## Python notebooks

A notebook explaining the process is [viewable publicly here](https://nbviewer.jupyter.org/github/paulbradshaw/pynotebooks/blob/master/mynotebook.ipynb)

## R notebooks

You can [create notebooks within RStudio](http://rmarkdown.rstudio.com/r_notebooks.html). Notebooks can then be exported as PDF documents, HTML files or Word documents.

R notebooks use a particular form of markdown called R Markdown - the files created use the extension `.Rmd`.

To create a notebook in RStudio, select **File > New file > R Markdown...**. The first time you do this, RStudio will install a bunch of packages (specifically `knittr` and `rmarkdown`) to allow you to create notebooks.

When you create a notebook it will be generated with some template code that explains how they work. This includes **chunks** of working code. Each chunk of code starts and ends with ```. The language of the code is also specified, like so: 

````{r}`

Each chunk of code is then coloured grey. In the upper right corner of that grey chunk you should see a settings button, a downward arrow and a 'play' button. The settings button allows you to specify whether each piece of code runs or not, is visible or not, and whether the output is shown or not. The other two buttons allow you to run just that piece of code or all previous chunks.

Notably, you can also run other languages within an R notebook, as long as they are installed on your computer. For example to run Python just use ````{python}` at the start of the chunk of code.

## JavaScript notebooks

JavaScript is less well supported than R or Python when it comes to notebooks. [Kajero](http://www.joelotter.com/kajero/) appears to be one attempt to replicate the functionality of R and Python notebooks, however, allowing you to add commentary and formatting in markdown alongside code which runs within the page.

Like R notebooks, you can specify whether each piece of code runs or not, is visible or not, and whether the output is shown or not. Users can also run or re-run the code themselves within the page.
