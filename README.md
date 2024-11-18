## Project Overview

The rapid adoption of Electric Vehicles (EVs) in India presents an exciting opportunity to analyze sales trends and market dynamics. This project provides a detailed analysis of EV sales data across various states, exploring insights such as top-selling states, popular vehicle types, and category preferences. By leveraging Python and data visualization, this project aims to assist businesses and policymakers in making informed decisions for the EV sector.

---

## Dataset Description

The dataset used in this project contains **96,846 rows** and **8 columns**, providing a comprehensive overview of EV sales in India. The dataset has been preprocessed to remove null values and duplicates, ensuring data integrity for accurate analysis.

### Key Columns:
- **State**: The state where the EV sales occurred.
- **Vehicle Type**: Type of EV (e.g., 2-Wheeler, 3-Wheeler, 4-Wheeler).
- **Vehicle Class**: Specific class of EV (e.g., E-Rickshaw, Motorcycle).
- **Category**: Usage category of the vehicle (e.g., Passenger, Goods).
- **Sales Quantity**: Number of EVs sold.

---

## Key Findings

### 1. State-Wise EV Sales
- **Top 3 States**: 
  1. Uttar Pradesh
  2. Maharashtra
  3. Karnataka
- These states show the highest EV adoption rates, driven by supportive policies and demand.
- ![image](https://github.com/user-attachments/assets/a3ba35aa-dbc5-4856-91b2-d4bedd0f0fa9)

  
### 2. EV Sales by Vehicle Class
- **E-Rickshaw Passenger** leads as the most sold vehicle class.
- Followed by **Motorcycles & Scooters**.
- **E-Rickshaw with Cart** ranks third in popularity.
- ![image](https://github.com/user-attachments/assets/8af3b85d-1d55-4f49-863f-cdfaede73514)


### 3. EV Sales by Vehicle Category
- **3-Wheelers** dominate the market, followed by **2-Wheelers** and **4-Wheelers**.
- ![image](https://github.com/user-attachments/assets/4ba74a44-d6c1-4cd2-83b2-99e69afb507b)


### 4. Most Sold EV Types
- **Three-Wheeler (Shared, Low Speed)** is the most popular vehicle type.
- **Two-Wheeler (Personal)** is the second-most sold category.
- **Three-Wheeler (Goods, Low Speed)** ranks third.
- ![image](https://github.com/user-attachments/assets/17343e6a-c1c7-4e4c-8a82-9b47ee7288f6)


---

## Tools and Technologies

The project leverages the following tools and technologies:

- **Python**: 
  - **Pandas**: For data manipulation and cleaning.
  - **NumPy**: For numerical operations.
  - **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: Interactive environment for documenting and executing the analysis.
- **Git**: Version control system for project management.

---

## Project Workflow

1. **Data Collection**: The dataset was sourced from a reliable repository.
2. **Data Cleaning**: 
   - Removed null values and duplicates.
   - Ensured data consistency for analysis.
3. **Exploratory Data Analysis (EDA)**:
   - Conducted state-wise, vehicle class, and category analysis.
   - Visualized trends using bar graphs and pie charts.
4. **Insights & Recommendations**:
   - Derived actionable insights for businesses and policymakers.
5. **Documentation**:
   - Created this README file to explain the project workflow and findings.

---

## How to Use This Repository

### Prerequisites
- Python (version 3.7 or higher)
- Jupyter Notebook
- Required Python libraries (listed below)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ev-sales-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ev-sales-analysis
   ```

3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Run the `EV_Sales_Analysis.ipynb` notebook to explore the analysis.

---

## Insights & Recommendations

### Insights:
1. **Market Focus**: States like Uttar Pradesh, Maharashtra, and Karnataka are key markets for EVs.
2. **Vehicle Type Trends**: 3-Wheelers dominate the market, indicating a strong demand in shared and goods transport.
3. **Growth Potential**: Increasing sales of low-speed vehicles highlight the potential for urban and rural adoption.

### Recommendations:
1. **Infrastructure Development**: Focus on building EV charging stations in high-adoption states.
2. **Product Strategy**: Invest in 3-Wheeler and 2-Wheeler segments to capture more market share.
3. **Policy Advocacy**: Work with state governments to promote EV-friendly policies.

---

## Folder Structure

```plaintext
ev-sales-analysis/
├── data/
│   └── ev_sales_data.csv   # Raw dataset
├── notebooks/
│   └── EV_Sales_Analysis.ipynb  # Jupyter Notebook with EDA
├── images/
│   └── charts/   # Visualizations generated during analysis
├── README.md
└── requirements.txt  # Required Python libraries
```

---

## Future Work

- **Predictive Modeling**: Build models to forecast EV sales.
- **Cluster Analysis**: Segment markets based on sales patterns.
- **Dashboard Development**: Create interactive dashboards for real-time analysis.



## Author

**Rohit Raj**  
*Data Analyst*  
- [GitHub](https://github.com/RohitRa200)  
- [LinkedIn](https://www.linkedin.com/in/rohitrajanalyticsmind/)

---

## Acknowledgments

Special thanks to the open-source community and the creators of the dataset used in this analysis.
---

## Visualizations

This project includes various visualizations to help interpret the data and derive actionable insights. Below are the key visualizations:

1. **Top States by EV Sales in India (2022)**: Highlights the leading states in EV adoption.
2. **Top-Selling EV Vehicle Classes in India (2022)**: Displays the most popular vehicle classes.
3. **EV Sales by Vehicle Category**: Illustrates the distribution of EV sales across 3-Wheelers, 2-Wheelers, and 4-Wheelers.
4. **Top-Selling EV Types by Usage (2022)**: Compares the most sold EV types based on usage categories.
5. **Market Share of EVs by State**: Shows the geographic distribution of EV adoption.
6. **Contribution of Vehicle Categories to Total EV Sales**: Demonstrates the sales contribution of each vehicle category over time.

### Explore More
For additional visualizations and a deeper dive into the analysis, please visit the **[visualizations](./images/charts)** folder.  
You can also view the detailed analysis in the **`EV_Sales_Analysis.ipynb`** file.

