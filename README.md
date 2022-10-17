This is a plain vanilla JavaScipt project of a simple Loan Calculator Application that can be used to compute 
loan amount for mortgages, car notes or any other type of repayment loan arrangement.
The application has three input fields namely: Loan Amount, Interest Rate and Load Duration. The result of the 
calculation based on the input values produce the monthly payment amount, total payment amount and the 
interest rate amount.

Primarily, I have used two JavaScript functions - (calculateResults and showError) to perform any computation requird by 
the Application and to display any exception when computations were impossible due to incorrect information being provided 
by the user.

The calculateResults function uses an addEventListener method to perform the computation upon the submit buttom being triggered
after the relevant information has been provided for the loan. The result generated are then displayed in the result section of 
the Application with a two seconds waiting period that is accomplished using the setTimeout method which aids in enhancing 
the user's experience.

Similarly, the showError function, which is triggered when incorrect values are provided by the user will result in an error 
message being displayed and then disappers within three seconds with the use of the setTimeout method for better user experience.

The application User Interface design was implemented with the Bootstrap front-end component library inconjuction with J-Query 
and popper.js dependencies.
