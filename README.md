# 👗 Fashion Trend Forecasting with Sales & Social Data

This project analyzes fashion retail sales alongside trending social hashtags to forecast product category trends. It combines structured sales data with unstructured social signals to uncover consumer preferences across time.

## 📊 Project Goals
- Forecast monthly fashion sales trends.
- Identify top-performing product categories.
- Use time series grouping and trendline visualizations.
- Enable data-driven inventory or marketing decisions.

## 🛠️ Tech Stack
- Python
- Pandas, Seaborn, Matplotlib
- Jupyter Notebook
- CSV-based sales data
- Power BI (optional for dashboard visualization)

## 📁 Folder Structure



fashion-trend-forecasting/
├── data/ # Contains CSV files (ignored in Git)
├── notebooks/ # Jupyter notebooks
├── visuals/ # Trendline plots and graphs
├── README.md # Project summary and instructions
├── .gitignore # Tracks ignored files

bash
Copy
Edit

## 🧪 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fashion-trend-forecasting.git
   cd fashion-trend-forecasting
Open the Jupyter notebook:

Copy
Edit
notebooks/01_data_ingestion_and_eda.ipynb
Ensure your data CSVs are placed in:

kotlin
Copy
Edit
data/
Run the notebook top-to-bottom to:

Load sales data

Merge with category and store info

Generate trendlines and monthly forecasts

View plots inside:

Copy
Edit
visuals/
📌 Sample Output
Line chart showing category-level monthly trendlines and top-performing segments over time.

📦 Dependencies
All standard Python libraries used (no need for requirements.txt):

pandas

matplotlib

seaborn

os

No external model training or large packages used — simple, clean and EDA-focused.

