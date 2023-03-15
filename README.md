# Ekeeda-Mini-Project-3

# Understanding the dataset
Problem statement: We have data from a Portuguese bank on details of customers related to selling a term deposit The objective of the project is to help the marketing team identify potential customers who are relatively more likely to subscribe to the term deposit and this increase the hit ratio

# Data info:

1. age (numeric) <br>
2. job : type of job (categorical: "admin.","blue-collar","entrepreneur","housemaid","management","retired","self-employed","services","student","technician","unemployed","unknown") <br>
3. marital : marital status (categorical: "divorced","married","single","unknown"; note: "divorced" means divorced or widowed) <br>
4. education (categorical: "basic.4y","basic.6y","basic.9y","high.school","illiterate","professional.course","university.degree","unknown")
5. default: has credit in default? (categorical: "no","yes","unknown") <br>
6. housing: has housing loan? (categorical: "no","yes","unknown") <br>
7. loan: has personal loan? (categorical: "no","yes","unknown") <br>
8. contact: contact communication type (categorical: "cellular","telephone") <br>
9. month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec") <br>
10. day_of_week: last contact day of the week (categorical: "mon","tue","wed","thu","fri") <br>
11. duration: last contact duration, in seconds (numeric) <br>
12. campaign: number of contacts performed during this campaign and for this client <br>
13. pdays: number of days that passed by after the client was last contacted from a previous campaign <br>
14. previous: number of contacts performed before this campaign and for this client <br>
15. poutcome: outcome of the previous marketing campaign <br>
16. emp.var.rate: employment variation rate - quarterly indicator <br>
17. cons.price.idx: consumer price index - monthly indicator <br>
18. cons.conf.idx: consumer confidence index - monthly indicator <br>
19. euribor3m: euribor 3 month ratev
10. nr.employed: number of employees - quarterly indicator <br>

# Conclusion:
There is no much difference in model performance after dealing with outliers, The performance can be incresed by tuning and so far the best fit model is Gradient boosting and adaboost model
