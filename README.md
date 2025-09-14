# Weather Trend Analysis – East Kotawaringin (2010–2024)

This project analyzes **weather trends in East Kotawaringin Regency, Central Kalimantan, Indonesia**, over the period **2010–2024**.  
The data was collected from **BMKG (Meteorology, Climatology, and Geophysics Agency of Indonesia)** in monthly format, merged into a complete dataset, preprocessed, and analyzed using **Python on Google Colab**.  

The study aims to identify long-term patterns in **temperature, rainfall, humidity, and wind dynamics**, and to observe seasonal variations and potential climate change impacts on the region.  

## Project Structure
- **images/** → Visualization outputs:  
  - `Histogram.png` → Distribution of weather variables  
  - `Korelasi Antar Variabel.png` → Correlation heatmap between variables
  - `Tren Harian.png` → Daily trends  
  - `Tren Bulanan.png` → Monthly trends  
  - `Tren Tahunan.png` → Annual trends  
- **825230136_Data_Bersih.xlsx** → Cleaned dataset after preprocessing  
- **825230136_Data_Mentah.xlsx** → Raw dataset merged from BMKG monthly files  
- **Analisis Tren Cuaca Kab Kotawaringin Timur 2010-2024.pdf** → Final research report (in Bahasa Indonesia)  
- **Kode Analisis Data.ipynb** → Jupyter Notebook for data analysis and visualization  
- **Kode Pra-Pemrosesan Data.ipynb** → Jupyter Notebook for data preprocessing  
- **README.md** → Project documentation  

## Methodology
The workflow includes:  
1. **Data Collection** – BMKG monthly weather data (2010–2024).  
2. **Data Integration** – Merging 180 monthly files into a single dataset.  
3. **Data Preprocessing** – Cleaning invalid values (`8888`, `9999`, `-`), filling missing data, formatting date/time.  
4. **Exploratory Data Analysis** – Descriptive statistics and correlation analysis.  
5. **Visualization** – Generating histograms, correlation heatmap, and time-series trend plots (daily, monthly, annual).  

## Visualizations
Key visualizations included in both the analysis code and the `/images/` folder:  
- **Histogram** – Variable distribution (e.g., temperature, rainfall, humidity).  
- **Correlation Heatmap** – Relationship between weather variables.  
- **Monthly Trends** – Weather patterns over months.  
- **Annual Trends** – Long-term changes across years.  
- **Daily Trends** – Short-term fluctuations.  

## Key Findings
- Average **temperature has increased by 1°C** over 15 years.  
- **Humidity trends upward**, while rainfall remains highly variable with extremes in specific years.  
- Clear **seasonal patterns** remain between wet and dry seasons.  
- Negative correlation between **temperature and humidity**.  

## Technologies Used
- **Python (Google Colab)** – Analysis and visualization  
- **Pandas & NumPy** – Data preprocessing and manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Excel** – Data integration and validation  

## Author
**Felicia June**
