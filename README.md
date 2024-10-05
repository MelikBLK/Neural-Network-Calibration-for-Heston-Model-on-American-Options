# 📈 **Neural Network Calibration for Heston Model on American Options**

---

## 📝 **Project Overview**

This project focuses on calibrating the **Heston Stochastic Volatility Model** using neural networks for American options. The goal is to apply deep learning techniques to effectively calibrate the model, improving its accuracy in pricing American options, where early exercise is possible.

---

## 🎯 **Objectives**

- 🔍 Implement the Heston Model for option pricing, focusing on American options.
- 🧠 Calibrate the model using neural networks to enhance predictive accuracy.
- 🛠️ Explore preprocessing techniques and hyperparameters for better calibration.
- 📊 Compare different calibration methods and measure improvements in option pricing.

---

## 📂 **Dataset**

The dataset for this project is based on **AAPL option chains** from **Q1 of 2016 to Q4 of 2020**. These options data include key information required for calibrating the Heston model, such as strike prices, expiration dates, and implied volatilities.

You can also find extended datasets, including **AAPL option chains from Q1 2021 to 2023**. However, due to their large size, I wasn't able to upload them directly in the repository. Instead, you can find a **Link to datasets.txt** file that redirects you to the kaggle page, from where I download the datasets.

⚠️ **Note:** You need to update the dataset path in the code to point to the location where the dataset is stored on your local machine. Modify the following line in the notebook:

```python
raw_df = pd.read_csv(r"C:\Users\msi\Desktop\Senior_Semester2\ISS Senior Project\Code\aapl_2016_2020.csv")
```

Change the file path `r"C:\Users\msi\Desktop\Senior_Semester2\ISS Senior Project\Code\aapl_2016_2020.csv"` to the path where your dataset is located on your machine.

---

## 📊 **Model Implementation**

- The **Heston Model** is used for pricing American options.
- A **Neural Network** is trained to calibrate the model, improving its parameter fitting.
- Multiple models are tested, and their performance is evaluated based on how well they predict option prices.

---

## 🔧 **Technologies Used**

- **Python**: Programming language.
- **NumPy** and **Pandas**: Data handling and preprocessing.
- **Scikit-learn**: Machine learning library for model training and evaluation.
- **Matplotlib**: Visualization of results.

---

## 📂 **Installation**

1. Clone the repository:

   ```bash
   git clone https://github.com/MelikBKL/Neural-Network-Calibration-for-Heston-Model-on-American-Options.git
   ```

2. Install the required Python libraries:

   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```

---

## 📫 **Contact**

Feel free to reach out for any questions or suggestions:

- [LinkedIn](https://www.linkedin.com/in/melik-belkhiria)
- [Email](mailto:belkhiria.melik02@gmail.com)
