This is repo for AD subject raports.

Datasets that will be worked on:
<li> Chronic_Kidney_Disease - <a href="https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease"> Dataset Link </a>

<code>
from ucimlrepo import fetch_ucirepo
fetch dataset 
chronic_kidney_disease = fetch_ucirepo(id=336)
data (as pandas dataframes) 
X = chronic_kidney_disease.data.features 
y = chronic_kidney_disease.data.targets  
metadata 
print(chronic_kidney_disease.metadata) 
variable information 
print(chronic_kidney_disease.variables) 
</code>
<li> 

