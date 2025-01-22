# lending-club-case-study
A Consumer finance company, specialises in lending various types ( personal loans, business loans and financing of medical procedures) of loans to urban customers, want's to build a risk analytics process of evaluating a borrwer's abilty to repay the loan and determine the like-lihood of default.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
   ### Business Understanding:
   A Consumer finance company, when receives a loan application, has to make a decision for loan approval based on the applicant’s profile. As part of risk
   mitigation, company want's to reduce the bussiness and financial or Credit loss. During evaluating a loan application there are two types of risks 
   associated with the bank’s decision:
   - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
   - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

   ### Business Objective:
   - Company's decision making in loan approval process is backed with strong analytics data, which helps to take a right decision for loan sancation.
   - Company's loan approval time can be reduced, which improves profitability and bussiness growth.
   - Company can mitigate the credit loss with help of risk analytics, by identifying the borrowers capability of loan repayment and can reduce such loans.
   - Company can mitigate the bussiness loss with help of risk analytics, by not rejecting a loan to a customer whose loan repayment status and credit score is very good or exceptional.
   - Company can take a decision on interest rate provided to customers based on the risk appetite i.e sancation a loan with high interest rate to a customer with average credit score and low interest rate to a customer with exceptional credit score.

  ### DataSet Understanding:
  Data given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person 
  is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher 
  interest rate, etc. Data contains consumer and loan attributes, which helps to take a decision of loan approval.There are two types of decisions that could be taken by the company using the risk analytics process.
 1. **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:
      1. Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
      2. Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
      3. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
 2. **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset).

  ### DataSet Attributes: 
  - The Loan.csv file has 39717 records.
  - There are a total of 111 columns.
  - The columns can be broadly be classified as follows.

  ### Data Classification:
   1. **Identifier** - `Id, member_id`
   2. **Loan Details** - `loan_amnt, funded_amnt, funded_amnt_inv, term, int_rate, installment, grade, sub_grade, issue_d`
   3. **Person Details** - `emp_title, emp_length, home_ownership, annual_inc, url, zip_code, addr_state, application_type`
   4. **Control Details** - `verification_status, pymnt_plan, policy_code`
   5. **Financial Details** - `desc, purpose, title, dti, delinq_2yrs, earliest_cr_line,  inq_last_6mths, mths_since_last_delinq, mths_since_last_record,open_acc,  pub_rec, revol_bal,revol_util, total_acc, initial_list_status, pub_rec_bankruptcies` 
   6. **Recovery Details** -  `out_prncp, out_prncp_inv, total_pymnt, total_pymnt_inv, total_rec_prncp, total_rec_int,
                                total_rec_late_fee, recoveries, collection_recovery_fee, last_pymnt_d, last_pymnt_amnt, next_pymnt_d, last_credit_pull_d` 
   7. **Does not contain Data** - `59 columns which do not contain any data can be dropped from the analysis -
                                     collections_12_mths_ex_med, mths_since_last_major_derog, annual_inc_joint, dti_joint, verification_status_joint, 
                                     acc_now_delinq, tot_coll_amt, tot_cur_bal,open_acc_6m, open_il_6m, open_il_12m, open_il_24m, mths_since_rcnt_il, total_bal_il, 
                                     il_util, open_rv_12m, open_rv_24m, max_bal_bc, all_util, total_rev_hi_lim, inq_fi, total_cu_tl, inq_last_12m, 
                                     acc_open_past_24mths,avg_cur_bal, bc_open_to_buy, bc_util, chargeoff_within_12_mths, delinq_amnt, mo_sin_old_il_acct, 
                                     mo_sin_old_rev_tl_op,mo_sin_rcnt_rev_tl_op, mo_sin_rcnt_tl,mort_acc, mths_since_recent_bc, mths_since_recent_bc_dlq, 
                                     mths_since_recent_inq,mths_since_recent_revol_delinq, num_accts_ever_120_pd, num_actv_bc_tl, num_actv_rev_tl, num_bc_sats, num_bc_tl,num_il_tl,num_op_rev_tl,num_rev_accts,num_rev_tl_bal_gt_0,num_sats,num_tl_120dpd_2m,num_tl_30dpd,num_tl_90g_dpd_24m,num_tl_op_past_12m,pct_tl_nvr_dlq, percent_bc_gt_75, tax_liens, tot_hi_cred_lim, total_bal_ex_mort, total_bc_limit, total_il_high_credit_limit`
   8. **Output Details** - `loan_status`
          

## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python](https://www.python.org/) - version 3.13.1
- [Matplotlib](https://matplotlib.org/) - version 3.10.0
- [Numpy](https://numpy.org/) - version 2.2.1
- [Pandas](https://pandas.pydata.org/) - version 2.2.3
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by live session of upGrad on EDA by [S Anand](https://www.linkedin.com/in/sanand0/)
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform.


## Contact
Created by @[GVChalamaReddy](https://github.com/GVChalamaReddy) and @[vikassunkad73](https://github.com/vikassunkad73)
