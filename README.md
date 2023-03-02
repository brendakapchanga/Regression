    EXPLANATORY DATA ANALYSIS 
         Introduction
	   This is an explanatory data analysis for insurance company used in predicting data visualization 
	   for their data and getting to know the variables and relationship between them.
	   
       Variables in the Data set
		 Age
		 bmi
		 children
		 sex-either the customer is a female or male
		 region-whethe the customer is from southwest or northwest
		 smoker-whether the customer is a smoker or not
		 
		            Steps followed
	      checking the shape of dataset to determine the number of rows and columns.
	      checking for missing values and handle them appropriately.
              checking the data types of the variables to ensure they are in the correct format.
              summarise the statistics of the variables.
              visualize the distribution of the variables using Heatmap.
              checking the relationship between variables using pair plots,displot and Relplot.
			  checking the distribution of the categorical variables using  catplot.
			    
				
				       Descriptions
				       Heatmap.
			    The correlation heatmap illustrates the relationship between each dataset compared to every other dataset.Black indicates a close                                       relatonship.
			    Purple indicates a more distant correlation in the data.The heatmap tells that age,bmi and charges have a high correlation coefficient and
			    affect each other.Age and bmi have a lower correlation coefficient.
					  
				     Pair plot
				 The relationship between age and bmi is most linear,which means that they hold a strong relationship.
				 As the data points fall uphill from left to right,they have positive relationship.it means that there is an increase in 
				 bmi with increase in age.
				 Roughly,there are no major outliers in the plot,but there are high-leverage point of charges.
				     
					 Relplot
				There is a linear relationship between age  and charges.However,with increase in charges,the number of those smoking increases,
				while the number of those not smoking does not increase.proportionally they do not have a linear relationship.
				
				    Displot
				From the histogram we can confirm that the median count for bmi lies around 30.
				
				   catplot
				 The plot indicates that the charges in southeast region tend to higer and have more variation than the charges in other regions.
				 By looking at the plot,it can be said that regardless of charges for each region the average charges ranges from 0-50000.The majority
				 of the regions charges are below 60000.
				 Based on the defination of how we identify outliers the black dots are outliers in the charges factor attribute and the blue
				 coloured box is the IQR range.
				
				      Conclusion
				Explanatory data analysis is a key in order to have better understanding and representing your data,which helps in bulding stronger,
				more generalized model.so,the visualization of the data is easy to achieve,which facilitates the comprehension of our analysis
				
				
				
