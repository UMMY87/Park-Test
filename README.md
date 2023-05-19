### Park-Test
The Park Test is additionally considered a formal technique for detecting heteroscedasticity.
The Park Test serves the purpose of detecting heteroscedasticity within the data.
A significant test is conducted to identify the presence of heteroscedasticity, where heteroscedasticity is confirmed if the p-value is lower than the predetermined significance level, alpha.
To perform this function follow step-by step procedure
```R
Go to "Stat"
Go to "Regression"
Go to "Regression"
Go to "Fit Regression Model"
Put "y" in response
Put "x" in continious predictor
Go to "Storage"
Click option "Residuals" then ok, then ok
Now write "sqresi" in next column
Go to "Calc"
Go to "Calculator"
Put "sqresi" in Store result in variable
Put "RESI*RESI" in Expression
click "Ok"
Write "lnsqresi" in next column
Go to "Calc"
Go to "Calculator"
Put "lnsqresi" in Store result in variable
Go to function search "Logarithm"
Click "Natural log(log base e)"
LN appears in Expression
Click "sqresi"
Click "OK"
Write "lnx" in next column
Go to "Calc"
Go to "Calculator"
Put "lnx" in Store result in variable
Go to function search "Logarithm"
Click "Natural log(log base e)"
LN appears in Expression
Click "x"
Click "OK"
Go to "Stat"
Go to "Regression"
Go to "Regression"
Go to "Fit Regression Model"
Put "lnsqresi" in response
Put "lnx" in continious predictor
Go to "Storage"
Exclude option "Residuals" then click "OK"
Then click "Ok"
```
Now analysis results appears
According to given data in file p-value is greater than alpha.
So, it effected insignificantly and have homocedasticity at 5% level of significance.
If p-value is less then alpha. Then it effected significantly and have heteroscedasticity at 5% level of significance.
