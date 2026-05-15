# 📈 Analisis Deret Waktu IHSG dengan Model ARIMA dan Intervensi

## 📌 Project Overview
Project ini berfokus pada pemodelan data deret waktu Indeks Harga Saham Gabungan (IHSG) menggunakan pendekatan **ARIMA** dan **Model Intervensi**. Analisis ini bertujuan untuk memodelkan pola data serta melihat dampak dari kejadian eksternal (intervensi) terhadap fluktuasi pasar saham Indonesia.

## 🛠️ Tech Stack & Tools
- **Language:** R 
- **Library:** `tseries`, `forecast`, `TSA`, `ggplot2`
- **Documentation:** RMarkdown (HTML)

## 📊 Key Analysis Steps
1. **Exploratory Data Analysis (EDA):** Visualisasi tren data IHSG.
2. **Stationarity Test:** Uji ADF dan transformasi (differencing/log).
3. **Model Identification:** Penentuan order ARIMA melalui plot ACF/PACF.
4. **Intervention Analysis:** Identifikasi titik intervensi dan estimasi dampaknya (Step/Pulse).
5. **Diagnostic Checking:** Uji residual (white noise & normalitas).
6. **Forecasting:** Peramalan untuk periode mendatang.

## 🚀 Results
- Model terbaik yang diperoleh: **ARIMA(p,d,q) + Intervention Model**.
- Akurasi Model: MAPE sebesar sebesar 0.74% atau setara dengan tingkat akurasi 99,26%.
- Kesimpulan: Intervensi Pengesahan RUU TNI (20 Maret 2025) tidak memberikan dampak yang signifikan terhadap pergerakan IHSG, karena model tanpa intervensi memiliki nilai AIC dan BIC yang lebih kecil.

## 📂 Project Files
- `index.html`: Laporan lengkap interaktif (Rendered RMarkdown).
- `Analisis_IHSG.Rmd`: Source code utama.
- `data`: Dataset IHSG (Yahoo Finance).
