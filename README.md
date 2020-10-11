# Ramp-Technical-Assessment

The data used in the python assessment is saved in this repo: demo_test_data.csv

## 1) Weighted retention curve for last 180 days
 - The weighted retention curve which I have plotted includes the NaN values in the weighted calculation as zeros, I would have excluded those items from the calculation if I had more time to get the calculation correct:
![alt text](https://github.com/SarahGraceMaclean/Ramp-Technical-Assessment/blob/main/Matrix.png)
  
## 2) Fit power curve to weighted retention curve
 - The power curve seems to flatten out at about 5% retention. Had I got the weighting calculation correct in the previous question, I think the curve would have followed the weighted retention data more closely - the later weighted values would have been higher if the NaN/zeros were excluded from the calculation (the last D180 value is 4.7% which is very close to 5%).
 
## 3) Plot modelled daily active users against actual data
- I am sure there is a more efficient/better way to calculate the modelled values. The curve flattens out after about 30 days and therefore the number of daily active users from each cohort should stay very consistent from about D30 - there may be a way to consider this assumption in the calculation to make it more efficient. 

## Observation
- I thought it was interesting that the retention rate for cohorts of users installing the software over weekends is consistently higher. 
