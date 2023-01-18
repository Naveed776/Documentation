# Research-track-2-Assignment-01

In this repository I used tools to complete. in this Assgnemtn is depend on documentation so i Can work on
- Doxygen
- Jypter
- statistics Analysis of Assignment


# Doxygen
Doxygen is the standard tool for generating documentation from annotated C++ sources, but it also supports other popular programming languages such as C, Objective-C, C#, PHP, Java, Python, IDL (Corba, Microsoft, and
UNO/OpenOffice flavors), Fortran, VHDL.
It can generate an on-line documentation browser (in HTML) and/or an off-line reference manual (in LaTeX) from a set of documented source files. There is also support for generating output in RTF (MS-Word),
PostScript, hyperlinked PDF, compressed HTML, and Unix man pages. The documentation is extracted directly from the sources, which makes it much easier to keep the documentation consistent with the source code.
You can configure doxygen to extract the code structure from undocumented source files. This is very useful to quickly find your way in large source distributions. Doxygen can also visualize the relations between the
various elements by means of include dependency graphs, inheritance diagrams, and collaboration diagrams, which are all generated automaticall. You can also use doxygen for creating normal documentation

## How to Install

- `sudo apt-get install –y doxygen`
- `sudo apt-get install doxygen-gui`

# Jupyter

The Jupyter Notebook is an open source web application that you can use to create and share documents that contain live code, equations, visualizations, and text. Jupyter Notebook is maintained by the people at Project Jupyter. Project Jupyter is a non-profit, open-source project, born out of the IPython Project in 2014 as it evolved to support interactive data science and scientific computing across all programming
languages IPython (short for Interactive Python) was started in 2001 by Fernando Perez as an enhanced
Python interpreter. As well as being a useful interactive interface to Python, IPython also provides
a number of useful syntactic additions to the language. The Jupyter notebook is a browser-based
graphical interface to the IPython shell, and builds on it a rich set of dynamic display capabilities. Jupyter Notebooks are a spin-off project from the IPython project, which used to have an IPython
Notebook project itself

The Jupyter Notebook is not included with Python, so if you want to try it out, you will need to install
Jupyter.

`pip3 install jupyter bqplot pyyaml ipywidgets`
`jupyter nbextension enable --py widgetsnbextension`

Now that you have Jupyter installed, let’s learn how to use it. To get started, all you need to do is open up
your terminal application and go to a folder of your choice. I recommend using something like your
Desktop folder to start out with and create a subfolder there called Notebooks or something else that is
easy to remember. Then run:
`jupyter notebook --allow-root` (the --allow-root option is only necessary if you are using the Docker Image.
Also, in the docker you will probably need to update firefox with apt-get install firefox)
