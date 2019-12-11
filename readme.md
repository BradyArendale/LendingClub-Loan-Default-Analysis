# LendingClub Data Analysis

*Brady Arendale, Aaron Cattley, John Partee*

[LendingClub](https://www.lendingclub.com/) is a peer-to-peer lending company. Customers can apply for loans, and then investors can choose which loans to invest in based on factors such as income, credit score, and amount of debt. LendingClub assigns grades to each loan based on its own evaluation of these metrics, with worse-graded loans typically having higher interest rates.

Although a safe investment strategy would be to only invest in highly-graded loans, this also limits the potential return on investment due to the lower interest rates. Therefore, we have decided to train a model to predict whether a loan will default or not, which will give us the confidence to invest in lower-graded loans while mitigating the risk of losses.

Our analysis is divided into four parts. The first part is visualization and exploratory data analysis. In the second part, we fit various classification models to predict default status and compare them. We also train regression models to predict loan amount. We use clustering in the third part to divide applicants into groups to see what similarities they have and what differences there are between each group. Finally, we present our model's effectiveness and explain how investors and portfolio managers can invest on LendingClub using our model to achieve high ROI while minimizing risk.

The data used for this analysis is the Q2 2019 data, downloaded from [LendingClub's website](https://www.lendingclub.com/info/statistics.action) (login required).

Notebooks available for online viewing at https://nbviewer.jupyter.org/github/BradyArendale/LendingClub-Loan-Default-Analysis/tree/master/