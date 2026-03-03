# Python_Data-Analysis

## Read from file (CSV , Excel ,JSON):

import numpy as np
import pandas as pd

df=pd.read_csv("/content/sample_data/data.csv", encoding='cp1252')

#Read from Excel
// pd.read_excel("/content/sample_data/data.xlsx",sheet_name="Sheet_name")

// Read and write from json
// import json
// with open("file.json", 'r',encoding='utf-8') as f:
//   cfg=json.load(f)
// cfg["threshold_mm"]=2.0

// with open("file.json", 'w',encoding='utf-8') as f:
//   json.dump(cfg,f,indent=2)
