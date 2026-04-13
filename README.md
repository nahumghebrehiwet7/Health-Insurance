# Health-Insurance
Simple python and SQL project analyzing how different characteristics can influence healthcare charges

# Python is used to check any issues regarding the data. 
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
df = pd.read_csv(r"C:\Users\nahum\Downloads\insurance.csv")
null_counts = df.isnull().sum()
print(null_counts)

