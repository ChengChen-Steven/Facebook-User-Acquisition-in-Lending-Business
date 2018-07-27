# Facebook-Marketing-in-Lending-Business
The project is focusing on user acquisition through digital channels like Facebook. In lending business, companies want to acquire users that have a higher likelihood of repayment. However, in many financially underserved places, many people have no financial identity like a credit score. So taking the first risk is quite a thing here. <br>

This is a project collaborated with a fintech company. The datasets are a __random sample of only 1,000 records__. I will just talk slight about the background of the business. <br>

* __Business__: small-loan, short-term, ranging-interest-rate lending in financially underserved place in the world; <br> 

* __Value Proposition__: 
  * understand the data quality collected from survey during app-sign-up phase.
  * leverage statistical apporach to understand the likelihood of repayment and give insightsto new customer acquisition strategy.
  * recommend on digital targeting fields of user acqusition through Facebook Platform.  

* __Data__:
  * people.csv: loan applications survey questions
  * repayment.csv: loan disbursement and repayment dates
  * device.csv: device characteristics
  * mpesa.csv: a sample of mobile money transactions per user

* __What I will be doing here__:
  * A preliminary Data Quality Report (DQR) on the application data
  * Leverage logistic regression and interpret the results
  * Define customer life-time-value (LTV) model to help understand how to target the new user who will have the highest life time value for the business
  
  
__Note__: For the privacy issue, I will keep the company anonymous. The DQR is written in R markdown and the analysis is conducted in Python Jupyter. 


