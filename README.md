# Handling-Missing-Data
Know about all the different techniques to handle missing data to make better ML models.

<h2>Complete Case Analysis</h2>
<p>For Detailed Explanation Go to CompleteCaseAnalysis folder<p>
<div>
    <p>It is a technique in which the null value data is deleted considering some constraints.</p>
    <code>new_data = data[col].dropna()</code>
    <p>dropna() function deletes all the null values</p>
  </div>
  


<h2>Multivariate Imputations</h2>
It is a technique to fill in the missing data with appropriate values with the help of different column/features which is mostly similar to that of missing data.<br>
Famous techniques are:<br>

1. KNN Imputer
2. MICE

  
