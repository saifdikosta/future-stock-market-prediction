# future-stock-market-prediction
#import packages
import pandas as pd
import numpy as np

#to plot within notebook
# import matplotlib.pyplot as plt
# #setting figure size
# from matplotlib.pylab import rcParams
#rcParams['figure.figsize'] = 20,10

#for normalizing data
from sklearn.preprocessing import MinMaxScaler
scaler = MinMaxScaler(feature_range=(0, 1))

#read the file
df = pd.read_csv('NSE-TATAGLOBAL11.csv')

#print the head
print(df.head())
