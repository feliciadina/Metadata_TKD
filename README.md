# Metadata TKD_Kelompok 8

## Dataset: `Financial Data (Standard & Poor’s 500) companies.csv`

### Deskripsi
File `Financial Data (Standard & Poor’s 500) companies.csv` menyediakan data keuangan perusahaan, termasuk pendapatan, laba bersih, dan rasio keuangan, yang berguna untuk benchmarking terhadap bisnis klien. Informasi ini dapat membantu mengidentifikasi tren industri, posisi kompetitif, dan peluang strategis. 

### Struktur Dataset
Berikut adalah deskripsi kolom yang tersedia dalam dataset:
| Nama Kolom                                | Tipe Data | Deskripsi                                                       |
|-------------------------------------------|-----------|-----------------------------------------------------------------|
| `No`                                      | int64     | Nomor urut untuk setiap baris data.                             |
| `date`                                    | object    | Tanggal terkait data.                                           |
| `firm`                                    | object    | Nama perusahaan.                                                |
| `Ticker`                                  | object    | Kode ticker perusahaan di bursa saham.                          |
| `Research Development`                    | float64   | Biaya riset dan pengembangan perusahaan.                        |
| `Income Before Tax`                       | float64   | Pendapatan sebelum pajak.                                       |
| `Net Income`                              | float64   | Pendapatan bersih setelah pajak.                                |
| `Selling General Administrative`          | float64   | Biaya penjualan, umum, dan administrasi.                        |
| `Gross Profit`                            | float64   | Laba kotor perusahaan.                                          |
| `Ebit`                                    | float64   | Earnings Before Interest and Taxes (EBIT).                      |
| `Operating Income`                        | float64   | Pendapatan operasional.                                         |
| `Interest Expense`                        | float64   | Beban bunga perusahaan.                                         |
| `Income Tax Expense`                      | float64   | Beban pajak penghasilan.                                        |
| `Total Revenue`                           | float64   | Total pendapatan perusahaan.                                    |
| `Total Operating Expenses`                | float64   | Total biaya operasional.                                        |
| `Cost Of Revenue`                         | float64   | Biaya yang terkait dengan pendapatan.                           |
| `Total Other Income Expense Net`          | float64   | Total pendapatan atau beban lain di luar operasional.           |
| `Net Income From Continuing Ops`          | float64   | Pendapatan bersih dari operasi yang berlanjut.                  |
| `Net Income Applicable To Common Shares`  | float64   | Pendapatan bersih yang berlaku untuk saham biasa.               |


### Cara Penggunaan
1. **Membuka Dataset**:
   Gunakan library seperti pandas di Python untuk membuka dan memproses dataset:
      ```python
   import pandas as pd
   data = pd.read_csv("Financial Data (Standard & Poor’s 500) companies.csv")
      
2. **Cek Tipe Data**:
   Periksa tipe data setiap kolom untuk memastikan konsistensi:
   ```python
   print(data.dtypes)
   
4. **Cek Missing Values**:
   Identifikasi nilai yang hilang;
   ```python
   print(data.isnull().sum())
   
6. **Handling Missing Values**:
   Tangani nilai yang hilang menggunakan rata-rata dari kolom yang terdapat Null.

### Data Lineage
belum

### Lisensi
