
To be, or not to be
==================

Classy Shakespeare plays and players
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the Shakespeare plays dataset from https://www.kaggle.com/kingburrito666/shakespeare-plays 
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more classification models to determine the player using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub


Dataset
=============
The dataset is in the csv file called- Shakespeare_data.csv 

This dataset has been retrieved from a Kaggle dataset: https://www.kaggle.com/kingburrito666/shakespeare-plays


About the dataset
==================

Context:
This is all of Shakespeare's plays.

Content:
This is a dataset comprised of all of Shakespeare's plays. It includes the following:

The first column is the Data-Line, it just keeps track of all the rows there are.
The second column is the play that the lines are from.
The third column is the actual line being spoken at any given time.
The fourth column is the Act-Scene-Line from which any given line is from.
The fifth column is the player who is saying any given line.
The sixth column is the line being spoken.

--------------------------------------------------------------------------------------------------------------------------

Code for the project
====================
The notebook for this project can be found in the 1.0-EECS731-HW2.ipynb Jupyter notebook. 


Classification model
===================
Built a Random Forest Classifier to predict the Player, using all the other columns as features


-------------------------------------------------------------------------------------------------------------------------
