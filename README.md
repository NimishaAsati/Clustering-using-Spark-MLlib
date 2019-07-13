# Clustering-using-Spark-MLlib
Clustering Reuters-21578 using Spark MLlib and TF-IDF matrix

### Steps:

#### 1) Converted the 22 files lowercase.

#### 2) Transformed the lowercased file to TF-IDF, for a matrix representation for the text files. 
The value in row i column j represents the TF-IDF value of token j in file i.

#### 3) Clustered the 22 files into 4 groups using K-Means algorithm implemented on the TF-IDF matrix.

#### 4) Create output file with cluster ID for each file.


### To Execute:
Save the ipynb file and you can run it in Jupyter Notebook.
