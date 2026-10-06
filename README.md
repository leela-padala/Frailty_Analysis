# Frailty and Grip Strength Analysis

An exploratory Python notebook maintained by **Leela Padala**. It examines the relationship between grip strength and the recorded frailty label in a small, ten-record sample using pandas, seaborn, and matplotlib.

## Work in This Repository

- Inspect column names and missing values.
- Encode the Y/N frailty label for a correlation calculation.
- Compare grip strength by frailty group with a boxplot.
- Normalize column names for subsequent analysis.

## Files

- [Notebook](Copy_of_Frailty_Grip_Strength.ipynb)
- [Ten-record input sample](frailty_data.csv)

## Running the Notebook

Open the notebook in Google Colab and upload `frailty_data.csv` when prompted. The analysis imports pandas, seaborn, and matplotlib. The first cell references `frailty_data` before it is initialized: on a fresh runtime, start with the second, initialization/analysis cell. Notebook code has been preserved rather than silently changing the original exercise.

The expected fields are `Height`, `Weight`, `Age`, `Grip Strength`, and `Frailty`. The sample's original provenance and measurement units have not been independently verified.

## Scope and Validation

This is a learning exercise, not a clinical model or a cybersecurity tool. Ten observations cannot establish causation, population-level findings, or medical recommendations. Before interpreting results, check the uploaded filename, column names, Y/N labels, and generated chart against the included sample.

The portfolio documentation review checked the notebook structure and bundled CSV schema. It did not certify a fresh end-to-end notebook execution.

## Other Sample Data and Attribution

`mnist_test.csv` and `anscombe.json` are unrelated sample data retained from the original repository. The original sample-data notes attributed MNIST to the [MNIST database](http://yann.lecun.com/exdb/mnist/) and Anscombe's quartet to:

Anscombe, F. J. (1973). *Graphs in Statistical Analysis*. American Statistician, 27(1), 17-21. JSTOR 2682899.

The quartet copy was prepared by the [vega_datasets library](https://github.com/altair-viz/vega_datasets/blob/4f67bdaad10f45e3549984e17e1b3088c731503d/vega_datasets/_data/anscombe.json). The original generic notes also mentioned California housing sample files, which are not present in this repository.
