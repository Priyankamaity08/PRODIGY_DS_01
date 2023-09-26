# PRODIGY_DS_01
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import scipy as sp
customer_satisfaction_data = {'Price':4.8, 'Product_Quality':4.5, 'Delivery_Speed': 4, 'Packaging': 3.7 }
attributes = list(customer_satisfaction_data.keys())
ratings = list(customer_satisfaction_data.values())
plt.bar(attributes, ratings, color ='pink', width=0.5)

plt.xlabel('Attributes')
plt.ylabel('Satisfaction Ratings')
plt.title('Customer Satisfaction Ratings')

plt.show()
