# profision_task

`profision.ipynb` contains all the tasks in order (Task 1 -> Task 7).

### Task Overview:

1.  Data Loading and Cleaning

2.  Exploratory Analysis
    *   `vessel_operational_status`
    *   `ais_speed`
    *   `ais_draft`

3.  Add New Dimension
    ![image](https://github.com/user-attachments/assets/b06f453e-7451-4da5-898f-39f52ee07eb2)
    *   Create a new column called `vessel_class` that maps each vessel to one of the above size categories.

4.  Cargo Analysis

5.  Geographical Analysis 

6.  Putting It All Together 
    *   Provide an analysis of vessels that loaded cargo in Southeast Asia between August 20, 2024 and August 24, 2024.
        *   What cargo was loaded onto these vessels?
        *   What are the top 2 exports from each country in Southeast Asia?
        *   Where is the cargo headed?
        *   Who are the most active operators in the region during this time period?
        *   What’s the relationship between the draft reported via AIS (`ais_draft`) compared with the vessel characteristic draft (`draft`)?

---

## Getting Started

**1. Import necessary packages:**


import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

Upload vessel_charachteristics.csv and vessel_positions.csv to directory
![image](https://github.com/user-attachments/assets/94d956bc-67d8-496a-baba-25ceaf34c6b5)

## Running


run all the cells for the desired output 

## Few PLots
![image](https://github.com/user-attachments/assets/ea06f285-e944-44f2-a194-9c04707b9192)
![image](https://github.com/user-attachments/assets/18e88ecb-89d3-4561-b02d-c8733e91afc0)



