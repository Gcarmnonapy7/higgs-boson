Higgs Boson Discovery: Machine Learning Project

This project explores the ATLAS Higgs Boson Machine Learning Challenge dataset from CERN, originally hosted on Kaggle. The objective is to predict the presence of the elusive Higgs boson particle using simulated particle collision data.
Project Overview

Using Python, I performed exploratory data analysis (EDA), preprocessing, and built several machine learning models to classify events as signal (likely Higgs boson) or background noise.

This project is not intended for competition submission, but rather as a personal study in applying ML techniques to high-energy physics data.
Dataset

The dataset contains 30 low-level and high-level physics features derived from proton collision experiments. Each row represents an event, with:

    Measured properties of particles such as leptons and jets,

    Derived quantities like transverse momentum and invariant mass,

    A Label column (only in the training set) indicating signal (s) or background (b).

Missing values are represented by -999.0, and were handled using feature-dependent imputation strategies (e.g., median, KNN, or removal depending on missing rate).
 ML Workflow

    Data cleaning and imputation of missing values

    Exploratory data analysis with matplotlib and seaborn

    Feature engineering and dimensionality checks

    Model selection and training (Random Forest, XGBoost, LightGBM)

    Evaluation using metrics such as Accuracy, AUC, and AMS (Approximate Median Significance, physics-specific)

 Goals

    Apply real-world machine learning workflows on physics datasets

    Understand feature importance and physical meaning of input variables

    Practice preprocessing large-scale noisy datasets

    Create reusable ML pipelines

 Tech Stack

    Python (Pandas, NumPy, Scikit-learn, XGBoost, LightGBM)

    Matplotlib & Seaborn for visualizations

    Jupyter Notebooks for analysis and documentation
