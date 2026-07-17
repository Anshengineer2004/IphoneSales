# 📱 iPhone Sales & Ratings Analysis (Flipkart India)

An interactive Exploratory Data Analysis (EDA) project that analyzes the pricing, discounts, and customer ratings of various Apple iPhone models sold on Flipkart (India). The project uses **Pandas** for data manipulation and **Plotly** for interactive visualizations[cite: 4].

---

## 📊 About the Dataset
The dataset (`apple_products.csv`) contains structured retail data for **62 unique iPhone models** with the following key attributes[cite: 4]:

* **Product Name**: The model name, color, and storage capacity of the iPhone[cite: 4].
* **Sale Price**: The actual price at which the phone is sold on Flipkart[cite: 4].
* **Mrp**: Maximum Retail Price (Original price before discount)[cite: 4].
* **Discount Percentage**: The discount percentage offered on the model[cite: 4].
* **Star Rating**: Average customer rating out of 5 stars[cite: 4].
* **Number Of Ratings**: Total number of ratings given by customers[cite: 4].
* **Number Of Reviews**: Total number of text reviews written by users[cite: 4].
* **Ram**: System memory of the device (e.g., 2 GB, 4 GB)[cite: 4].

---

## ⚙️ Key Steps Performed in the Notebook

### 1. Data Loading & Inspection
* Loaded the dataset using Pandas and displayed the initial records to understand the structure[cite: 4].
* Analyzed the data types and shape of the dataset (62 rows, 11 columns)[cite: 4].

### 2. Data Cleaning & Integrity Check
* **Missing Values**: Checked for null values across all columns and found **0 missing values**[cite: 4].
* **Duplicate Records**: Checked for duplicate rows and found **0 duplicate entries**, ensuring a highly clean dataset[cite: 4].

### 3. Descriptive Statistics (`df.describe()`)
* **Average Selling Price**: The average sale price of an iPhone in this dataset is approximately **₹80,073**[cite: 4].
* **Discounts**: Apple products offer an average discount of **~10%**, going up to a maximum of 29%[cite: 4].
* **Customer Satisfaction**: iPhone ratings are exceptionally high, with a minimum rating of **4.5** and a maximum rating of **4.7**[cite: 4].

---

## 📈 Key Insights & Findings

* **The Top Rated Models**: The **iPhone 11 Pro Max** series (in Gold, Midnight Green, and Space Grey) holds the peak position as the highest-rated phone with a **4.7-star rating**[cite: 4].
* **Highly Popular Mid-Rangers**: The **iPhone XR (128 GB)** and **iPhone 8 Plus** are highly popular choices among consumers, maintaining a solid **4.6-star rating**[cite: 4].
* **Consistent Quality**: No data imputation or cleaning of duplicates was required as the raw Flipkart dataset was already clean and consistent[cite: 4].

---

## 🛠️ Tech Stack Used

* **Language**: Python 3[cite: 4]
* **Environment**: Google Colab / Jupyter Notebook[cite: 4]
* **Libraries**:
  * `pandas` & `numpy` (Data Preprocessing & Stats)[cite: 4]
  * `plotly.express` & `plotly.graph_objects` (Interactive Data Visualizations)[cite: 4]

---

