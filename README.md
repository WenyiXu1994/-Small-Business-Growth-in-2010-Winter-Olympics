# Small-Business-Growth-in-2010-Winter-Olympics
This is a project finished in DataOpen challenge under the guidance of data experts from Citadel and Correlation One.  
  
A brief introduction of this project is described in file "Project_Poster".  
Detailed description of this project is in the file "Project_Report".

## Project Description

### Step 1: Structural break test of different regions
We visualized the growth of small business amount in region DR01 - DR08 and tested if there exist structural breaks in time series (QLR test). We concluded that DR01, DR04, and DR06 are significantly sensitive to the $2010$ Winter Olympics, with p-value 0.141, 0.095, and 0.094.  
![avatar](/images/break.png)


### Step 2: Spectral clustering of industries
We utilized the Pearson correlation matrix of industries to identify the high & low sensitive industries to the 2010 Winter Olympics. The structural break p-values of cluster 1 (sensitive) and cluster 2 (insensitive) are $0.078$ and $0.390$. We further verified that the regions with higher growth rates have higher proportions of cluster 1 industries, which validated our argument.  
![avatar](/images/cluster.png)

## Conclusion
The differences of small business growth patterns among the districts in British Columbia Amrea during the 2010 Winter Olympics are caused by the different industry composition in these districts.
![avatar](/images/logic.png)
![avatar](/images/logic.png)   

