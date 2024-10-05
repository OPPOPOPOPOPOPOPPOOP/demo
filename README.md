# demo

It is for NASA Space app challenge 2024 
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor

# data

lol = pd.read_csv("archive op.csv")

# Drop missing values 

lol1 = lol.dropna()  # 

# Make a copy 

lol2 = lol1.copy()

# Set the random seed

np.random.seed(87)   
