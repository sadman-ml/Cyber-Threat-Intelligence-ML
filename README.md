#Cybersecurity Threat Analysis & ML

A comprehensive Machine Learning pipeline designed to analyze and predict cybersecurity threats using data from 2015 to 2024. This project automates preprocessing, model selection, and evaluation across multiple threat dimensions.

##Key Features
* **Multi-Target Analysis:** Predicts *Attack Type*, *Vulnerability*, *Financial Loss*, and *Resolution Time*.
* **Model Comparison:** Evaluates **24 models** (including Random Forest, Gradient Boosting, SVM, and KNN) to identify the best fit for each target.
* **Automated Pipeline:** Streamlined Label Encoding, Feature Scaling, and Model Serialization.
* **Data Insights:** Visualizes **Feature Importance** to identify key risk drivers for different types of cyber attacks.

##Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-Learn
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib, Plotly

##Summary of Results
* **Classification:** Ensemble methods like **Random Forest** showed high accuracy in identifying Attack and Vulnerability types.
* **Regression:** Factors like **Affected Users** and **Resolution Time** were found to be the strongest predictors of threat severity.
* **Deployment Ready:** All best-performing models and scalers are saved as `.pkl` files for easy integration.

##How to Run
1. **Clone this repository** to your local machine or Google Colab.
2. **Upload the dataset:** Ensure `Global_Cybersecurity_Threats_2015-2024.csv` is in your environment path.
3. **Execute the Notebook:** Run the `.ipynb` file to reproduce the training process and visualizations.

##Author
**Sadman Ahmed**
#
## ⭐ Show Your Support
If you find this project helpful or interesting, please give it a **Star**! It helps others discover the work and keeps me motivated to build more.
