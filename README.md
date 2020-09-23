# Loan Data Analysis - Borrower's APR 


### Dataset

The Loan Dataset studied in this analysis contains 113,917 loan records. Each record has serveral attributes such as Borrower's APR, Employmnet Status, Loan amount, Debt to Income Ration, Prosper Rating, etc. This study focuses on analyzing the key attribue - Borrower's APR and what loan related factors impact or influence this key attribute and how significantly it gets influenced. <br><br>

Before beginning the analysis, the data was slightly wrangled to eliminate records that do not have a Borrower's APR rate, as this is our main attribute of interest. Several other attributes, not required for further analysis were also discarded from the dataset. At a later point, records with Monthly Income over 30k were found to be a very minimal number and were eliminated too, for better results.<br><br>

The original dataset can be downloader from here: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv<br>

### Summary of Findings<br>

The attributes taken into consideration for studying Borrower's APR rate were: Loan Amount, Monthly Income, Employment Status, Term, Prosper Score and Prosper Ratings. <br><br>

From the analysis, we can conclude that Borrower APR rate is negatively correlated to all the numeric attributes. Loan Amount and Monthly Income impact Prosper Score and Prosper Rating. It turns out that Prosper Score has the strongest negative correlation to Borrower API. The analysis summarizes that borrowers with a higher Prosper Score(0-11) or Prosper Rating(AA-HR) are generally more reliable as they have better monthly income, have a better overall credit standing and are definitely employed or self-employed, and hence they have lower APR rates. <br><br>


### Key Insights for Presentation<br>

The presentation is just focused on features that impact our key attribute of interest - Borrower APR. It starts off by showing the visual relationship between Borrower APR and Prosper Score followed by Loan Amount, Monthly Income. Relationship between APR and Employment Status is also analyzed. Next, how each indiviudual Prosper Rating affects APR rate is observed. Loan Term is then added on to study how this additional attribute impacts the APR rates.<br>
