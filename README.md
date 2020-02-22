# Project Overview
- Data on sales from book retailers from 1992 to late 2019 was gathered from the Federal Reserve Economic Data (FRED).
- The goal of this project was to use the book sales history to create a model that can forecast future sales into the end of 2020.
- A model was created using an LSTM recurrent neural network, which was trained on a subset of the data and the results were compared to a test set.
- Once satisfactory performance was achieved, a second LSTM model was trained using the entire data set, which was then used to project book sales of retailers into 2020.

The project notebook can be found in the .ipynb file. <br>

The dataset is can be found under MRTSSM451211USN.csv and the library requirements/versions used for this project are located in the requirements.txt file. <br>

<b>Technologies used for this project:</b> python, pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow, keras, jupyter notebook.
