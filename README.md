# AB_testing
- Which helps the companies to determine what options or alternatives when displayed to the users will bring better engagement
  
- different creatives similar audience

> - Existing audience - control group
> - Audiance exposed to new variation - treatment group

- Same creative different audience
> - different geo with same age
> - different age group

# ABN_testing
- one control group and more than one treatment group
- treatment group will have different variations
- EX: 3 buttons (buy now, try now, choose now)
> - 1st round - which button
> - 2nd round - which color
> - 3rd round - placement of button

# Step by step process
- objective - goal/ which metric we want to improve
- variation creation - create multiple variations, including control version
- random assignment - randomly assign different variations to users
- Experiment execution - run the experiment
- data analysis - analyze data to obtain data driven decision
- conclusion and implementation - draw conclusion based on analysis, implement and monitor ongoing performance

# Hypothesis Testing
- process of filtering from potential factors that could be responsible for an outcome to the critical list of factors that are responsible for an outcome

# Steps 
- hypothesis is an assumption
  
1. select test based on the data type and conditions
2. State null and alternative hypotheses
- there are 2 posibilities
- assumption continues to hold good
>  - we have reason to belive that assumption doesn't hold good anymore
>  - H0 - assumed to be true, unless there is evidence to consider not tru (null hypothesis)
>  - H1 - claim against the assumption
> EX: the judgment
> <img width="347" alt="image" src="https://github.com/user-attachments/assets/ffdfb354-553a-41e8-b06b-9feeee0dd82d">

> here null hypothesis is every person is innocent
> type 1 error : α alpa : false positive, person is innocent but judgment is guilty = 5% 
> type 2 error : β beeta : false negative, person is guilty but judgment is innocent = 10%
> confidence level : 1- α
> α is making wrong decission and confidence level is making write decission, we should have 95% confidence when performing hypothesis testing
>
> Why α is small?
> you can't punish innocent person even if 100 culprits go free
>
> 1 - β is power of test: determine right sample size
>
> p-value: where you actually are, calculating probability of making type 1 error
>
> if we are making an error less than alpha, we may be allow to reject the H0
> if p value < alpha - reject H0 (if p is low null is go)
> else fail to reject H0 (if p is high null is fly)

4. determine the leve of significant
5. compute test statistic /P value
6. conclude hypothesis result

# Mean
Mean = Sum of all values / Number of values

4,8,6,5,3,9

Sum of all values: 4+8+6+5+3+9=35

Number of values: There are 6 values in the dataset.

Mean = 35 / 6 = 5.83

# SD
<img width="659" alt="image" src="https://github.com/user-attachments/assets/3a77c781-9d37-4f7e-ab4b-a8ec42469340">

## one sample Z test
# Problem 1

<img width="590" alt="image" src="https://github.com/user-attachments/assets/516f8850-6ab8-4ecc-ab9c-0968f0cbd392">

This is a right tail problem when it comes to P value we should 1-value
# critical value methode
<img width="390" alt="image" src="https://github.com/user-attachments/assets/bbf1db28-062c-4047-a57b-6fe2a28ca61e">

<img width="129" alt="image" src="https://github.com/user-attachments/assets/628149d5-c699-455c-8834-818c2ef410e3">

<img width="512" alt="image" src="https://github.com/user-attachments/assets/e8cd3402-f767-4e35-a400-310870878312">

<img width="441" alt="image" src="https://github.com/user-attachments/assets/1ad0f475-1262-49a4-a8e8-59402a70e451">

<img width="376" alt="image" src="https://github.com/user-attachments/assets/68dfdc42-0ac0-4d76-8828-02282ae5cf93">

<img width="369" alt="image" src="https://github.com/user-attachments/assets/0105900a-f9b5-4e01-a0ac-1eb1bcb123db">

<img width="588" alt="image" src="https://github.com/user-attachments/assets/904a2998-6c28-4b40-8085-e560337c76a9">

# P value method 
<img width="134" alt="image" src="https://github.com/user-attachments/assets/7c324d32-ad94-4822-a258-0f63a192e3bd">

<img width="117" alt="image" src="https://github.com/user-attachments/assets/e504dae0-23f9-4f8b-97c6-a3bd92490e4f">

<img width="588" alt="image" src="https://github.com/user-attachments/assets/527fe037-6e82-4df1-a03a-7079bfa9ecb1">

# Problem 2
<img width="581" alt="image" src="https://github.com/user-attachments/assets/1b8cc352-7030-42bf-82f7-58c163886016">

This is a left tail problem when it comes to P value we don't need to minus

<img width="630" alt="image" src="https://github.com/user-attachments/assets/1d4eb8ea-eb39-49fb-8040-8cc86bad1fd2">
Here we dont know population standard deviation, so need to use sample standard deviation

<img width="498" alt="image" src="https://github.com/user-attachments/assets/55cd500f-fd5b-4b48-ba5b-273b773c491a">

<img width="541" alt="image" src="https://github.com/user-attachments/assets/231039d2-e2c2-4069-aded-28f1e32a4208">

<img width="142" alt="image" src="https://github.com/user-attachments/assets/98423053-deea-46a3-882a-d312628c8e3b">

<img width="641" alt="image" src="https://github.com/user-attachments/assets/aff4e4cb-ae77-435b-b945-2d48f6f46fa2">



















