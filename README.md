# Jupyter, Python and Pandas

[Jupyter](http://jupyter.org/) is a browser-based development environment geared toward creating shareable documents called [notebooks](http://jupyter.org/assets/jupyterpreview.png) which can be a mix of code, output, presentation and charts. The Jupyter name is an acronym for the programming languages Julia, Python and R, which are used heavily in scientific and statistical computing.

A notebook is talks to a kernel on the server running a programming language over a web socket. Code entered into the notebook is sent to the kernel, where it is executed and the result is returned to the browser. 

Presentation can be a mix of markdown, html, and LaTeX, for mathematical formulas.

Charts can be created from code which can output pngs, svg, or javascript, for interactive charts.

In addition to code, users can open a terminal in the browser that runs a command line shell.

The Python kernel in a notebook supports additional functionality via magic commands, such as running command line statements, outputting html, Javascript, css, or svg, and executing R code and sharing variables between Python and R. You can also execute Perl and Ruby, if the server has them installed.

We use [Python](https://www.python.org/), which has a rich set of scientific libraries. [Pandas](http://pandas.pydata.org/) is a very popular library that uses R & Excel like functionality for cleaning, wrangling, analysing and charting data. It is built on top of the Numpy and Matplotlib libraries.

You can try out Jupyter here: [http://try.jupyter.org/](http://try.jupyter.org/)

This repo has the slides (.pdf), a notebook (.ipynb) where we found an "alien" outlier in the data, and a dataset (.csv) of nba players.

You may wish to use Anaconda to install the tools needed
[https://www.continuum.io/downloads](https://www.continuum.io/downloads)
