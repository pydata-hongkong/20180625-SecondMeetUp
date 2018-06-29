This directory stores the materials in Dr. Howard Cheung's presentation on _Demonstration to Use Regular Expression, Python and LaTeX Template to Automatically Create Documents_. It contains several files:

* _Author-Index-Demo.ipynb_: _Jupyter_ Notebook showing the Python code. Can be viewed online by clicking at the file or be downloaded to run locally
* _conference\_session\_paper.txt_: text file containing all the conference paper information. Trimmed from the original one to minimize the amount of data put in the repository
* _double\_name.txt_: text file containing the double name information in the _conference\_session\_paper.txt_
* _preamble.tex_: heading files for the author index _LaTeX_ file
* _Presentaiton-v00.pdf_: presentation file shown on the presentation day
* _README.md_: this description

## Running the files locally?

To run the files locally, you'd need _LaTeX_ and _Jupyter_. _Jupyter_ can be installed via installing [Anaconda](https://www.anaconda.com/), and _LaTeX_ can be used by installing [MiKiTeX](https://miktex.org/). Installing both will allow you to run the _Author-Index-Demo.ipynb_ locally if you have both _.txt_ file with it.

## Other methods?

Note that this tutorial is only used to demonstrate one method that you can use to create documents from text data automatically. There are other methods to do so. For example, one-post presentation evaluation suggests to use [neo4j](https://neo4j.com/) wih [Markdown](https://daringfireball.net/projects/markdown/) and [Pandoc](https://pandoc.org/) and the author index can be done in a few lines.

