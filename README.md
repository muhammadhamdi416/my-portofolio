# INPUT KARYAWAN 7 VISUALISASI DATA EXCEL 

## Deskripsi Proyek
Sebuah sistem all-in-one dalam Excel yang menggabungkan:
1. Form Input Data Karyawan yang user-friendly dengan Data Validation dan Form Controls
2. Pencarian Data Karyawan sederhana
3. Dashboard Interaktif dengan visualisasi dinamisdan analisis performa penjualan 

Tujuan: Membuat sistem yang lengkap dalam 1 file Excel saja - dari input data hingga analisis - tanpa membutuhkan tools programming tambahan.

## Teknologi yang Digunakan
Hanya Microsoft Excel dengan fitur-fitur advanced:
- Data Validation & Dropdown Lists
- Advanced Formulas (VLOOKUP, SUMIFS, INDEX-MATCH)
- Pivot Tables & Pivot Charts
- Form Controls (Buttons, Combo Boxes, Spin Buttons)
- Conditional Formatting
- Excel Tables & Structured References

## Worksheet dalam Project_Input_karyawan_&_Visualisasi_data.xlsm:
| Sheet Name | Deskripsi |
|------------|--------|
| PORTOFOLIO | Keterampilan menggunakan Excel |
| SKILL | Tingkat Kemahiran Excel dan Tempat penerapannya |
| DASHBOARD |	Visualisasi & analisis interaktif |
| SOURCE_DASHBOARD | Tabel data dari Dashboard |
| PENCARIAN | Pencarian data  karyawan dari sheet DATA_KARYAWAN |
| DATA_KARYAWAN | Input Data Karyawan dan Database karyawan |
| DATA_JABATAN | Input Data jabatan dan Database jabatan |
| superstore | Data referensi (produk, kategori, dll) |

## Cara Menggunakan Sistem 
A. Input Data Baru:
  1. Buka worksheet "DATA_KARYAWAN"
  2. Isi field yang tersedia :
   
      1) Nama (Text dan akan do conver jadi UPPERCASE saatUpdate)
      2) Divisi (Cukup isi Jabatan maka Divisi akan otomatis terisi)
      3) Jabatan (Dipilih dengan Data Validation dengan source DATA_JABATAN)
      4) Tanggal Lahir (Number dengan petunjuk dd/mm/yyyy saat kolom di select)
      5) Email (Text)
      6) No HP (number)
      7) Alamat (Text)
      9) Gaji (Cukup isi Jabatan maka Gaji akan otomatis terisi)
      10) Klik Tombol **Update Data Karyawan** agar data ditambahkan
      11) jika terdapat field yg kosong maka muncul error saat klik tombol update
      13) SAVE file (CTRL + S)

B. Melihat Analisis:
  1. Buka worksheet "DASHBOARD"
  2. Gunakan filter interaktif (Month, Year, Region, State)

## Fitur & Fungsi
  1. Automated Input System :
      - Data Validation mencegah input error
      - Auto-complete untuk konsistensi data
      - Update data dengan macro button

  2. Interactive Dashboard:
      - Sales Trend Chart (Bulanan/Tahunan)
      - Total kontribusi Category Breakdown Pie Chart
      - Sales Summary Metrics (Sales, Total_Order, Profit, Profit_margin, quantity)
      - Top 10 Products Visualization
    
## Preview Dashboard
<img src=".my-portofolio/Images-/DASHBOARD_SALES.png" alt="DASBOARD_SALES">
