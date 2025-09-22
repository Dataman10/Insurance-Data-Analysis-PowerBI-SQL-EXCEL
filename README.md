# Insurance Data Analysis Project

## Project Overview

This project focuses on analyzing an insurance dataset from **INSURANCE PVT. LTD.** to uncover insights related to policies, premiums, claims, and customer feedback. The analysis combines **data aggregation, visualization, and sentiment analysis** to provide a complete overview of the insurance operations and customer satisfaction.

## Key Features

* Analyze **policy distribution** by type (Auto, Health, Home, Life, Travel)
* Aggregate **Premium Amount**, **Coverage Amount**, and **Claim Amount** by different categories
* Track **claims status** (Rejected, Settled, Pending) and analyze **number of claims**
* Study **age and gender-based claim patterns**
* Count **active vs inactive policies**
* Analyze **customer feedback**, score, sentiment, and trends

## Dataset Columns

* `PolicyNumber`, `CustomerID`, `ClaimNumber`
* `PremiumAmount`, `CoverageAmount`, `ClaimAmount`
* `Number of Claims By Claims Status` (Rejected, Settled, Pending)
* `PolicyType` (Auto, Health, Home, Life, Travel)
* `Age`, `Gender`, `Age Group`
* `PolicyStartDate`, `PolicyEndDate`
* `ClaimStatus`, `ClaimDate`
* `Customer Feedback`, `Score`, `Sentiment`

## Tools & Technologies

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, NLTK/TextBlob (for sentiment analysis)
* **Techniques:** Data Cleaning, Aggregation, Exploratory Data Analysis (EDA), Visualization, Sentiment Analysis

## Analysis Highlights

* **Premium Amount by Policy Type:** Travel insurance has the highest premium amount, followed by Health and Auto.
* **Claim Amount by Age Groups:** Adults contribute the highest claim amount, followed by Elder and Young Adult.
* **Active vs Inactive Policies:** 58.13% policies are active, 41.87% inactive.
* **Claims Status Analysis:**

  * Rejected: 4.4K
  * Settled: 3.4K
  * Pending: 2.3K
* **Customer Feedback Insights:**

  * Most customers are satisfied with claim processes and policy coverage.
  * Sentiment analysis highlights areas needing improvement, such as customer support response time.

## Project Structure

```
Insurance-Data-Analysis/
│
├── data/                 # Dataset CSV files
├── notebooks/            # Jupyter notebooks with analysis code
├── visuals/              # Plots and visualizations
├── README.md             # Project documentation
└── requirements.txt      # Python libraries used
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Insurance-Data-Analysis.git
```

2. Navigate to the project directory:

```bash
cd Insurance-Data-Analysis
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the Jupyter notebook and run analysis:

```bash
jupyter notebook
```

## Author

**Hitesh Moota**
Data Analyst
📧 [hiteshdataman@gmail.com](mailto:hiteshdataman@gmail.com)
[LinkedIn](https://www.linkedin.com/in/hitesh-moota)
