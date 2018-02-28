# Hypothesis-Testing- (DONE by using "MINITAB 18" software)

 # Remember the thumb rule for Hypothesis testing "p LOW Ho GO" and "p HIGH Ho FLY"
  This means if the p value after every step is less than "0.05" then let "Ho" go and accept "Ha" and if the p-value is greater than 0.05 then "Ho" fly that means accept "Ho"

For all the datasets above in the repository hypothesis testing is done in the following way 

# STEP 1 : Define your business problem

# STEP 2 : Check your inputs and output whether they are continous and discrete and after doing that us the following data and perform approperiate test

    Y = continuous & X = discrete in exactly 2 categories do 2-sample t test and follow the below steps 
           1. Normality test (Ho = Data are normal , Ha = Data are not normal)
           2. Variance test  (Ho = variances in diameters of 2 units is equal , Ha = variances in diameters of 2 units is not equal)
           3. 2 sample t test with equal variance /unequal variance  (Ho = Average of unit A = average of unit B , Ha = Average of unit A NOT = average of unit B)
    
    Y = continuous & X = discrete in > 2 categories we proceed with ANOVA test and follow the below steps 
           1. Normality test (Ho = Data are normal , Ha = Data are not normal)
           2. Variance test  (Ho = variances in diameters of 2 units is equal , Ha = variances in diameters of 2 units is not equal)
           3. ANOVA - One Way or Two Way ( Ho = All averages of dataset are equal , Ha = Atleast one average in dataset are not equal)
           4. Analysis of Variance (If Ha is accepted then perform  TUKEY’s Comparision)
  	
    Y = Discrete & X = discrete in exactly 2 categories then we go with 2 Proportion test and follow the below steps 
           1. 2 proportion  test for association (Ho = proportions of both inputs are equal , Ha = proportions both inputs are not equal)
           2.	From the proportion test the p-value(0.00)<0.05 so “accept Ha”
		       3. Accepting alternate hypothesis and comparing. (Ho = Proportion(X1) <= Proportion(X2) , Ha = Proportion(X1) > Proportion(X2))


    Y = Discrete & X = discrete in > 2 categories  then we go with Chi-square test and follow the below tests
           1. Stack into two columns in the same file
		       2. chi-square  test for association (Ho =  % in all the X is equal , Ha = % in all the X is not equal)
			   
# STEP 3 : Prepare an approperiate solution for your business problem using the above results from the respective test

Ho = Null Hypothesis and Ha = Alternate Hypothesis 
p-value is 0.05 because the accepted value or the default value of error for a business problem is taken as 0.05
