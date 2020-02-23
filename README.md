# BreastCancerDiagnosis

## Presentation:
https://docs.google.com/presentation/d/1vrJn5TcE7WsW7bjVI7g2B3VJBYJMcyHkxvnuOkhQ5vE

### Stakeholder:
Breast Cancer Clinics.

#### Impact on stakeholder:
Clustering pacients into benign or malignant groups will allow preprocessing of digitized image of a fine needle aspirate (FNA) of a breast mass before setting diagnosis. This can help doctors to make correct diagnosis and react sooner for patients with potentially malignant illness, which may save lives.

### Research Objective:
Following [dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) contains features that are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass and diagnosis. Features describe characteristics of the cell nuclei present in the image and can be used as a data for clustering.  
  
Research will be focused on investigating data for quantity of potential clusters (it may be more than two, even despite only two types of diagnosis are present in a dataset, since there can be subtypes of diagnosis). After this, natural continuation of research will be to find clusters.  
  
Firstly, unsupervised learning clusterisation will be used to find clusters based on features. Next, clusters will be checked on which diagnosis they have. Those clusters can be used to investigate whether data can be effectivly clustered with unsupervised learning.  
  
Next, supervised learning algorythm will be used to create clustering that can predict whether patient has benign or malignant breast cancer.  
  
For all types of clustering custom functions will be created.  
