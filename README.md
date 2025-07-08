# Matplotlib and pyplot

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

Each question is worth two points: 

* Data plotted as described by the question (1 pt)
* Plot contains required elements (title, axis labels, axis titles, legend if required)

### Activate Virtual Environment Before Installing Packages

* create a local virtual environment in your repo (e.g. in the .venv folder) and activate it (this option offers more practice with environments), OR
* create a virtual environment for the course somewhere on your machine and reuse that (this option saves space).
* install packages (e.g. requests, spacy, spacytextblob)

#### python -m pip install matplotlib

1. Task 1. Get Started - Copy the base repository
2. Task 2. Open Notebook and Complete Tasks
   1. Create a bar plot (or a horizontal bar plot) that shows the frequency distribution of characters in the string
   2. Generate a sequence of at least 5 random numbers (integers are fine), and visualize the data using both `scatter` and `plot` on different axes
   3. Change the syle and color of both the scatter and the plot from question 2
   4. Given the data sets, plot or scatter both on the same set of axes
3. Task 3. Export to HTML and Finalize Repo
    import os
    os.system('jupyter nbconvert --to html python-ds.ipynb')
