# Data-Mining-255
Dataset : https://making.lyst.com/lightfm/docs/_modules/lightfm/datasets/stackexchange.html

It is a stackexchange dataset consists of user-question interaction and question and tags item features

### Objective : Use state of art libraries for Approximate nearest neighbor search for a  data set

1. Install the required libraries like faiss,annoy,LightFM etc.
2. Retrieve the dataset using fetch_stackexchange() and model it using LightFM to create a vector embedding of item and features.
3. Open a pickle file in writing mode and store the feature labels, vector and item features, so that it can be used again without re-loading
4. Load the data from the pickle file to work with it.
5. Created a function to retrieve the tags of a question based on question id
6. A class is created for each algorithm. The class have a get_similar_tagged_questions function to get similar tags for a particular vector. We can see the ouput below. The output shows 12 question id's which are similar to the input and their corresponding tags. The output is shown below for Exhaustive Search.
```
{'question_id:0': ['bayesian', 'prior', 'elicitation'],
 'question_id:14826': ['bayesian', 'elicitation', 'r'],
 'question_id:17409': ['bayesian', 'modeling', 'hierarchical-bayesian'],
 'question_id:29382': ['bayesian',
  'prior',
  'elicitation',
  'regression',
  'hyperparameter'],
 'question_id:29552': ['bayesian', 'prior', 'elicitation'],
 'question_id:32951': ['bayesian', 'prior'],
 'question_id:45542': ['bayesian', 'prior', 'elicitation'],
 'question_id:53448': ['bayesian', 'prior'],
 'question_id:60904': ['bayesian', 'prior'],
 'question_id:62277': ['bayesian', 'prior', 'optimization'],
 'question_id:65706': ['bayesian', 'prior'],
 'question_id:71861': ['bayesian', 'prior']}
 ```
7. Conclusion
```
 HNSW and Exhaustive search have a similar output.

Product Quantization and LSH have a similar output.

Tree and Graphs output is different from others.
```
