# Interactive Forecast Tool

## Installation

git clone https://github.com/maralski/ift.git

cd ift

conda env create -f environment.yml

## Run

voila ift_notebook.ipynb

## Usage

Upload spreadsheet or CSV containing following columns:

Group -> Item to plot

X -> Metric to plot on X-axis (usually date column)

Y -> Metric to plot on Y-axis

Y_MAX -> Metric used to set max Y-value. Used to forecast when Y approaches Y_MAX.

Select "Item" to measure.
Set **History** to number of points to look back.
Set **Forecast** to number of points to project ahead.
Set **Breakpoints** to number of breaks in piecewise linear regression.
