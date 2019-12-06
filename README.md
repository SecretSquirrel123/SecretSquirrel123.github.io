# SecretSquirrel123.github.io
Website to deploy CTL models

This project is a case study of the employee data provided, contained in 3 files:
1) CaseStudy2Data.xlsx - 870 rows of full data, including both attrition and salary (MonthlyRate).
2) CaseStudy2CompSet No Salary.xlsx - 300 rows of full data, except the MonthlyRate is missing, and to be predicted.
3) CaseStudy2CompSet No Attrition.csv - 300 rows of full data, except the Attrition is missing, and to be predicted.
Other than the missing fields that are noted, all columns were present for all data. All three files contain the same columns.

The following are the columns of data provided. I did not receive a description of the columns. 

 $ ID                          : int. unique.
 $ Age                         : int  
 $ Attrition                   : Factor w/ 2 levels "No","Yes"
 $ BusinessTravel              : Factor w/ 3 levels "Non-Travel","Travel_Frequently", "Travel Frequently"
 $ DailyRate                   : int  
 $ Department                  : Factor w/ 3 levels "Human Resources","Research and Development", "Sales"
 $ DistanceFromHome            : int  
 $ Education                   : Factor w/ 5 levels "1","2","3","4","5"
 $ EducationField              : Factor w/ 6 levels "Human Resources", "Life Sciences", "Marketing", "Medical", "Other", "Technical Degree"
 $ EmployeeCount               : int 
 $ EmployeeNumber              : int  
 $ EnvironmentSatisfaction     : Factor w/ 4 levels "1","2","3","4"
 $ Gender                      : Factor w/ 2 levels "Female","Male"
 $ HourlyRate                  : int  
 $ JobInvolvement              : Factor w/ 4 levels "1","2","3","4"
 $ JobLevel                    : Factor w/ 4 levels "1","2","3","4"
 $ JobRole                     : Factor w/ 9 levels "Healthcare Representative","Human Resources","Laboratory Technician", "Manager", "Manufactoring Directory", "Research Director", "Research Scientist", "Sales Executive", "Sales Representative"
 $ JobSatisfaction             : Factor w/ 4 levels "1","2","3","4"
 $ MaritalStatus               : Factor w/ 3 levels "Divorced","Married","Sinle"
 $ MonthlyIncome               : int  
 $ MonthlyRate                 : int  
 $ NumCompaniesWorked          : int  
 $ Over18                      : Factor w/ 1 level "Y"
 $ OverTime                    : Factor w/ 2 levels "No","Yes"
 $ PercentSalaryHike           : int  
 $ PerformanceRating           : Factor w/ 2 levels "3","4"
 $ RelationshipSatisfaction    : Factor w/ 4 levels "1","2","3","4"
 $ StandardHours               : int  
 $ StockOptionLevel            : Factor w/ 4 levels "0","1","2","3"
 $ TotalWorkingYears           : int  
 $ TrainingTimesLastYear       : int  
 $ WorkLifeBalance             : Factor w/ 4 levels "1","2","3","4"
 $ YearsAtCompany              : int  
 $ YearsInCurrentRole          : int  
 $ YearsSinceLastPromotion     : int  
 $ YearsWithCurrManager        : int  
