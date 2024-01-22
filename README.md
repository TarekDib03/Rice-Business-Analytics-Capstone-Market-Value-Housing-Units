### Reading Data and Importing Modules


```python
# Change working directory
import os
os.chdir("D:\Rice_Uni_Business_Analytics_Capstone\Data")

# Data files with extension .txt
txt_files = [item for item in os.listdir() if item.endswith(".txt")]
txt_files

    ['thads2001.txt',
     'thads2003.txt',
     'thads2005.txt',
     'thads2007.txt',
     'thads2009.txt',
     'thads2011.txt',
     'thads2013.txt']

```python
# Columns slected to be used for analysis
usecols = ["CONTROL", "AGE1", "METRO3", "REGION", "LMED", "FMR", "IPOV", "BEDRMS", "BUILT", "STATUS", 
           "TYPE", "VALUE", "NUNITS","ROOMS", "PER", "ZINC2", "ZADEQ", "ZSMHC", "STRUCTURETYPE", 
           "OWNRENT", "UTILITY", "OTHERCOST", "COST06", "COST08","COST12", "COSTMED", "ASSISTED"]
```
