# Guided Lab 386.6.2 – Creating Bar Charts with Matplotlib

## Overview

This lab introduces bar charts in Matplotlib for visualizing and comparing categorical data. It covers creating vertical, horizontal, stacked, and grouped bar charts, along with customizing colors, labels, legends, titles, and bar widths. The lab also demonstrates how to create bar charts directly from Pandas DataFrames.

## Objectives

* Create vertical and horizontal bar charts
* Build stacked and grouped bar charts
* Customize bar colors, labels, titles, and legends
* Adjust bar width and positioning
* Create bar charts using Pandas and Matplotlib

## Technologies Used

* Python 3
* Matplotlib
* Pandas
* NumPy
* Google Colab / Jupyter Notebook

## Methods & Concepts

* `plt.bar()` – Create vertical bar charts
* `plt.barh()` – Create horizontal bar charts
* `bottom=` – Stack multiple bar categories
* `width=` / `height=` – Adjust bar size
* `label=` – Assign legend labels
* `plt.legend()` – Display chart legends
* `plt.xticks()` – Rotate and customize axis labels
* `plt.figure()` – Set figure size
* `plt.tight_layout()` – Prevent overlapping chart elements
* `pd.DataFrame()` – Create charts from Pandas data

## Key Points

* Bar charts are ideal for comparing categorical data.
* Horizontal bar charts improve readability when category names are long.
* Stacked bar charts show how multiple categories contribute to a total.
* Grouped bar charts allow side-by-side comparison of multiple datasets.
* The `bottom` parameter stacks bars, while x-coordinate offsets (`x ± width/2`) position grouped bars.
* Pandas integrates seamlessly with Matplotlib for creating visualizations from DataFrames.

## Topics Covered

* Vertical bar charts
* Horizontal bar charts
* Stacked bar charts
* Grouped bar charts
* Bar customization
* Legends and labels
* Bar positioning
* Pandas visualization
* Course enrollment comparisons

## Dataset

The lab uses sample datasets including:

* Student enrollments by course
* Student Group 1 vs. Student Group 2 comparisons
* Rice, wheat, and mustard production/prices across multiple years

## Learning Outcome

By completing this lab, I gained hands-on experience creating a variety of bar charts in Matplotlib, customizing their appearance, comparing multiple datasets using grouped and stacked bars, and integrating Pandas DataFrames to build clear and informative categorical data visualizations.
