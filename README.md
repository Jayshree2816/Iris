# Iris

# 1. Import below libraries

	a. Pandas - import pandas as pd
	b. Numpy - import numpy as np
	c. Seaborn - import seaborn as sns
	d. Matplotlib import matplotlib.pyplot as plt

# 2. Import the CSV file using pd.read_csv

	df = pd.read_csv("iris.data", header = None)

# 3. Check the imported dataset using below functions

	a. df.head() - first 5 rows of data
	b. df.columns - get the columns names
	c. df.describe - get min , max, std values 
	d. df.info - get info of column name with datatype
	e. df.isnull - check if is there any null value in dataset

# 4. Visualization

	plot the below graphs to check the relations between the data variables
		a. pairplot
		b. histogram 
		c. violinplot
		d. boxplot
		e. scatterplot 













