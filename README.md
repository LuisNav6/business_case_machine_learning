### README for the Repository: **Audiobook Purchase Prediction**

# 🎧 **Predicting Customer Purchases for an Audiobook App**  
🚀 *Focusing efforts on customers with the highest conversion potential*

---

## 🧠 **Problem Description**  
This project leverages a *Machine Learning* model to predict whether a customer of an audiobook app will make another purchase within the next 6 months, based on their behavior over the past 2 years.

🎯 **Why is this important?**  
1. **Resource optimization**: Avoid unnecessary spending on advertising to customers with a low likelihood of returning.  
2. **Target key customers**: Identify and prioritize customers with a high probability of conversion.  
3. **Create value**: Uncover key metrics that drive loyalty and repeat purchases.  

---

## 📋 **Data Description**  
The data is provided in a `.csv` file containing relevant information about users and their interaction with the app.

### 📂 **Input Variables (Features)**  
- **Customer ID**: Unique identifier (excluded from the model).  
- **Book length in mins_avg**: Average length of purchased audiobooks.  
- **Book length in mins_sum**: Total length of purchased audiobooks.  
- **Price paid_avg**: Average price paid for audiobooks.  
- **Price paid_sum**: Total price paid for audiobooks.  
- **Review (Boolean)**: Indicator of whether the customer left a review.  
- **Review (out of 10)**: Average review score (1 to 10).  
- **Total minutes listened**: Total listening time.  
- **Completion**: Average percentage of books completed (0 to 1).  
- **Support requests**: Number of support tickets submitted.  
- **Last visited minus purchase date (in days)**: Days between the last visit and the last purchase.  

### 🎯 **Output Variable (Target)**  
- **Will Buy Again**:  
  - `1`: The customer will purchase again.  
  - `0`: The customer will not purchase again.  

### 📅 **Evaluation Period**  
- **Inputs**: Data from the past **2 years**.  
- **Prediction**: Conversion within the next **6 months**.  

---

## 🛠 **Project Goal**  
Develop a binary classification algorithm to predict whether a customer will make a repeat purchase.

### 💡 **Applications**  
1. Customer segmentation for advertising campaigns.  
2. Analysis of key metrics for customer retention.  
3. Prioritization of retention and loyalty strategies.  

## 🚀 **Getting Started**  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/LuisNav6/business_case_machine_learning.git
   cd business_case_machine_learning
   ```
2. **Install dependencies**  
   ```bash
   pip install numpy tensorflow scikit-learn
   ```
3. **Train the model**  
   Ensure the data is in the folder and run:  
   ```bash
   python TensorFlow_Audiobooks_Preprocessing_with_commments.ipynb
   python TensorFlow_Audiobooks_Preprocessing_Exercise_Solution.ipynb
   ```
4. **Make predictions**  
   Use new data with:  
   ```bash
   python TensorFlow_Audiobooks_Machine_Learning_with_comments.ipynb
   ```

---

## 📊 **Technologies Used**  
- **Language**: Python  
- **Libraries**:  
  - `numpy`: Data processing.  
  - `scikit-learn`: Modeling and evaluation.  
  - `tensorflow`: Make predictions.  

---

## 💡 **Expected Outcomes**  
- **Key insights**:  
  - Identification of customers with high conversion potential.  
  - Key metrics influencing repeat purchases.  
- **Business impact**:  
  - Savings on advertising campaigns.  
  - Improved retention and loyalty strategies.  

---

## 🧑‍💻 **Author**  
Developed with passion by Luis Navarrete.  
📧 **Contact**: luishnb4@gmail.com  

---

## ⭐ **Contribute**  
If you find this project useful, feel free to ⭐ it on [GitHub](https://github.com/LuisNav6/business_case_machine_learning). Your support makes a difference! 🚀
