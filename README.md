# superstore-sales-analysis

Analisis Kinerja Penjualan Superstore dengan Excel dan Power BI


Dashboard interaktif penjualan retail 2014–2017 untuk melihat kategori, wilayah, dan kebijakan diskon yang memengaruhi keuntungan.

**Tools:** Excel (cleaning, pivot) · Power BI (dashboard)

---

## Latar Belakang
Analisis ini menjawab:
- Kategori/sub-kategori paling untung dan merugi  
- Wilayah dengan penjualan tertinggi/terendah  
- Pola penjualan tahunan  
- Dampak diskon besar terhadap profit  

## Data
- **Sumber:** [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  
- **Cakupan:** 9.994 transaksi (2014–2017)  
- Kolom utama: Order Date, Region, Category, Sales, Discount, Profit  

## Proses
- **Excel:** pemeriksaan data, kolom tambahan (Tahun, Bulan, Margin, Diskon), PivotTable  
- **Power BI:** dashboard interaktif dengan filter Tahun, Region, Segment  

## Ringkasan
- Total penjualan: ± 2,30 juta USD  
- Total profit: ± 286 ribu USD  
- Margin: 12,5%  
- Kuantitas: 37.873 unit  

**Temuan utama:**  
- Puncak penjualan tiap September–November  
- Furniture margin tipis, Technology paling untung  
- Sub-kategori merugi: Tables, Bookcases, Supplies  
- Diskon >20% → margin negatif  
- Wilayah West tertinggi, South terendah  

## Rekomendasi
- Batasi diskon ≤20%  
- Evaluasi kategori Furniture  
- Siapkan stok/promosi sebelum September  
- Fokus perbaikan wilayah South  

## Struktur Repo
```
├── excel/superstore-analysis.xlsx
├── powerbi/superstore-dashboard.pbix
├── images/
└── README.md
```
## Cara Membuka
- **Excel:** buka `excel/superstore-analysis.xlsx`  
- **Power BI:** buka `powerbi/superstore-dashboard.pbix` dengan [Power BI Desktop](https://powerbi.microsoft.com/desktop/)  

---

