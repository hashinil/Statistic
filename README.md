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

