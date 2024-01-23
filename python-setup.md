# A brief tutorial on how to setup a python installation

This guide is not supposed to be a complete and detailed tutorial on how to setup python, but might be enough for a complete beginner to start running his first program.

## Initial setup

- **Download** python from the official [site](https://www.python.org/)
- **Install** it on your machine either through the package manager or through terminal (Linux) or from the installer (Windows)

## Working environment

It's reccomended to setup a virtual environment where to install your packages, so you can keep running different package versions in different projects. To do so manually,
run:

- **Linux**  `$ python -m venv /path/to/new/virtual/env` followed by `$ source /path/to/new/virtual/env/bin/activate`
- **Windows**   `$ py -m venv c:\path\to\myenv` follewd by `$ c:\path\to\myenv\Scripts\activate`

If you're using a modern dedicated IDE (e.g. PyCharm), all of that is automatically done when you create a new project directory.
It's also worth to note packages are often quite heavy, so avoid creating too many different directories if there's not a reason to do so.

For more info about venv's, check the [python official site](https://docs.python.org/3/library/venv.html).


## Installing libraries

In order to install the required packages in your venv you have to use pip, the official package installer, either through your IDE settings (check the docs of your preferred IDE)
or in terminal by running:

- **Linux**  `$ python3 -m pip install "libname"`
- **Windows**  `$ py -m pip install "libname"`

## Running a program

Now you should be ready to run a python script, you should be able to do so easily in your IDE console, or alternatively by using:

`$ python3 "my_script.py"`
