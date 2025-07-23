# 🇮🇳 Indian Political Data Analysis (1980–2024)

This project is a comprehensive analysis of Indian Lok Sabha election results from **1980 to 2024**. It involves **web scraping**, **data transformation**, **exploratory analysis**, and **visualization of party-wise performance trends** over the decades.

The goal is to produce clean, structured, and analyzable datasets across election years and deliver insights on party dominance, vote margins, and voter behavior.

---

## 📁 Project Structure

| Notebook Name | Description |
|---------------|-------------|
| `1980-2014-Data-Extraction-Process.ipynb` | Web scraping and initial extraction of ECI election result tables for years 1980 to 2014. |
| `2009-Data-Extraction-Process.ipynb` | Dedicated script to extract 2009 results due to ECI format changes. |
| `2019-election-data-scraping.ipynb` | Scrapes candidate-level 2019 results from the ECI website. |
| `2024-Political-dataset-ingestion.ipynb` | Extracts and structures 2024 results from updated web format. |
| `2019-election-data-scraping-and-transformation.ipynb` | Transforms raw 2019 data into analyzable form—cleaning and renaming columns. |
| `1980-to-2014-transformation.ipynb` | Cleans and harmonizes data from 1980–2014 to align with newer years. |
| `2024-Transformation.ipynb` | Cleans 2024 data (e.g., vote formatting, missing values). |
| `Party-transformations-1980-2024.ipynb` | Applies standardization and mapping to party names across years. |
| `party_wise_performance.ipynb` | Aggregates constituency-wise data to compute party-wise performance (votes, counts, margins). |
| `CVI_EDA.ipynb` | Computes CVI (Constituency Volatility Index) and explores vote swing trends. |
| `Exploratory Data Analysis.ipynb` | Analyzes key patterns: margins, top winners/losers, runner-up gaps. |
| `Data Loading.ipynb` | Loads final cleaned datasets into a MySQL database for long-term storage and BI use. |

---

## 🗂️ Data Files

| CSV File | Purpose |
|----------|---------|
| `yearly_party_performance.csv` | Summarized party-wise vote performance by year |
| `CVI_TABLE.csv` | Contains calculated CVI scores for each constituency |
| `State_const_dup_mapping.csv` | Handles renamed or duplicated constituency mappings over time |
| `API-data-dictionary.csv` | Metadata definitions for final structured dataset (useful for APIs or frontend integration) |

---

### 1. 🟦 Number of Seats Won by Party (Grouped by Year)


<img width="1233" height="521" alt="image" src="https://github.com/user-attachments/assets/fc344969-18a7-44a5-badf-089b2cc804de" />



---

### 2. 🟧 Line Plot: Voting Share (%) Trend by Party

<img width="1225" height="521" alt="image" src="https://github.com/user-attachments/assets/86589a5d-1efa-4ccb-8873-5b98bd9caed7" />

<img width="1377" height="853" alt="image" src="https://github.com/user-attachments/assets/1ce1510a-3907-4342-b47d-d3b198b83f60" />


---

### 3. 🟥 Barplot: Median Constituency Volatility Index (CVI) Per State

<img width="675" height="413" alt="image" src="https://github.com/user-attachments/assets/6e33fe96-8f86-436a-8c93-c97d11ce71d4" />


---

### 4. 🟨 Screenshot: Final MySQL Table View

<img width="1599" height="887" alt="Screenshot 2025-07-23 at 6 54 40 PM" src="https://github.com/user-attachments/assets/8bbd36c1-09b6-48e2-b13a-fabf418b553c" />

---

## 🧠 Key Highlights

- 🔁 **Standardized party names** across decades using mapping and string harmonization.
- 🧹 **Transformed raw ECI tables** with inconsistent formats into consistent DataFrames.
- 🧮 **Computed CVI scores** to measure how volatile or stable constituencies are.
- 📈 **Trend analysis** on party performance, voter turnout, and margins.
- 🗃️ **Loaded final datasets into MySQL** for use in Power BI dashboards or public APIs.

---

## 💡 Future Enhancements

- 📍 Geo-visualizations using Plotly or Folium
- 🧠 Sentiment analysis from party manifestos or Twitter during elections
- 📤 Public API for polling data access (based on `API-data-dictionary.csv`)
- 🧪 Use ML to predict close contests based on historical CVI & margin trends

---

## 👤 Author

**Badrinath Sanagavaram**  

Data Engineer - Data Enthusiast - Data Migration Expert

---

