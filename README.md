# Software Bug Prediction
_Note: Download the ML_porject.html file and open it with the brower for smoother and easier project browsing. And for better visuals_
### Dataset:
The dataset is collected at the University of Geneva in Switzerland related to the bug prediction dataset. It contains data about the following software systems:
    - Eclipse JDT Core
    - Eclipse PDE UI
    - Equinox Framework
    - Lucene
    - Mylyn
    
### Objective:
Software success depends heavily on the ability of maintaining the software and ensuring that the software is released with minimal number of issues. Knowing in advance an estimation of possibile bugs in the software will mitagate some of the risks after the software is released. Our main objective is to be able to predict in advance the number of bugs in the software using the software data itself such as the number of lines of code, number of methods, number of attributes, and other important software properties. This is an overview of our objectives in details:
- Data Analysis
- Data preprocessing
- Data visualization
- Advanced EDA and visulaization using ML/D-reduction algorithms
- hyper-parameter tuning and solving the imbalance problem
    - Classifying data where the classes are: no bugs, 1 bug, or > 2 bugs
    - Classifying data where the classes are: no bugs, > 0 bugs

### Outline:
- import
- data cleaning
- EDA and visualization
    - descriptive statistics
    - correlation matrix
    - feature importance (Lasso)
    - feature importance (RFC)
    - kernal density estimation
    - 3D scatter cross plots
    - UMAP dimensionality reduction
    - PCA dimensionality reduction
    - clustering analysis
   
   
- Base Line Classifier
    - Accuacy
    - ROC
    - F-1 Score
    - Confusion Matrix
    - Area Under the Curve of ROC Viz
    
    
- first stage modeling
    - hyper-parameter tuning model optimization
    - dimensionality reduction
    
    
- evaluation
    - Accuacy
    - ROC
    - F-1 Score
    - Confusion Matrix
    - Area Under the Curve of ROC Viz
    
    
- second stage modeling (data-driven model optimization to tackle imbalance)
    - Under Sampling
    - Over Sampling
    - Feature Selection


- evaluation
    - Accuacy
    - ROC
    - F-1 Score
    
    
- models quality metrics table
    - Multi
        - Accuacy (All and Best)
        - ROC (All and Best)
        - F-1 Score (All and Best)
    - Binary
        - Accuacy (All and Best)
        - ROC (All and Best)
        - F-1 Score (All and Best)
