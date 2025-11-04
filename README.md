## ABOUT DATASET 

Tugas ini dibuat oleh : 
Aulia Nadya C (202210370311382)
Larasati Khadijah K.K (202210370311410) 

Temu Kembali Informasi A

## Deskripsi Dataset 
Dataset Narkotika merupakan kumpulan data putusan pengadilan yang berkaitan dengan tindak pidana narkotika di Indonesia khususnya pada pengadilan negeri di kota Gresik. 
Dataset ini terdiri dari arsip data dalam format .zip dan file overview dalam format .xlsx

## Isi Dataset 
Berisi ratusan file teks hasil ekstraksi dari **putusan pengadilan negeri** yang berkaitan dengan tindak pidana narkotika.  
Setiap file mewakili satu kasus dan mencakup beberapa bagian utama:
- **Nomor Putusan**  
- **Identitas Terdakwa**  
- **Fakta Persidangan**  
- **Amar Putusan**  
- **Barang Bukti**

Overview.xlsx
Berisi **metadata dan statistik** dari dataset, antara lain:
- Jumlah total putusan.  
- Nomor Putusan  
- Lembaga Peradilan
- Barang Bukti  
- Amar Putusan

File ini membantu memahami karakteristik dataset sebelum digunakan untuk pelatihan model atau analisis lebih lanjut.

## Cara Menggunakan 
1.	Download Dataset
- Klik file yang ingin diunduh (misalnya `Narkotika.zip` atau `Overview.xlsx`)
- Pilih tombol **“View raw”** untuk mendownload.
2.	**Ekstrak File**
   ```bash
   unzip Narkotika.zip -d data/
