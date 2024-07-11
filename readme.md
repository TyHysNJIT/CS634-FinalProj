# Overview
*	Algorithms
*	Random Forest (sklearn.ensemble - RandomForestClassifier)
*	LSTM (tensorflow.keras.layers -  LSTM)
*	K-Nearest Neighbors (sklearn.neighbors - KNeighborsClassifier)
*	Dataset
*	Census Income - https://archive.ics.uci.edu/dataset/20/census+income
*	Task

    This project will attempt to utilize the above three algorithms to correctly classify whether a given individual has an income greater than $50,000. Because of this, the task is fundamentally a binary classification problem. The individual being predicted either does (affirmative) or does not (negative) make greater than $50,000 a year.

# Setup  
This project is contained entirely within the notebook (CS634 Final Proj.ipynb). Any dependencies which require a package to be installed (tensorflow, sklearn, tqdm) are checked prior to the main body of the code running. If it detects that any of these packages are not available, it will attempt to install them:
As a result, installation should be as simple as clicking “Run All” in your respective notebook environment. Any dependencies which are needed should be installed by the above snippet.  
  
Data will be grabbed from the “/data/” folder relative to the notebook’s working directory. Because of this, if you clone the repository and run the notebook you should be able to successfully run all cells without any modifications. The data should be in the same relative path, and ingestion of the data into this notebook should be seamless.  
  
This should account for all necessary setup of this project, as the data will be automatically detected from the local file system upon execution. All other aspects of the notebook’s code are self-contained and will not require any intervention for running.  