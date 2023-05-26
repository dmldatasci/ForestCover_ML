# ForestCover_ML
Examining forest cover type prediction through a variety of supervised learning techniques.

# Requirements:
1. Find a problem worth solving, analyzing, or visualizing.
2. Use machine learning (ML) with the technologies we’ve learned.
3. You must use Scikit-learn and/or another machine learning library.
4. You must use at least two of the following: 
Python Pandas
Python Matplotlib
HTML/CSS/Bootstrap
JavaScript Plotly
JavaScript Leaflet
Tableau
SQL Database
MongoDB Database
Google Cloud SQL
Amazon AWS

# Data in SQL:
Put the name of the file or screen capture on the SQL table that holds the test and train dataset.
# Machine Learning Accuracy Scores

<img width="205" alt="machine_learning_scores" src="https://github.com/dmldatasci/ForestCover_ML/assets/117786548/ec0cf7da-2c2f-4783-93fe-c6df41c72704">

# Visualization 1: Number of Trees by Cover Type
![predictions_cover_type_count](https://github.com/dmldatasci/ForestCover_ML/assets/86619869/3352ccf3-9316-484f-8d83-3e662e94158f)

# Visualization 1: Number of Trees by Cover Type
![predictions_tree_count_per_WA](https://github.com/dmldatasci/ForestCover_ML/assets/86619869/6d42b0e6-cbf7-467b-982f-31b5f37f8e1b)

# Visualization 3:
![predictions_tree_count_per_elevation](https://github.com/dmldatasci/ForestCover_ML/assets/86619869/104d34ab-737f-49d0-b2b6-56f4e3337b8e)

# Authors and acknowledgment:
Daniel Carrasco, David Levy, Joel Pangilinan, Poonam Fandan, and Ra-Cee Lucas
* Edited README file
* Studied the dataset at https://archive.ics.uci.edu/ml/datasets/Covertype
* Explore Data Analysis
* Research on what machine learning framework I should use.  I settled with PyTorch
* Worked on cleaning the dataset for both test.csv and train.csv.  The clean datasets are in joel branch (clean_test.csv and clean_train.csv). 
* Worked on machine learning and saved the predicted cover types in joel branch - test_predictions.csv
* Worked on visualizations.  All png files are located in joel branch.
* Code for cleaning is joel_clean_dataset.ipynb at joel branch
* Code for machine learning is joel_machine_learning.ipynb at joel branch
* Code for visualizations is joel_visualize.ipynb at joel branch
* Edited README file
* Studied the dataset at https://archive.ics.uci.edu/ml/datasets/Covertype
* Created two different Machine learning models using RandomForestClassifier and KNeighborsClassifier and compared the scores- Forest_cover_type_pred0.ipynb
* Created Postgresql database, created the SQL table “coverage_type”. Worked on loading the  covertypes data that was available in csv (covtype.csv) into “coverage_type”table.  The scripts to create the table and data load can be found in pfandan create_table_Cover_type.sql, Load_CSV_to_Cover_type.sql
* Code for multiple type of machine learning on Daniel_Machine_Learning in Daniel file
* Saved csv prediction in predictions_csv file found in Daniel file
* 2d Cluster Visualization in Cluster_Visualization found in Daniel file

# References:
UCI Machine Learning Repository - https://archive.ics.uci.edu/ml/datasets/Covertype

# Project status:
Completed
