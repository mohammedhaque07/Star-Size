import numpy as np
import pandas as pd

file_name = input("Enter file Name: ")
star_type = input("Enter the name of the star type: ")
data = pd.read_csv(file_name)
x = data[data['Star type'] == (star_type)]
max_value = x['Radius(R/Ro)'].max()
min_value = x['Radius(R/Ro)'].min()

print("The radius of the largest",star_type,max_value)
print("The radius of the smallest",star_type,min_value)
