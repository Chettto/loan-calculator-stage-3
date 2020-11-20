# Python education project by JetBrains: loan calculator stage 3/4 Annuity payment
## Description
Let's compute all the parameters of the loan. There are at least two kinds of loan: those with annuity payment and those with differentiated payment. In this stage, you are going to calculate only the annuity payment which is fixed during the whole loan term.
Where:
a = annuity payment;
p = loan principal;
i = nominal (monthly) interest rate. Usually, it’s 1/12 of the annual interest rate, and usually, it’s a floating value, not a percentage. For example, if your annual interest rate = 12%, then i = 0.01;
nn = number of payments. This is usually the number of months in which repayments will be made.
You are interested in four values: the number of monthly payments required to repay the loan, the monthly payment amount, the loan principal, and the loan interest.
## Objectives
In this stage, you should add new behavior to the calculator:
First, you should ask the user which parameter they want to calculate. The calculator should be able to calculate the number of monthly payments, the monthly payment amount, and the loan principal.
Then, you need to ask them to input the remaining values.
Finally, compute and output the value that they wanted.
Note that the user inputs the interest rate as a percentage, for example, 11.7, so you should divide this value by 100 to use it in the formula above.
Please be careful converting "X months" to "Y years and Z months". Avoid writing "0 years and 11 months" (output "11 months" instead) and "1 years and 0 months" (output "1 year" instead).

Note that in this stage, you have to ask the user to input parameters in a specific order which is provided below. Simply skip the value the user wants to calculate:

The first is the loan principal.
The second is the monthly payment.
The next is the number of monthly payments.
The last is the loan interest.

