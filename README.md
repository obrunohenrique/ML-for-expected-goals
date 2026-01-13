# Football xG Predictor: A Comparative Machine Learning Analysis

This repository features a comprehensive study on calculating **Expected Goals (xG)** for football shots using **StatsBomb Open Data**. The project explores various Machine Learning architectures to determine the most effective approach for predicting the probability of a shot resulting in a goal.

## 🚀 Project Overview

The goal of this project is to model the likelihood of goal scoring based on event-level data. By processing spatial and contextual features of thousands of shots, we built a pipeline that evaluates different mathematical approaches to the xG problem.

### Key Results
After benchmarking several models of different natures, the **Logistic Regression** model emerged as the best performer, providing the most reliable balance between interpretability and predictive accuracy (AUC-ROC/Log-Loss).

---

## 📂 Repository Structure

The project is organized into two main modules:

* **`/dataset`**: Contains the Google Colab notebooks dedicated to data science. This includes data extraction from the StatsBomb API, cleaning, feature engineering, and final dataset preparation.
* **`/models`**: Contains individual notebooks for each trained model. Each notebook includes the training, testing, and evaluation metrics for a specific algorithm, allowing for a transparent comparison between them.

---

## 🛠️ Technologies Used

The project was built using the standard Python Data Science stack:
* **Data Handling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn, XGBoost (e outros modelos testados)
* **Data Source:** [StatsBomb Open Data](https://github.com/statsbomb/open-data)

---

## 👥 The Team

This project was developed as a collaborative group effort. Connect with the contributors:

* **[Bruno Henrique]** - [GitHub Profile Link](https://github.com/obrunohenrique)
* **[Mateus Riff]** - [GitHub Profile Link](https://github.com/mateusriff)
* **[Pedro Stelzer]** - [GitHub Profile Link](https://github.com/pedroStelzer)
* **[Paulo Emílio]** - [GitHub Profile Link](https://github.com/paulogestosa)
* **[Thiago Felipe]** - [GitHub Profile Link](https://github.com/thiago-felipe-de-franca)

---

## 📝 License

This project utilizes StatsBomb's free data. Please ensure compliance with their [User Agreement](https://statsbomb.com/resource-centre/statsbomb-data-user-agreement/) when using this repository.
