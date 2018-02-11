# HR-ATTRITION-CASE-STUDY--IIIT
Develop a model to identify whether a employee will leave a company or not.

#                                 Business Understanding
##################################################################################################################################

 Basically in large companies, employee count will affect the business drastically . If a new employee enters the organisation,there needs to be a initial understanding about the business and internal logistics.Lot of KT and several trainings has to be given to the employees inorder to make them productive.If an employee leave the company, they need to be replaced with the talent pool available 
 in the job market and also the projects and their timelines will get delayed which leads to a reputation loss among consumers and partners as well as the money.So, we are developing a model which will predict the probability of employee attrition, 
 which helps company to be proactive.

##################################################################################################################################
#                                 Data Understanding
##################################################################################################################################


# Age gives  age of the employee	
# Attrition explains us Whether the employee left in the previous year or not	
# BusinessTravel explains	How frequently the employees travelled for business purposes in the last year	
# Department explains	Department in company	
# DistanceFromHome	gives info about Distance from home in kms	
# Education	contains four Levels	1 'Below College'2 'College'3 'Bachelor'4 'Master'5 'Doctor'
# EducationField	Field of education	
# EmployeeCount	 gives no info as it is single Employee data	
# EmployeeNumber unique id in the dataset	acts as a primary key	
# EnvironmentSatisfaction	explains Work Environment Satisfaction of employee contains four Levels	1 'Low'2 'Medium'3 'High'4 'Very High'
# Gender tells us the	Gender of employee	
# JobInvolvement explains about the	Job Involvement of the employee contains four Levels	1 'Low'2 'Medium'3 'High'4 'Very High'
# JobLevel gives the employee	Job level at company on a scale of 1 to 5	
# JobRole	gives the employee Name of job role in company	
# JobSatisfaction	explains the employee Job Satisfaction with four Levels	1 'Low'2 'Medium'3 'High'4 'Very High'
# MaritalStatus	gives Marital status of the employee	
# MonthlyIncome gives the employee	Monthly income in rupees per month	
# NumCompaniesWorked explains	Total number of companies the employee has worked for	
# Over18 gives no info as all the employees will be over 18	
# PercentSalaryHike gives the	Percent salary hike for last year	
# PerformanceRating gives the employee	Performance rating for last year with four levels	1 'Low'2 'Good'3 'Excellent'4 'Outstanding'
# RelationshipSatisfaction gives the employee	Relationship satisfaction contains four levels	1 'Low'2 'Medium'3 'High'4 'Very High'
# StandardHours gives	Standard hours of work for the employee	
# StockOptionLevel gives Stock option level of the employee	
# TotalWorkingYears gives	Total number of years the employee has worked so far	
# TrainingTimesLastYear explains	Number of times training was conducted for this employee last year	
# WorkLifeBalance explains	Work life balance of the employee with four levels	1 'Bad'2 'Good'3 'Better'4 'Best'
# YearsAtCompany gives	Total number of years spent at the company by the employee	
# YearsSinceLastPromotion	gives Number of years since last promotion	
# YearsWithCurrManager	gives Number of years under current manager
# In and out time dataset give the employee working hours and their leaves taken 


####METHODS#########
Logistic Regression With STEPAIC.

#                                    CONCLUSIONS
################################################################
#Our Logistic Regression model is able to predict with 77% accuracy.
#Sensitivity is more important to us.
#Overall Accuracy was 81%.
#Sensitivity  of our model is 81% i.e. it correctly identifies 81% of employees which are likely to leave the company.
#Specificity of our model is 80% i.e. it correctly identifies 80% of employees which are not likely to leave the company.
#KS Statistics for the model is 54% which indicates our model is fairly good and accurate.

#   Recommendations are as follows:
#1. Company should takes some actions to improve work life balance of employees.
#2. Working environment should be improved. Employees should get regular breaks. Quizes and indoor games should be promoted.
#3. Managers should not be changed very frequently.
#4. For Frequently traveling employees, company should take some steps to keep them in our company.
