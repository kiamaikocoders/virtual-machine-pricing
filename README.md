# virtual-machine-pricing

# **Cloud VM Pricing and Regional Analysis**

## **Overview**
This project focuses on analyzing a dataset of virtual machine (VM) configurations, pricing, and discounts across various regions. The goal is to derive insights into cost-effectiveness, regional trends, and price-resource relationships to aid in decision-making for cloud service selection.

---

## **Dataset**
The dataset contains the following key features:
- **VM Configurations**:
  - `name`: The configuration name.
  - `numberOfCores`: Number of CPU cores.
  - `memoryInMB`: Amount of memory (in MB).
- **Pricing**:
  - `linuxPrice`: Hourly price for Linux-based configurations.
  - `windowsPrice`: Hourly price for Windows-based configurations.
- **Regional Discounts**:
  - `bestPriceRegion`: Region offering the best price, often including a discount percentage.
- **Derived Columns** (from data processing):
  - `region`: Extracted region name.
  - `discount`: Calculated percentage discount for each configuration.

---

## **Objectives**
1. **Best Prices by Region**: Identify the most cost-effective VM configurations per region.
2. **Linux vs. Windows Price Comparison**: Analyze price distributions to compare costs across operating systems.
3. **Price-Resource Correlation**: Determine relationships between price, CPU cores, and memory.
4. **Regional Trends**: Explore pricing and discount patterns across regions.
5. **Cost-Effectiveness**: Evaluate configurations based on price per core and price per MB of memory.

---

## **Analysis and Insights**
### **Key Findings**
1. **Best Prices by Region**:
   - Identified the lowest prices for Linux and Windows configurations in each region.
2. **Linux vs. Windows Pricing**:
   - On average, Linux configurations are more cost-effective than Windows.
3. **Price-Resource Relationship**:
   - Pricing correlates strongly with both CPU cores and memory, with some anomalies.
4. **Regional Discounts**:
   - Certain regions consistently offer higher discounts, with "East US" being the most frequently discounted region.
5. **Cost-Effective Configurations**:
   - Highlighted the configurations offering the best price per core and price per MB of memory.

---

## **Visualizations**
The project includes several key visualizations:
1. **Price Distributions**:
   - Histogram comparing Linux and Windows pricing.
2. **Price vs. Resources**:
   - Scatterplot of pricing against CPU cores.
3. **Regional Discount Heatmap**:
   - A heatmap showing average discounts per region.

---

## **Tools and Technologies**
- **Languages**: Python
- **Libraries**: 
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization
  - `numpy` for numerical analysis

---

## **Next Steps**
1. **Advanced Analysis**:
   - Predictive modeling to estimate future pricing trends.
   - Clustering regions based on pricing and discount patterns.
2. **Interactive Dashboards**:
   - Implement tools like Tableau or Dash for better visualization.
3. **Benchmarking**:
   - Compare this dataset with other cloud providers for deeper insights.

---

## **How to Use**
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   python analysis.py
   ```
4. View results:
   - Outputs will include CSV summaries and interactive visualizations.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## **Contributors**
- [kiamaikocoders] - Data Analyst
- Contributions and feedback are welcome!

---

Let me know if you'd like me to adjust or expand on any part of this template!
