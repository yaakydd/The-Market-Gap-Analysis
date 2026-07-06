### A. The Executive Summary
* The biggest gap is in Sweet Snacks & Desserts. Out of 1,116 products in that category, only 0.99% are both low in sugar and high in protein as compared to 74.5% in Meat & Seafood, though that's not a fair comparison since meat is naturally high in protein. A new product should aim for around 16.1g protein and under 0.9g sugar per 100g, matching what already works in the market. A separate check using Nutri-Score backs this up: 60% of products in this category score a D or E.

### B. Project Links
* **Link to Notebook:** (https://colab.research.google.com/drive/1h_71VdhYbVgOSLs9191BgxgYJCH2VRUH?usp=sharing)
* **Link to Dashboard:** (https://app.powerbi.com/view?r=eyJrIjoiZTUyNWU0YmQtYTFjZi00OWRlLTkzMTctYTYxNDQ1NjNkMzA0IiwidCI6IjEwNGQ4MDQ4LWZkMGMtNDNkNS1hNjMwLWZjNjI5ZTVkYWI1OSJ9).
* **Link to Presentation:** (https://knustedugh-my.sharepoint.com/:p:/g/personal/yaantwi1_st_knust_edu_gh/IQDVIqdD5D-PT7oqQQFAeTgSAWuul5TxJCzuYVfn6DJK5ZY?e=ABTBjI)

### C. Technical Explanation
* Briefly explain how you handled the "Data Cleaning".
* I dropped rows missing values for key information like product name, sugar, protein, or category, since those are essential for the analysis. I also filtered out impossible values, such as sugar or protein above 100g per 100g, or negative numbers. Lastly, I checked that sugar never exceeded total carbohydrates, since sugar is technically part of carbohydrate and shouldn't be higher than it.
* 
* Explain your "Candidate's Choice" addition.
* For my Candidate's Choice addition, I decided to add a Nutri-Score ratings for Sweet Snacks & Desserts. I picked this because it's a well-known, external rating and it doesn't depend on my own sugar/protein cutoffs. It confirmed what I'd already found out that 60% of products scored a D or E.


