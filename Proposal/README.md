# Bank Churners
In this project the main thing is to predict between credit card and customers in general by using classification models for example :a manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction.

# Dataset Description:
This data has *10127 rows and 23 columns.*, This dataset can be found at [Kaggle](https://www.kaggle.com/sakshigoyal7/credit-card-customers).



| Num | Command | Description |
| --- | --- | --- |
| 1  | CLIENTNUM |  which is a client number. Unique identifier for the customer holding the account |
| 2  | Attrition_Flag | which is an internal event (customer activity) variable - if the account is closed then 1 else 0 |
| 3  | Customer_Age | which is a demographic variable - Customer's Age in Years |
| 4  | Gender | which is a demographic variable - M=Male, F=Female |
| 5  | Dependent_count | which is a demographic variable - Number of dependents |
| 6  | Education_Level | which is a demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)  |
| 7  | Marital_Status | which is a demographic variable - Married, Single, Divorced, Unknown |
| 8  | Income_Category | Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown) |
| 9  | Card_Category | which is a product Variable - Type of Card (Blue, Silver, Gold, Platinum) |
| 10 | Months_on_book | Period of relationship with bank |


#### The sample of data is shown in the following table:

<table width="100%">
 <tr>
  <th>CLIENTNUM</th><th>Attrition_Flag</th><th>Customer_Age</th><th>Gender</th><th>Dependent_count</th><th>Education_Level</th><th>Marital_Status</th><th>Income_Category</th><th>Card_Category</th>
 </tr>
 <tr>
  <th>768805383</th><th>Existing Customer</th><th>45</th><th>M</th><th>3</th><th>High School</th><th>Married</th><th>60K-80K</th><th>blue</th>
 </tr>
</table>





## Tools
- Jupyter
- Python
- Pandas
- Numpy
- Seaborn
- Scikit learn
- Zoom



## Questions that needs to be answered:

- What is the most Income Category based on Attrition Flag?
- Is the Education Level affect on the Income Category?
- Does `Customer_Age` influnce the `Marital_Statu?
- Which income category can be types with card category?

## Authors:
- [@msealadwani](https://github.com/msealadwani)
- [@Yazeed-11](https://github.com/Yazeed-11)
- [@MahaAlHarqan](https://github.com/MahaAlHarqan)
- [@Moha0014](https://github.com/Moha0014)
