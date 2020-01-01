# ML-Classification
Machine learning classification techniques to identify which is the best classifier for loan dataset
This dataset is about past loans. The __Loan_train.csv__ data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
|----------------|---------------------------------------------------------------------------------------|
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |




load a historical dataset from previous loan applications, clean the data, and apply different classification algorithm on the dataset. Using the following algorithms to build your models:
<ul>
<li>k-Nearest Neighbour</li>
<li>Decision Tree</li>
<li>Support Vector Machine</li>
<li>Logistic Regression</li>
</ul>



The results is reported as the accuracy of each classifier, using the following metrics when these are applicable:
<ul>
  <li>Jaccard index</li>
  <li>F1-score</li>
  <li>LogLoass</li>
</ul>




