# Data-Mining-255
Link to dataset : https://drive.google.com/drive/u/1/folders/1zCTTgGxLxQZzX8_f4ZXnlWtwNA7jS5Oa

Link to colab : https://colab.research.google.com/drive/1UNUIKcS-RQn1rXkVGjH93mFE2kI51_d0?authuser=1#scrollTo=YlhCTrOkSNy5&uniqifier=1

The dataset consists of medical records of people which helps them into cluster into whether they have a heart disease or not.

### Objective : Implement various clustering algorithms in colabs

1. First the data is analysed to understand different columns. This would help in understanding relation between columns and how needs to be cleaned.
2. The data is visualized using different plots against different columns.
3. Since the data has 12 columns, the dimensions are reduced to 2 using PCA.2 PCAs covered 90% variance.

![Image Dataset](https://github.com/poojakota17/Data-Mining-255/blob/Clustering/PCA.PNG)

4.kmeans algorithm is applied from scratch.

![Image Dataset](https://github.com/poojakota17/Data-Mining-255/blob/Clustering/k-1.PNG)

5. GMM clustering is performed and the resulting clusters are shown below.

![Image Dataset](https://github.com/poojakota17/Data-Mining-255/blob/Clustering/k-2.PNG)

6. Heirarchical clustering is performed and the dendoograms are shown below.

![Image Dataset](https://github.com/poojakota17/Data-Mining-255/blob/Clustering/k-3.PNG)

![Image Dataset](https://github.com/poojakota17/Data-Mining-255/blob/Clustering/k-4.PNG)

7. DBSCAN clustering is performed and the resuts are below.

![Image Dataset](https://github.com/poojakota17/Data-Mining-255/blob/Clustering/k-5.PNG)

8. Results : The best algorithm for this dataset was kmeans with more SSE score and less Davies-bouldin score.

![Image Dataset](https://github.com/poojakota17/Data-Mining-255/blob/Clustering/clust_res.PNG)

