# Probabilistic Models for Predicting COVID-19 Pandemic Spread

### Code Execution:

- Required Technologies: Install from _requirements.txt_ from the same directory using the below command. <br>
  ```
  $ pip install -r requirements.txt
  ```
- Dataset Source: Download _raw_data.csv_ and _districts.csv_ at [covid19india.org](https://www.covid19india.org)
  
  * To combine all the raw data files run __Merge.ipynb_ located in “Data till 2 may 2021/Raw Data” directory with all the raw_data files located in the same directory.
 
- Dataset is already present in the main directory named as _“main.csv”, “Graphdata.csv” and “districts.csv”_

- Then run _Final_Raw_Data.ipynb, Final_Bitmap.ipynb, Final_South_India.ipynb_ for different dataset creation.

- Model code: Run _Final_HBM.ipynb_ (Hierarchical Bayesian Model), <br>
          _Final_PLR.ipynb_ (Piecewise Linear Regression), <br>
          _Final_SES.ipynb_ (Simple Exponential Smoothing), <br>
          _Final_XGBoost.ipynb_ (XGBoost) <br>
          
- To run the webapp: Run _Final_Website.ipynb_ after running the model code with the following files present:
  
  * andhra pradesh_district.json
  * karnataka_district.json
  * kerala_district.json
  * maharashtra_district.json
  * states_india_copy.json
  * tamil nadu_district.json
  * And all the files generated after running model codes
 
  
