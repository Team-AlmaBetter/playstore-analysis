# playstore-analysis
Almabetter project 
# import package
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt, seaborn as sns
%matplotlib inline
sns.set(color_codes=True)
 
path = '/content/drive/MyDrive/Colab Notebooks/Data for class/PlayStoreData.csv'
play_df = pd.read_csv(path)
play_df.info()
