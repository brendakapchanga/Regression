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
 checking the shape of dataset to determine the number of rows and columns,
 checking for missing values and handle them appropriately,
 checking the data types of the variables to ensure they are in the correct format,
 summarise the statistics of the variables,
 visualize the distribution of the variables using Heatmap,
 checking the relationship between variables using pair plots,displot and Relplot,
 checking the distribution of the categorical variables using  catplot.
			    
				
    Descriptions
       Heatmap.
 The correlation heatmap illustrates the relationship between each dataset compared to every other dataset.Black indicates a close  relatonship.
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
The plot indicates that the charges in southeast region tend to be higher and have more variation than the charges in other regions.
By looking at the plot,it can be said that regardless of charges for each region the average charges ranges from 0-50000.The majority
of the regions charges are below 60000.
Based on the defination of how we identify outliers the black dots are outliers in the charges factor attribute and the blue
coloured box is the IQR range.
	
     Conclusion
Explanatory data analysis is a key in order to have better understanding and representing your data,which helps in bulding stronger,
more generalized model.so,the visualization of the data is easy to achieve,which facilitates the comprehension of our analysis.



				
			
	
	
	
	Churn_Modelling
        Introduction
This is a predictive model for a customer in a bank predicting whether a customer is excited with the bank or not, whether the customer is going to leave the banks services or not based on the behaviour with their products.
     Variables used
RowNumber: a unique identifier for each record.
CustomerId: a unique identifier foe each customer.
Surname: a surname of customer.
CreditScore: credit score of customer.
Geography: country of the customer.
Age: age of the customer.
Gender: whether a male or female.
Tenure: period which the customer has been in the bank.
Balance: customers account.
NumOfProducts: number of bank products the customer is using.
HasCrCard: whether the customer has a credit card or not.
IsActiveMember: whether the customer is active or not.
Salary:  Estimated salary of the customer.
Exited: indicates whether the customer is exited with the bank or not.

          Steps Followed
load the customer churn data into pandas dataframe 
perform explanatory data analysis by checking the head of the data,the shape of data,for missing values and  plotting the distribution of numerical and categorical variables
prepare the data for the model by splitting it into training and test sets,one-hot encoding categorical variables and fitting a logistic regression model
predict customer churn using the logistic regression model and evaluate its performance using the classification report

                     Explanation
The code first loads the data into a pandas dataframe and performs EDA operations such statistical summary, distribution of target column and checking missing values 
Next,it then encodes the categorical features and concatenates the encoded features with the original data
Lastly,it splits the data into training and testing sets and fits a Logistic Regression model on the training data.It then predicts the target on the test data and evaluates the model using the confusion and classification report.


                      conclusion
With Machine learning and deep analysis it is possible to predict which customer is excited with the bank company and who will leave the services depending on the products offered.		      




	           
