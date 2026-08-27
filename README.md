# SuperStore Data Profiling & Exploratory Analysis

## Project Overview
Analisis eksploratif (EDA) pada dataset ritel SuperStore untuk mengidentifikasi tren penjualan, anomali profitabilitas, dan performa kategori produk.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Seaborn, Matplotlib
- **Environment:** Google Colab / Jupyter Notebook

## Key Findings & Hypotheses
- **Sales vs Profit Anomaly:** Ditemukan beberapa item dengan volume penjualan (*sales*) tinggi namun menghasilkan profit negatif (rugi).
- **Category Insights:** Kategori *Furniture* mencatatkan rata-rata profit terendah dibandingkan *Office Supplies* dan *Technology*, meskipun volume penjualan tergolong tinggi.

## Visualizations & Analysis
- **Data Cleansing & Profiling:** Pemeriksaan tipe data, penanganan nilai hilang, dan agregasi data menggunakan `pd.pivot_table`.
- **Trend & Correlation:** Analisis hubungan *Sales* vs *Profit* menggunakan *Scatterplot* dan *Linear Regression Plot (`sns.lmplot`)*.
