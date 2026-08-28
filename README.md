# 📊 Global Superstore Advanced Analytics

## 📌 Project Overview

Proyek ini merupakan latihan analisis dan visualisasi data menggunakan **Microsoft Excel** dengan fokus pada pembuatan **interactive charts**.

Saya menganalisis data transaksi Global Superstore selama periode **2011–2014**. Setelah proses data cleaning, data yang digunakan dalam analisis terdiri dari **51,284 records**.

Dalam proyek ini, saya menggunakan beberapa fitur Advanced Excel untuk membuat visualisasi yang interaktif, termasuk **Slicers, Form Controls, Dynamic Data Lookup, dan Advanced Charting Techniques**.

Analisis digunakan untuk melihat tren pertumbuhan Sales, distribusi nilai transaksi, pola penjualan bulanan, serta hubungan antara tingkat Discount dan Profit berdasarkan data yang tersedia.

---

## 🗂️ Dataset

- **Dataset:** Global Superstore Dataset
- **Source:** Kaggle
- **Publisher:** Fatih İlhan
- **Period:** 2011–2014
- **Records:** 51,284

📎 **Dataset Source:**  
[Global Superstore Dataset – Kaggle](https://www.kaggle.com/datasets/fatihilhan/global-superstore-dataset)

---

## 🛠️ Data Preparation & Analysis

Beberapa proses yang saya lakukan dalam proyek ini meliputi:

### Data Preparation

- Memeriksa data kosong pada variabel yang digunakan dalam analisis
- Menghapus 6 baris data kosong sehingga jumlah data yang digunakan menjadi **51,284 records**
- Memeriksa format dan struktur data
- Menyesuaikan formatting angka agar nilai Sales lebih mudah dibaca

### Data Transformation

- Membuat **Group Sales** untuk mengelompokkan nilai transaksi ke dalam beberapa rentang harga
- Membuat **Group Discount** untuk mengelompokkan tingkat Discount ke dalam beberapa interval persentase
- Mengekstrak informasi **Month** dari kolom Order Date untuk mendukung analisis bulanan

### Analysis & Excel Features

- Menggunakan **PivotTables** untuk membantu proses analisis
- Menggunakan **Slicers** untuk membuat visualisasi yang dapat difilter secara interaktif
- Menggunakan **Form Control Scroll Bar** untuk menampilkan data secara dinamis
- Menggunakan **Dynamic Data Range** dengan fungsi `OFFSET`
- Membuat dynamic chart title
- Menggunakan Custom Error Bars untuk membuat indikator perubahan nilai
- Menggunakan Conditional Formatting untuk mendukung visualisasi data
- Membuat interactive charts menggunakan Microsoft Excel

---

# 📈 Interactive Charts & Key Insights

## 1️⃣ Year-over-Year Sales Trend

Interactive chart digunakan untuk menampilkan perubahan Sales tahunan selama periode 2011–2014.

Visualisasi dapat difilter berdasarkan Region dan dilengkapi dengan indikator perubahan serta persentase pertumbuhan tahunan.

### 🔍 Key Insight

Berdasarkan data yang dianalisis, Sales menunjukkan peningkatan selama periode 2011–2014.

- **2011:** $2.26M
- **2012:** $2.68M
- **2013:** $3.41M
- **2014:** $4.30M

Sales meningkat sebesar **18.5%** pada 2012, kemudian meningkat sebesar **27.2%** pada 2013 dan **26.2%** pada 2014.

Berdasarkan visualisasi, Sales menunjukkan pertumbuhan positif selama periode analisis.

---

## 2️⃣ Sales Distribution by Transaction Value

Interactive histogram digunakan untuk melihat distribusi transaksi berdasarkan beberapa rentang nilai Sales.

Data transaksi dikelompokkan ke dalam beberapa kelompok nilai, mulai dari **$0–$99** hingga **$900+**.

### 🔍 Key Insight

Berdasarkan distribusi data:

- Kelompok **$0–$99** memiliki proporsi terbesar sebesar **56.19%**
- Kelompok **$100–$299** memiliki proporsi sebesar **23.89%**
- Kedua kelompok tersebut secara bersama-sama mencakup **80.08%** dari data transaksi yang dianalisis
- Kelompok transaksi **$900+** memiliki proporsi sebesar **5.26%**

Hasil ini menunjukkan bahwa sebagian besar transaksi dalam dataset berada pada rentang nilai Sales yang relatif rendah hingga menengah.

---

## 3️⃣ Monthly Sales Trend & Seasonality

Combination Chart digunakan untuk membandingkan pola Sales bulanan dan melihat perubahan pola penjualan berdasarkan tahun.

Visualisasi juga digunakan untuk melihat pola historis penjualan dari Januari hingga Desember.

### 🔍 Key Insight

Berdasarkan data historis, Sales menunjukkan perubahan nilai sepanjang tahun.

- **Februari** mencatat Sales sebesar **$543.8K**
- Sales kembali meningkat pada beberapa bulan berikutnya
- **November** mencatat Sales sebesar **$1.55M**
- **Desember** mencatat Sales sebesar **$1.58M**

November dan Desember memiliki nilai Sales tertinggi dalam data yang dianalisis.

Pola ini menunjukkan adanya peningkatan Sales menjelang akhir tahun pada data historis yang tersedia.

---

## 4️⃣ Discount Distribution & Profit Analysis

Interactive chart digunakan untuk melihat distribusi data berdasarkan kelompok Discount.

Visualisasi dapat digeser menggunakan **Form Control Scroll Bar** untuk menampilkan kelompok data secara dinamis.

### 🔍 Key Insight

Berdasarkan hasil analisis:

- Kelompok Discount **0–10%** mencakup **65.69%** dari data yang dianalisis
- Kelompok Discount **11–20%** mencakup **12.22%**
- Kelompok transaksi dengan Discount rendah memberikan kontribusi positif terhadap Profit
- Kelompok dengan Discount di atas **20%** menunjukkan adanya kontribusi Profit negatif dalam hasil analisis

Hasil ini menunjukkan bahwa hubungan antara Discount dan Profit dapat menjadi area yang menarik untuk dianalisis lebih lanjut.

---

## 💡 Analytical Considerations

Berdasarkan hasil analisis, terdapat beberapa hal yang dapat menjadi pertimbangan untuk analisis lebih lanjut:

- Hubungan antara Discount dan Profit dapat dievaluasi lebih lanjut untuk memahami dampak Discount terhadap profitabilitas.
- Distribusi nilai transaksi dapat digunakan untuk mengeksplorasi pola Sales berdasarkan kelompok nilai yang berbeda.
- Pola peningkatan Sales menjelang akhir tahun dapat digunakan sebagai dasar untuk mengeksplorasi pola musiman dalam data.
- Perbedaan pertumbuhan Sales antar-Region dapat dianalisis lebih lanjut untuk memahami variasi performa berdasarkan wilayah.

> **Note:** Temuan dalam proyek ini didasarkan pada data dan variabel yang tersedia dalam dataset. Hasil analisis menunjukkan pola pada data historis dan tidak digunakan sebagai dasar untuk menentukan keputusan bisnis secara langsung.

---

# 🖼️ Project Preview

### 1. YoY Sales Trend with Percentage Growth

![Chart 1 - YoY Sales Trend](chart1_yoy_trend.jpeg)

### 2. Interactive Histogram

![Chart 2 - Interactive Histogram](Chart%202%20-%20Histogram.jpeg)

### 3. Monthly Sales Trend & Seasonality

![Chart 3 - Annual Trend](Chart%203%20-%20Seasonality.jpeg)

### 4. Interactive Frequency Distribution

![Chart 4 - Frequency Distribution](Chart%204%20-%20Frequency%20ScrollBar.jpeg)

---

# 📁 Workbook Structure

**Order Data:** Berisi data transaksi yang digunakan dalam proses analisis.

**Advanced_Charting_Techniques:** Berisi proses analisis, staging tables, PivotTables, Slicers, Form Controls, dan interactive charts.

📄 **Main File:**  
`Advanced_Excel_Global_Superstore_Analytics.xlsx`

---

# 🧰 Tools & Skills Demonstrated

**Tool Used:** Microsoft Excel

**Skills & Techniques:**

- Data Cleaning
- Data Preparation
- Data Transformation
- Feature Engineering
- Nested IF
- Date Manipulation
- PivotTables
- Interactive Slicers
- Form Controls
- Dynamic Data Range
- OFFSET Function
- Custom Error Bars
- Conditional Formatting
- Data Visualization
- Trend Analysis
- Seasonality Analysis
- Sales Analysis
- Discount Analysis
- Interactive Chart Development

---

# 🎯 Project Takeaways

Melalui proyek ini, saya berlatih menggunakan fitur Advanced Excel untuk membuat visualisasi data yang lebih interaktif.
Proyek ini membantu saya memahami bagaimana data dapat diolah menjadi visualisasi yang dapat dieksplorasi melalui filter dan interactive controls.

Proses yang dilakukan dalam proyek ini meliputi:
**Raw Data → Data Preparation → Data Transformation → Analysis → Interactive Visualization**

---

# 👤 Author

**Alena Mansika**

- 💻 **GitHub:** [@alenamansika](https://github.com/alenamansika)
- 💼 **LinkedIn:** [Alena Mansika](https://www.linkedin.com/in/alenamansika)
