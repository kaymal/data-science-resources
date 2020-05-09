# Data Analytics Methodologies


There are several Data Analytics methodologies. Three popular methodologies are "Cross-industry standard process for data mining (CRISP-DM)", "The knowledge discovery in databases (KDD) process", and Microsoft's "Team Data Science Process (TDSP)".

1. CRISP-DM

![CRISP-DM](https://barnraisersllc.com/wp-content/uploads/2018/09/CRISP_en.png)
[_CRIPS-DM_](https://barnraisersllc.com/wp-content/uploads/2018/09/CRISP_en.png)
![CRISP-DM2](https://www.actuaries.digital/wp-content/uploads/2016/07/datapic2.png)[_CRIPS-DM_](https://www.actuaries.digital/wp-content/uploads/2016/07/datapic2.png)

2. KDD

![KDD](https://www.actuaries.digital/wp-content/uploads/2016/07/datapic1.png)
[_KDD_](https://www.actuaries.digital/wp-content/uploads/2016/07/datapic1.png)

3. TDSP

![TDSP](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/media/overview/tdsp-lifecycle2.png)![TDSP2](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/media/overview/tdsp-tasks-by-roles.png)
[_TDSP_](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/media/overview/tdsp-tasks-by-roles.png)

4. Extra: Methadology mentioned in the [_R for Data Science_](https://r4ds.had.co.nz) book
![R](https://d33wubrfki0l68.cloudfront.net/795c039ba2520455d833b4034befc8cf360a70ba/558a5/diagrams/data-science-explore.png)
[_Source_](https://r4ds.had.co.nz)

5. Extra: A standard machine learning pipeline (source: [Practical Machine Learning with Python, Apress/Springer](https://link.springer.com/book/10.1007/978-1-4842-3207-1))
![Machine Learning Workflow](https://cdn-images-1.medium.com/max/1600/1*2T5rbjOBGVFdSvtlhCqlNg.png)


I have summarized the tasks within each step of CRISP-DM  below. It is worth noting that this is an **iterative** (not a linear) process. Thus, we may call this process a "Data Science Lifecyle".

_**Note:** Following list is prepared by me based on CRISP-DM. The steps might differ from use case to use case._

* Business Understanding
    - Defining Objectives - Problem Definition
    - Identifying Data Sources
* Data Understanding
    - Data collection/acquisition
    - Exploring Raw Data (Initial EDA)
        + Describing Data
        + Viewing Structure/Data Types
        + Verifying Data Quality
* Data Preparation 
    - Tidying Data (Data Wrangling) (Some sources put this into Data Understanding section)
        + Reshaping Data (melting, pivoting, etc.)
        + Splitting Cells
    - Data Preprocessing (Data Wrangling)
        + Data Cleaning (Data Cleansing in some sources)
            - Missing, Inconsistent and Noisy Data, and Outlier Analysis
            - Converting Data Types
        + Data Transformation (Manipulation)
            - Feature Engineering
            - Feature Scaling (Standardization, Normalization)
            - Feature Selection (Data Reduction)
                * Checking Correlation
                * Dimensionality Reduction (PCA, Lasso, etc.)
    - Data Exploration (EDA)
        + Summary
        + Visual
    - Sampling (If the data is big)
    - Data Splitting
    - Setting up a Pipeline 
* Modeling
    - Selecting Modeling Techniques
    - Building Model
    - Assessing Model
* Evaluation
    - Evaluating Results
    - Reviewing Process
* Deployment


