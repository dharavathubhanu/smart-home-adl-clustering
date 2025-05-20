 Unsupervised Learning on Smart Home Sensor Data
=============================================================

This project explores **unsupervised machine learning techniques** to recognize *Activities of Daily Living (ADL)* using smart home sensor data. The objective is to apply clustering techniques to raw binary sensor events, extract meaningful features, and visualize patterns to aid in behavioral analysis.

 Project Structure
--------------------
Project structure might look like this:

    ├── smart_home_adl_clustering.ipynb   
    ├── /data(UCI ADL Binary Dataset)                     
    ├── README.md                    

Techniques Used
-------------------

- Feature Engineering (temporal, frequency-based, transition features)
- Dimensionality Reduction:
  - PCA (Principal Component Analysis)
  - UMAP (Uniform Manifold Approximation)
- Clustering Algorithms:
  - K-Means
  - Gaussian Mixture Models (GMM)
  - Agglomerative Clustering
- Evaluation Metrics:
  - Silhouette Score
  - Adjusted Rand Index (ARI)
  - Normalized Mutual Information (NMI)



 Dataset
----------

- Dataset: Smart home sensor logs (e.g., OrdonezA, OrdonezB)
- Sensor types: PIR, Magnetic, Pressure, Flush, Electric
- Activities: Sleeping, Breakfast, Lunch, Snack, TV/Spare_Time, etc.

> Dataset Source: [CASAS Datasets](http://casas.wsu.edu/datasets/)

Results
----------

- Best clustering result: **UMAP + GMM**
    - ARI: 0.31
    - NMI: 0.46
    - Silhouette Score: 0.56

- Visualizations include:
    - Cluster scatter plots (2D)
    - Confusion matrix (aligned to labels)

Future Work
--------------

- Improve feature selection with domain-specific metrics  
- Explore deep clustering models (e.g., autoencoders + KMeans)  
- Build an interactive dashboard for cluster interpretation

 Author
---------

**Bhanu Prasad Dharavathu**  
Master’s Student in Artificial Intelligence  
Email: [dharavathubhanu340@gmail.com]

