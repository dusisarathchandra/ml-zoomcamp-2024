# Module 1

## Notes:

#### 1. Introduction to Machine Learning
- Machine learning is a process of extracting patterns from data
- Data is of two types.
    1. Features
    2. Target
- Information we know is called `features`, what we want to predict is called `target`
- `Features + Target` combination of both is used to train a model. Model encapsulates all the patterns that it finds from the data ingested to it
- We use the model to predict the data which is basically depicted as 
    `(Features + Model) ---> Predictions`


#### 2. ML vs Rule based systems
- Rule based system works better if the requirements are less complex
- As and when the new rules get added to predict an outcome, the complexity gets increased
- Machine learning outperforms rule based system if the prediction is dependent on multiple rules
- In ML, we basically start with rules and then use these rules as features.
- Example: the course talks about spam detection wherein, if the number of rules increases to detect a spam message like
    1. Domain name starts with `onlinetest.com`, `test.com`
    2. email body has `deposit` in it
    3. email subject length is greater than 20 words
    4. email subject looks suspicious - `you won a lottery`

   Rule based system makes the code complex where as an ML system just looks for patterns by marking each rule to either 1/0, making it easy to form a pattern for later use.
- Rule based system flow:
![rule-based-system-flow](./images/Rules-based-system.png)


- ML bases system flow:
![ml-based-system-flow](./images/ML-based-system.png)


Screenshots taken from course video: https://www.youtube.com/watch?v=CeukwyUdaz8&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=3


