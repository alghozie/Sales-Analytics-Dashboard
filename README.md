# Global Sales Performance Dashboard

Dashboard ini dikembangkan untuk menampilkan **kinerja penjualan global** secara komprehensif dan interaktif.  
Proses **data cleaning dan preparation** dilakukan menggunakan Python, sedangkan visualisasi final dibuat menggunakan **Looker Studio**.

Dashboard dirancang untuk membantu pengguna dalam:
- Memantau performa penjualan berdasarkan segmentasi produk, kategori, wilayah, dan waktu.
- Menganalisis tren penjualan bulanan serta profitabilitas per segmen.
- Menilai efektivitas pengiriman (shipping performance) melalui analisis waktu pemrosesan dan ketepatan waktu.
- Melihat detail penjualan hingga level produk dan kota secara visual.

---

## Tujuan Proyek
- Menyajikan visualisasi penjualan global secara ringkas dan mudah dipahami.
- Memberikan wawasan berbasis data untuk mendukung proses pengambilan keputusan.
- Menggabungkan metrik kunci seperti **total sales**, **profit**, **orders**, **return rate**, dan **average order value (AOV)**.
- Menyediakan analisis performa pengiriman untuk menilai efisiensi distribusi logistik.

---

## Teknologi yang Digunakan

### 1. Data Cleaning & Preparation (Python)
Menggunakan library berikut:
- **Pandas**
- **NumPy**
- **OpenPyXL / Excel Reader Tools**

Tahapan pembersihan data meliputi:
- Penanganan missing values  
- Formatting & standardisasi kolom  
- Transformasi data (date parsing, renaming columns, dsb.)

### 2. Dashboard Development (Looker Studio)
Elemen visual yang digunakan:
- **KPI Cards** (Total Sales, Total Order, Profit, Return Rate, AOV)
- **Pie Chart** (Sales by Segment)
- **Line Chart** (Monthly Sales Trend)
- **Bar Chart** (Profit per Segment)
- **Data Table** (Detail Sales per Product)
- **Interactive Filters** (Date Range, Segment, Category, Region, City)
- **Geo Map** (Sales by City)
- **Shipping Performance Visuals** (On-time vs Delayed, Processing Time per Ship Mode)

---

## Fitur Utama Dashboard

### 1. Sales Overview
Menampilkan metrik utama seperti:
- Total Sales  
- Total Orders  
- Profit Margin  
- Average Order Value (AOV)  
- Return Rate  

Visual yang ditampilkan:
- Sales by Segment (Consumer, Corporate, Home Office)
- Monthly Sales Trend
- Profitability per Segment
- Product Detail Table (Quantity, Sales, Discount, Profit)

### 2. Shipping Performance
Analisis pengiriman meliputi:
- Rata-rata waktu pemrosesan per ship mode
- Perbandingan pengiriman **on-time vs delayed**
- Shipping performance berdasarkan region (Central, South, West, East)
- Visual bar & line chart untuk analisis per mode pengiriman

---

## Sumber Data
Dataset berupa file Excel (.xlsx) yang berisi:
- Informasi produk  
- Segmentasi pelanggan  
- Region & city  
- Sales & profit  
- Shipping detail (mode, processing time, status)

Data dibersihkan menggunakan Python sebelum digunakan di Looker Studio.

---

## Insight yang Dihasilkan
Beberapa temuan penting dari dashboard:
- Segmen **Consumer** menyumbang penjualan terbesar secara keseluruhan.
- Terdapat **fluktuasi signifikan** pada monthly sales sepanjang tahun.
- Kategori **Technology** menghasilkan sales tertinggi.
- Shipping performance berbeda jauh antar region, dengan **Standard Class** memiliki waktu pemrosesan terlama.
- Gap yang cukup jelas terlihat antara pengiriman **on-time** dan **delayed** pada beberapa ship mode.

---

## Cara Menggunakan Dashboard
Dashboard dapat dilihat langsung di Looker Studio dengan fitur:
- Filter interaktif
- Pemilihan periode waktu
- Drill-down dari **Category → Sub-Category → Product**
- Pemetaan sales berdasarkan kota (Geo Visualization)

---

## Tampilan Dashboard
<img width="1436" height="1079" alt="Cuplikan layar 2025-11-17 031145" src="https://github.com/user-attachments/assets/7d1b8959-143e-4f3c-a969-770d0f13e144" />

> *https://lookerstudio.google.com/s/v7gI6Fn4gz4*

---  
