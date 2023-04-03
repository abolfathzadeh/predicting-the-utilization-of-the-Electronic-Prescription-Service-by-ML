# predicting-the-utilization-of-the-Electronic-Prescription-Service-by-ML
predicting the utilization of the Electronic Prescription Service (EPS) and Electronic Repeat Dispensing (eRD) items to categorize General Practitioner (GP) practices based on their usage patterns

## Data Description
The dataset contains 1,498 records related to dispensaries, EPS, and eRD acquired from the National Health Service (NHS) online medical database in the UK. Each record includes the following variables:
•	Region: The region of the UK where the dispensary is located.
•	Place Code: The code assigned to the place where the dispensary is located.
•	Place: The name of the place where the dispensary is located.
•	ODS Code: "Organization Data Service", a unique identifier assigned to the dispensary.
•	GP Practice (ODS Code): The ODS code of the GP practice associated with the dispensary.
•	Registered Patients: The total number of patients registered with the dispensary.
•	% of patients with a nomination: The percentage of registered patients who have nominated the dispensary as their preferred dispensing site.
•	EPS Items: The number of prescription items that have been processed using the Electronic Prescription Service (EPS) at the dispensary.
•	eRD Items: The number of prescription items that have been processed using the Electronic Repeat Dispensing (eRD) service at the dispensary.
•	All Items: The total number of prescription items dispensed at the dispensary.
•	EPS Utilisation: The percentage of prescription items processed using EPS out of all items dispensed.
•	eRD Utilisation (EPS Items): The percentage of prescription items processed using eRD out of all items processed using EPS.
•	eRD Utilisation (All Items): The percentage of prescription items processed using eRD out of all items dispensed.
Figure 1 below is a view of the first few rows of the dataset used for this study, while Figure 3 shows the summary statistics.
![image](https://user-images.githubusercontent.com/9671082/229549721-508f29b2-c130-46ff-b0aa-83761a859e48.png)

## result
The Random Forest Regression model outperformed both the Linear Regression and the Decision Tree Regression models, as it had the lowest RMSE value. 
This suggests that the Random Forest model was able to predict the target variable (EPS Utilisation) more accurately using the input features.
![image](https://user-images.githubusercontent.com/9671082/229549995-5a52d6da-aeda-4d1b-abc3-41d632d21a8a.png)
![image](https://user-images.githubusercontent.com/9671082/229550091-6b5f1d3c-97ba-437a-a79a-188611c48e3f.png)
