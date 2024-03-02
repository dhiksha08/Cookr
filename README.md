## Cookr Hackathon 2024

### Introduction 
 <p> In this gitHub repository, the solution for Cookr Hackathon 2024 is presented for Problem statements 1 and 3. </p>

 ### Problem Statement 1:
 #### Problem description
<p> Create a model or research the necessary steps to create a model for
categorizing items. When the cook adds an item to their kitchen, it should be automatically
categorized into multiple categories. We can provide the sample data for this to train the model.</p>

 #### Approach
 <p>In this problem statement, a food item is given as input, for which categories has to be generated. This is modelled as a multi-class classification problem. The datset is generated using bulkGPT from a dataset available in Kaggle which contains multiple food items, whose ingredients were obtained through EDAMAM api.This dataset is then vectorised using term frequency inverse document frequency method(tfidf) and then various machine learning models such as multinomial naive bayes for multi-label classification and multinomial logistic regression for categories with single label field. The categories are translated as a one Hot vector. Label power set method is used to do multi-label classification in naive bayes.</p>

### Problem Statement 3:
#### Problem description
<p> Create AI models or research the necessary steps to create AI models
that can predict potential failures or issues in infrastructure components (e.g., servers,
networks) based on historical data. This could help DevOps teams proactively address issues
before they cause downtime or performance degradation.</p>

#### Approach
<p>Various research papers and some blogs in the internet has been referenced to create a comprehensive report about predictive maintenance and prediction of component failure. Using historical log files, it is possible to extract some features which can be used to perform analysis and create machine learning models, which can be used to predict system failure.</p>
