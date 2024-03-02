## Cookr Hackathon 2024

### Introduction 
 <p> In this gitHub repository, the solution for Cookr Hackathon 2024 is presented for Problem statements 1 and 3. </p>

 ### Problem Statement 1:
 #### Introduction and problem description
<p> Create a model or research the necessary steps to create a model for
categorizing items. When the cook adds an item to their kitchen, it should be automatically
categorized into multiple categories. We can provide the sample data for this to train the model.</p>

 #### Approach
 <p>In this problem statement, a food item is given as input, for which categories has to be generated. This is modelled as a multi-class classification problem. The datset is generated using chatGPT from a dataset available in Kaggle which contains multiple food items, whose ingredients were scrapped from Archana's kitchen website. This dataset is then vectorised using term frequency inverse document frequency method(tfidf) and then various machine learning models such as multinomial naive bayes for multi-label classification and multinomial logistic regression for categories with single label field. The categories are translated as a one Hot vector. Label power set method is used to do multi-label classification in naive bayes.</p>

 
