## 🧰 Tools & Libraries Used
- Python  
- Pandas  
- NumPy
- matplotlib.pyplot
- Jupyter Notebook

---

## 🔍 Analysis Workflow

### 1. Data Loading & Inspection
- Imported required libraries & Loaded the dataset
  
  ![image](1.png)
  
- Checked data types, missing values, and general statistics
  
  ![image](2.png)


### 2. Data Cleaning
- Handled missing values using median and logical defaults & Removed unnecessary columns

  ![image](3.png)
  
- Created a unified agent full name column & Standardized text columns

  ![image](4.png)

### 3. Feature Engineering
- Converted categorical Yes/No columns to numerical values

  ![image](5.png)                           ![image](5..png)


  
- Created call duration categories & Grouped customer ages into meaningful age groups

  ![image](6.png)                          ![image](6..png)

- Reordered columns for better readability

  ![image](7.png)

### 4. Exploratory Data Analysis (EDA)
The analysis answers key business questions such as:
- What are the main reasons for call abandonment?

  ![image](8.png)
  
- Which products have the highest failure rate?

  ![image](9.png)

- Which products require more follow-up calls?

  ![image](10.png)

- Do repeat customers require more follow-ups?

  ![image](11.png)

- Is there a relationship between call outcome and time of day?

  ![image](12.png)

---

## 📊 Key Insights
- Long wait time is the primary reason for call abandonment
- Certain products show higher failure and follow-up rates
- Repeat customers tend to require fewer follow-up calls
- Call outcomes vary depending on the time of day

---

## 📁 Output
- A cleaned and structured dataset ready for further analysis or visualization:
  - `call_center_cleaned.csv`
