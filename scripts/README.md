In order to execute correctly the Software Maintanability Prediction you should run firstly the data preparation and the Feature Subset Selection
with the notebook called 'Data_Exploration_Descriptive_Stats_and_Feature_Subset_Selection.ipynb'
and it will add files to the folder Datasets where 6 types of subset are stored: the Original Datasets and
5 Subset selected by each algorithm in that notebook.
Next you can run the other notebook 'Modeling_LSTM_and_Results.ipynb' that works automatically:
it will take each datasets, perform the fit and evaluation of the LSTM and store the results in a dictionary.
The dictionary will be saved then in the results folder as csv.
