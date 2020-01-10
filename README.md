# Banking-Analytics
I.Calculation of capital requirment and provisions of a Bank following Basel III agreement

In this project Bank analytics 1 i build my model to calculate bond price with unconventional coupon payments, which are randomly generated. 
Then with the standards and the functions of different capital requirments regulated in the Basel III .
I can easily get the capital requirement and risk assets of different business lines.
Furthermore, calculate the Risk weighted assets of these business lines(Based on Basel III).
Actually my project does not give a specific way to calculate 
In this part i read the details of the Basel III agreement, know the changes from the previous agreement and the regulatories of different business line.

II.Credit risk estimation

In the data cleaning part, I deal with the data from Lending club(2003-2017), which has 2 million samples and each sample has 148 variables.
I cleaned the data and leave useful variables and samples, then use WOE to find the important variables, finally get the data set i want.
for the Target object, i defined those charged off samples as Default, Fully paid as Good.
then use the logistic model to find the function of predicting Probability of Defualt(PD).
with the function we get from the logistic model, we can build a scorecard for our customers.
