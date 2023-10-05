# Supply Chain Optimization for a FMCG Company
![FMCG](https://github.com/HibaBargaoui/Project-2/assets/135720154/5ffbb442-86b8-422c-874f-0152f4dc77f0)



**Author**: Hiba Bargaoui 

## Business problem: 
To improve the FMCG company's supply chain, it's crucial for higher management to strike a balance between customer demand and product supply. Data scientists play a key role in this process. Their task is to create a strong and reliable model that can aid the company in figuring out the perfect weight of products to be shipped to each warehouse. By doing so, the company can ensure a seamless and efficient supply chain, meeting customer demands effectively.


## Data Description: 
This dataset contains 25000 rows and 24 columns of valuable information about the instant noodles business that the FMCG has created. 

Data source: https://www.kaggle.com/datasets/suraj9727/supply-chain-optimization-for-a-fmcg-company
## Data Dictionary:
![imgonline-com-ua-twotoone-AchdCrVuq7Psoyf](https://github.com/HibaBargaoui/Project-2/assets/135720154/f6177a40-b866-452f-8cd6-2a077007ee96)


## Data Analysis:
In order To gain deeper insights into the data patterns, we examined the data employing straightforward and informative data visualizations:


![im1](https://github.com/HibaBargaoui/Project-2/assets/135720154/3aa9d830-4cd2-4383-a580-a901b7a23ea0)


* This histogram shows that most of the warehouses are located in the Rural zone which could potentially impact the FMCG company’s agility.
  

![imgonline-com-ua-twotoone-yMw9Pex3fs73](https://github.com/HibaBargaoui/Project-2/assets/135720154/96ff8b9c-af7a-49e9-9a16-dd49c8371cf4)


* The majority of products are dispatched to the North, primarily due to its large storage capacity. However, The more products we store, the more storage complications we might encounter, as suggested by the graph below:


![im4](https://github.com/HibaBargaoui/Project-2/assets/135720154/72354a05-6ce5-45d1-9921-3a18ae707227)

  

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
