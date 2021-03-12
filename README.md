# Graph-Recommendations
This repository contains the implementation of graphs-based models to make recommendations using link prediction techniques. These models are useful when we need to generate recommendations, but we have not sufficient knowledge to use classical techniques such as collaborative filtering or content-based systems. 
We have several folders in the repository:
- **models-notebooks** contains the implementation of the models proposed and the evaluation performed. There are eight notebooks, four of them corresponding to the items-based approaches and the other four to the user-based approaches. Each one of these four implementations is different for each aggregation method proposed.
- **aux-notebooks** contains several auxiliary notebooks to get and analyse the datasets used in the evaluation.
- **data** contains the datasets used in the evaluation: 
    - original MovieLens 100K dataset; 
    - datasets with the 200 most popular films and users that have interacted with at least 50%, 25% and 12.5% of these popular films, respectively;
    - items chosen randomly for the evaluation;
    - training sets and test sets for each user in every experiment.  
- **results** contains the scores obtained in the evaluation:
    - raw is the folder where we keep the results got from the notebooks
    - best-results-k10.xlsx summarises the best results obtained for k = 10.
    - results.xlsx and results.csv keeps all the results in one sheet to be filtered and analysed.
    
