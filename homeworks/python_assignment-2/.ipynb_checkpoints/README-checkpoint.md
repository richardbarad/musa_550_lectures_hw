[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/HDaP31zx)
# Assignment #2 

## Due Dates

> **Section 401:** Monday, October 9 by end of day (11:59 PM)
> 
> **Section 402:** Thursday, September 28 by end of day (11:59 PM)


## Recommended Readings

- Matplotlib:
  - [Guide to getting started with matplotlib](https://pbpython.com/effective-matplotlib.html)
  - [Plotting & visualization chapter of Python for Data Analysis](https://wesmckinney.com/book/plotting-and-visualization)
  - [Matplotlib chapter of the Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/04.00-introduction-to-matplotlib.html)
- Altair:
  - [Introduction to Statistical Visualization](https://altair-viz.github.io/getting_started/starting.html)
  - [Exploring Seattle Weather: A Case Study](https://altair-viz.github.io/case_studies/exploring-weather.html)
- Data viz design: [Introductory slides of London's design guidelines](https://data.london.gov.uk/blog/city-intelligence-data-design-guidelines/)

## Reference materials

- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [altair](https://altair-viz.github.io/)

## Exploratory Data Visualization

In this part, you'll use matplotlib, seaborn, and altair to explore a
dataset of your choosing and generate some charts in a Jupyter notebook.

### Part 1: Select a dataset

For this assignment, you can choose your own dataset to explore. I recommend selecting a dataset from [OpenDataPhilly](https://www.opendataphilly.org/). You are welcome to to use a dataset from elsewhere, **but please email your instructor and let them know what you want to analyze.**

Datasets with timestamped entries will be particularly good for analysis, but there are many
interesting datasets to consider. They include:

- [311 Requests](https://www.opendataphilly.org/dataset/311-service-and-information-requests)
- [Voter turnout](https://www.opendataphilly.org/dataset/voter-turnout)
- [Complaints against police](https://www.opendataphilly.org/dataset/police-complaints)
- [Parking violations](https://www.opendataphilly.org/dataset/parking-violations)
- [Shooting victims](https://www.opendataphilly.org/dataset/shooting-victims)
- [L+I Violations](https://www.opendataphilly.org/dataset/licenses-and-inspections-violations)

and many more...

For OpenDataPhilly datasets, data files can be downloaded in the form of CSV files.

### Part 2: Explore and visualize the data

From within a Jupyter notebook, you should explore the
datasets and generate charts visualizing different aspects of the data.

**Requirements:**

- **1 Matplotlib chart** (of any type)
  - You should consider what aspect of the dataset might be best plotted using matplotlib.
  - Include your reasoning for using matplotlib to visualize this specific aspect of the data.
  - You will be graded on the aesthetics of the plot, namely, color choices and clarity.
- **1 seaborn chart** (of any type)
  - Please include the motivation behind your choice for the type of seaborn plot used and why.
- **3 altair plots**
  - **Both** of the following techniques should be used:
    - A transformation (mean, count, binning, etc)
    - Brush selection
- Include a short discussion (a few sentences) of the main conclusion of each chart
  (in a markdown cell below each chart). It does not need to be interesting or insightful,
  but it is good practice to always note the main conclusions so the notebook make sense after time passes.
- **Extra credit:**: 2-chart altair dashboard,
  - This should be **in addition to** the 3 charts above
  - Filtering on one chart should cross-filter the other chart (via `transform_filter()`)

**Note:** You may include geospatial charts to satisfy the above requirements, but
you are not required to.

## Grading Guidelines

See the [grading rubric](./rubric.md) for more details.

**Important:** Your notebooks should be a polished finished product. For example:

- Please remove any extra or unneccesary code.
- Please try to use markdown cells with section headers to mark different sections of the analysis.

## Submission

**Note:** Be sure to read the documentation for assignment [guidelines](https://musa-550-fall-2023.github.io/assignment/overview.html#guidelines) and [submission](https://musa-550-fall-2023.github.io/assignment/overview.html#submission).

We'll be using GitHub for assignment submission again. 
The invitation link depends on your section. For this assignments, the links are:


> **Section 401**: [https://classroom.github.com/a/HDaP31zx](https://classroom.github.com/a/HDaP31zx)
>
> **Section 402**: [https://classroom.github.com/a/coiOv0PU](https://classroom.github.com/a/coiOv0PU)

Your assignment notebook should be added to this GitHub repository before the deadline.

**Note:** File sizes are limited to 25 MB when adding files to a repository via GitHub in a browser. If your
dataset is larger than this, you can try compressing it into a ".zip" to make the file smaller, and then
add it to the repository on GitHub. If you run into problems, please email your instructor for help.
