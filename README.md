# Purpose

This repo serves as a continuation of the Light weight additive spanner project that was started during COSC480A in Fall of 2022. This can be found [here](https://github.com/retdude/SpannersDataVis).

The initial import is simply the final project that was submitted. Thus, this requires some polishing before the continuation of the project for an independent study course, COSC482, advised by Professor Reyan Ahmed. 

As of now (2/1/23), the goal of the continued research is to expand the work with LW additive spanners and to expand the scope of its usability to multi-level data sets. The updated goals and results will be updated periodically to reflect the progress of the independent study project. 

-------------------------------------------
# Dev Set-up

In order to use and work on the spanner.py file, there are a few package dependencies that must be installed to your pyenv


1. First select the pyenv you want to use
    - To check your pyenv type `pyenv versions`, the version with the `*` is your current pyenv

2. Then pip install the following packages:
    - networkx
    - numpy
    - scipy
    - matplotlib

For example, type in your console `pip install networkx`
You will be able to check the status of these packages by typing `pip list` which will display the packages installed on your pyenv

-------------------------------------------
# Repository Navigation

- `Pseudo.txt` includes notes on the pseudo code used as well as the algorithm provided. This is mostly an artifact from the prior project.

- `LWSPaper.pdf` is the research paper describing LWA Spanners. It details the steps and the algorithm to create the spanner, as well as a proof for testing.

- `AdditiveSpanner.html` is a simple visualization of the start and end png files.

- `start.png` & `end.png` are graph visualizations produced by the main spanning file.

- `spanner.py` is the main file, containing the spanner algorithm
