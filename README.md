# Matematika-Diskrit-Matrix-2
Tugas ini berfokus pada pembuktian kebenaran pernyataan matematika (khususnya tentang matriks, deret bilangan ganjil, dan deret geometri) dengan cara membuat program Python untuk mengecek validitas rumus.

# Penugasan Matematika Diskrit (MATDIS) - Analisis Validitas Pernyataan Matematika
>Repository ini berisi penyelesaian tugas Matematika Diskrit yang menganalisis validitas beberapa pernyataan matematika untuk berbagai nilai bilangan bulat n. Kode ditulis dalam Python dan dijalankan dalam format Jupyter Notebook.

## 📋 Deskripsi Tugas
Tugas ini menentukan untuk bilangan bulat n berapa saja pernyataan-pernyataan matematika berikut valid:
1. 1 + 3 + 5 + ... + (2n - 1) = n^2
2. 1 + 2 + 2^2 + 2^3 + ... + 2^n = 2^n+1 - 1
3. 1^2 = 2^2 + 3^2 + ... + n^2 = n(n+1)(2n+1)/6
4. n! > 2^n-1
5. 2^n > n^2

## 🚀 Hasil Analisis
Berdasarkan simulasi Python untuk n = 1 hingga n = 20, diperoleh hasil:
1. Jumlah Bilangan Ganjil
   * Hasil: Valid untuk semua n ≥ 1
   * Kesimpulan: Rumus berlaku untuk semua bilangan bulat positif.
2. Jumlah Deret Geometri
   * Hasil: Valid untuk semua n ≥ 0
   * Kesimpulan: Rumus berlaku untuk semua bilangan bulat non-negatif.
3. Jumlah Kuadrat
   * Hasil: Valid untuk semua n ≥ 1
   * Kesimpulan: Rumus berlaku untuk semua bilangan bulat positif.
4. Pertidaksamaan Faktorial
   * Hasil: Valid untuk semua n ≥ 1
   * Kesimpulan: Pertidaksamaan berlaku untuk semua bilangan bulat positif.
6. Pertidaksamaan Eksponensial
   * Hasil: Valid untuk n = 0, 1, n ≥ 5
   * Kesimpulan: Pertidaksamaan tidak berlaku untuk n = 2, 3, 4.

## 📊 Contoh Output
text
5. 2^n > n^2 (Detail)

n | 2^n | n^2 | Valid?
--|-----|-----|-------
 0 |   1 |   0 | True
 1 |   2 |   1 | True
 2 |   4 |   4 | False
 3 |   8 |   9 | False
 4 |  16 |  16 | False
 5 |  32 |  25 | True
 6 |  64 |  36 | True
... (selanjutnya True)

## 🛠️ Teknologi Used
* Python 3
* Jupyter Notebook
* Libraries: Standard Python only

## 📁 Struktur Repository
text
│   Penugasan_Matematika_Diskrit_(MATRIKS)_Kelas_A_[24083010034]_Aisyah_Amalia_Hamid.ipynb
│   README.md

## 👩‍💻 Author
Aisyah Amalia Hamid
NIM: 24083010034
Kelas: A
Program Studi: Sains Data

>© 2024 Aisyah Amalia Hamid. All rights reserved.
