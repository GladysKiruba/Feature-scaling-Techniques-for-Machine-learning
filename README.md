# Feature-scaling-Techniques-for-Machine-learning
The numerical features can be of different range. If the difference is larger the machine learning model may produce poor results. In order to overcome this, data is transformed by using feature scaling methods to fit into a particular range.

**Why scaling is needed in Machine learning?**

The numerical features can be of different range. If the difference is larger the machine learning model may produce poor results. In order to overcome this, data is transformed by using feature scaling methods to fit into a particular range.

**Feature scaling Techniques:**

•	Standardization
•	Min-Max Scaling
•	Absolute Maximum Scaling
•	Robust Scaling

**1)	Standardization**

In this method Z value is calculated by the below formula for each and every data and it is replaced with the new value.
X new = (X-X mean)/σ

**2)	Min-Max Scaling:**

X new=(X-X min)/(X max-X min)
In Min-Max scaling method new value is calculated by subtracting each value from the dataset with the minimum value and then it is subtracted by the difference of the maximum and minimum value. All the new values lie in between 0 and 1

**3)	Absolute Maximum Scaling:**

In this method each value in the column is divided by the maximum value of that particular column. Here the new values lie between -1 to 1.

**4)	Robust Scaling**
New value is calculated by subtracting each value with the median value and divided by the Inter Quantile Range (IQR). It is the difference between 75th percentile and 25th percentile. 
X new = (X-X median)/IQR
Unlike the other scaling methods it is robust to the outliers.


