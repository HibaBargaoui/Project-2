# Supply Chain Optimization for a FMCG Company


**Author**: Hiba Bargaoui 

## Business problem: 
To improve the FMCG company's supply chain, it's crucial for higher management to strike a balance between customer demand and product supply. Data scientists play a key role in this process. Their task is to create a strong and reliable model that can aid the company in figuring out the perfect weight of products to be shipped to each warehouse. By doing so, the company can ensure a seamless and efficient supply chain, meeting customer demands effectively.


## Data: 


For this dataset, we have 8523 rows and 12 columns. 

## Data Dictionary:


In order To gain deeper insights into the data patterns, we examined the data employing straightforward and informative data visualizations:

## Data Analysis:



* This histogram shows that most of the warehouses are located in the Rural zone which could potentially impact the FMCG company’s agility.



* The majority of products are dispatched to the North, primarily due to its large storage capacity. However, The more products we store, the more storage complications we might encounter, as suggested by the graph below:

  

## Best Maching Learning Models:
#### Gradiant Boosting Regressor: 
* Evaluation metrics for the training set:
  
  Mean_Absolute_Error: 667.66 
  
  Mean_Squared_Error: 782704.62
  
  Root_Mean_Squared_Error: 884.71
  
  R2_scores: 0.99

* Evaluation metrics for the testing set:
  
  Mean_Absolute_Error: 670.73  
  
  Mean_Squared_Error: 782804.50
  
  Root_Mean_Squared_Error: 884.76 
  
  R2_scores: 0.99
  
--> By employing the Gradient Boosting Regressor, we can make highly accurate predictions. This model enables us to determine the optimal product weights for shipmentto the different warehouses, ensuring the most efficient distribution strategy.

## Recommendations:
To align supply with demand effectively, the FMCG company should:
* Increase warehouse presence in urban zones which can optimize product distribution, catering to the densely populated areas more efficiently.
* Decrease the weight of products allocated to the North, ensuring a smoother storage process and minimizing complications.
* Expand the number of warehouses in the East in order to strategically cover all zones and have better supply chain management.

## For further information


For any additional questions, please contact **bargaoui.hiba42@gmail.com**
