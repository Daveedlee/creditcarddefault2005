## Progression
  1. Dataset acquired from Chicago Data Portal
  2. Exploratory data analysis has been performed
  3. Two hypotheses has been tested
  4. The findings have been presented
  5. **Further research is underway.**
  
# Introduction
-

## Datasets


## Understanding the dataset
This dataset, which seems very reasonable at first, has its riddles; the payment status(PAY_0~PAY_5)
is marked by a digit ranging from -2 to 8. To add to the confusion, the description provided by UCI's Machine
Learning repository claims that those columns have digits ranging from -1 to 8. Thankfully, the user 'ezboral' on Kaggle
reached out to the professor who created the dataset and shared the following:

"-2: No consumption;
-1: Paid in full;
0: The use of revolving credit;
1 = payment delay for one month;
2 = payment delay for two months;
 . . .;
 8 = payment delay for eight months;
 9 = payment delay for nine months and above."

Also, mfahey further clarified each digit's meaning in the comment section of the thread:
"-2 = Balance paid in full and no transactions this period (we may refer to this credit card account as having been 'inactive' this period)
-1 = Balance paid in full, but the account has a positive balance at end of the period due to recent transactions for which payment has not yet come due
0 = Customer paid the minimum due amount, but not the entire balance. I.e., the customer paid enough for their account to remain in good standing, but did revolve a balance"

Of course, this information has to be taken with a grain of salt. Nonetheless, they seem very reasonable.



## Methodology

## Metrics to consider:

## Findings
