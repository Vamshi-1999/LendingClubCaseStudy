# Consumer  Finance Company Case Study Analysis
> Consumer  Finance Company Case Study Analysis <br>
Team : Amit Goyal and Vamshi Raghu Guntha <br>
Date : 21-08-2024

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Overview:

> Consumer finance company specializing in various loans.

> Aims to reduce credit risk and financial losses.

> Analyzes historical data to identify loan default indicators.

> Goals include optimizing lending decisions, enhancing profitability, and ensuring compliance with regulations.

> Grounded in risk analytics principles to make data-driven decisions.

- The background of this project is rooted in the financial services sector, where a consumer finance company seeks to leverage data analysis and risk analytics to improve its lending practices, reduce credit risk, and enhance overall financial performance while ensuring compliance with regulations.

   Business Problem:
   The primary business problem this project is trying to solve is related to managing credit risk and minimizing financial losses associated with lending loans. There are 
   two types of risks the company faces:

   Loss of Business: If the company rejects loan applications from applicants who are likely to repay, it results in a loss of potential business opportunities.

   Financial Loss: On the other hand, if the company approves loans for applicants who are likely to default, it can lead to financial losses, as borrowers may fail to 
   repay the loans.

   Data Availability:
   The project relies on historical data that contains information about past loan applicants and whether they defaulted on their loans. This dataset is used for analysis 
   to identify patterns and factors that indicate whether a person is likely to default on a loan.

   Business Objectives:
   The main objectives of the project are as follows:

   Identify patterns and indicators that can predict loan defaults.
   Minimize credit losses by making informed lending decisions.
   Optimize the loan portfolio to reduce the risk associated with lending.
   Enhance profitability by approving loans for applicants more likely to repay.
   Ensure compliance with regulatory requirements related to credit risk assessment.

   Risk Analytics and Decision-Making:
   The project is grounded in the principles of risk analytics, which involves using data analysis and statistical techniques to assess and manage risk. By understanding 
   the factors driving loan defaults, the company aims to make data-driven decisions about approving or rejecting loan applications, adjusting interest rates, or setting 
   other lending terms.

- The business problem that this project is trying to solve is to minimize credit risk and financial losses associated with lending loans to individuals. Specifically, the company aims to address the following challenges:

> Identifying Risky Applicants: The primary objective is to develop a better understanding of the factors that contribute to loan defaults. By doing so, the company seeks to identify and flag applicants who are more likely to default on their loans. This is crucial for reducing the credit risk associated with lending.

> Minimizing Credit Loss: The company wants to minimize credit losses, which occur when borrowers fail to repay their loans. Defaulting borrowers can lead to significant financial losses, and identifying high-risk applicants in advance can help mitigate this risk.

> Portfolio and Risk Assessment: To make informed decisions about lending, the company needs to assess the risk associated with its loan portfolio. Understanding the driving factors behind loan defaults allows for a more accurate evaluation of portfolio risk. This knowledge can be used to optimize the loan portfolio by adjusting lending criteria, interest rates, or loan amounts.

> Enhancing Profitability: By reducing the number of loans granted to high-risk applicants, the company can enhance its profitability. This involves making data-driven decisions to approve loans for applicants who are more likely to repay them.

> Compliance and Regulatory Considerations: Lending institutions often have legal and regulatory obligations to assess and manage credit risk. Failing to do so can lead to legal and financial consequences. Therefore, understanding and managing risk is not only a financial concern but also a regulatory requirement.

In summary, the business problem this project aims to solve revolves around improving the company's ability to make informed lending decisions by identifying the key variables and factors that influence loan defaults. By doing so, the company can reduce credit losses, enhance profitability, and ensure compliance with regulatory requirements.

- 'loan.csv' dataset is used here.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Minor Impact
	Higher loan amount (above 16K)
	Higher installment amount (above 327)
	Lower annual income (below 37K)
	Higher debt to income ratio (above 15%)
	Applicant’s address state (NV, SD, AK, FL, etc.)
	Loan issue month (Dec, May, Sep)

Heavy impact
	Higher interest rate (above 13%)
	Higher revolving line utilization rate (above 58%)
	Repayment term (5 years)
	Loan grade & sub-grade (D to G)
	Missing employment record
	Loan purpose (small business, renewable energy, educational)
	Derogatory public records (1 or 2)
	Public bankruptcy records (1 or 2)

Combined impact
	High loan amount & interest rate for lower income group
	High installment and longer repayment term
	Home ownership (other) and loan purpose (car, moving or small business)
	Residential state and loan purpose
	Income group and loan purpose. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupiter Notebook: 7.0.8
- Python: 3.11.7
- Numpy:  1.26.4
- Pandas: 2.1.4
- Seaborn:  0.12.2
- Matplotlib: 3.8.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [[@Amit-code2024](https://github.com/Amit-code2024), [@Vamshi-1999](https://github.com/Vamshi-1999)] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
