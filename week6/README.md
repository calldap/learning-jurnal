# Week 06 — Static Analysis Malware

## Ringkasan

Pada pertemuan keenam, saya mempelajari teknik **Static Analysis** sebagai langkah awal dalam proses Malware Analysis. Static Analysis merupakan metode analisis yang dilakukan tanpa menjalankan malware sehingga risiko infeksi terhadap sistem dapat diminimalkan. Melalui metode ini, saya mempelajari bagaimana mengidentifikasi karakteristik suatu file, menganalisis struktur executable, mengekstrak informasi penting, serta memahami fungsi-fungsi yang terdapat di dalam malware.

Materi ini memberikan pemahaman bahwa banyak informasi penting dapat diperoleh hanya dengan menganalisis file malware tanpa harus mengeksekusinya.

---

# Pembahasan Materi

## 1. Identifikasi Jenis File

Langkah pertama dalam Static Analysis adalah mengidentifikasi jenis file yang akan dianalisis. Proses ini bertujuan untuk mengetahui format file sehingga metode analisis yang digunakan dapat disesuaikan.

Informasi yang dapat diperoleh meliputi:

- Format file (PE, ELF, dan lain-lain).
- Ukuran file.
- Arsitektur sistem (32-bit atau 64-bit).
- Compiler yang digunakan (jika tersedia).

Tahap ini menjadi dasar sebelum melakukan analisis lebih lanjut terhadap struktur malware.

---

## 2. Analisis Struktur Executable

Setelah mengetahui jenis file, langkah berikutnya adalah mempelajari struktur executable.

Beberapa bagian penting yang diperhatikan antara lain:

- Header File.
- Section pada executable.
- Entry Point.
- Import Table.
- Export Table.

Melalui analisis struktur executable, saya dapat memperoleh gambaran mengenai bagaimana program disusun sebelum dijalankan.

---

## 3. Analisis Symbol Tree

Materi juga menjelaskan penggunaan **Symbol Tree** untuk melihat daftar fungsi maupun struktur program yang terdapat pada executable.

Melalui Symbol Tree, seorang analis dapat:

- Menemukan fungsi utama program.
- Mengidentifikasi fungsi sistem yang digunakan.
- Mengetahui hubungan antar fungsi.
- Mempermudah proses navigasi saat analisis.

Fitur ini sangat membantu ketika menganalisis program yang memiliki banyak fungsi.

---

## 4. Ekstraksi Strings

Static Analysis juga dilakukan dengan mengekstrak **strings** yang terdapat pada file executable.

Informasi yang dapat ditemukan antara lain:

- Nama file.
- URL.
- Alamat IP.
- Registry Key.
- Pesan kesalahan.
- Nama library (DLL).

Strings sering kali memberikan petunjuk awal mengenai perilaku malware tanpa harus menjalankan file tersebut.

---

## 5. Analisis Disassembly

Tahap berikutnya adalah melihat hasil **disassembly**, yaitu proses mengubah machine code menjadi bahasa assembly.

Melalui proses ini, saya dapat:

- Memahami alur eksekusi program.
- Mengidentifikasi fungsi penting.
- Menemukan proses validasi maupun autentikasi.
- Memahami logika dasar malware.

Walaupun bahasa assembly cukup sulit dipahami, proses ini menjadi bagian penting dalam Reverse Engineering.

---

# Insight Minggu Ini

Materi minggu ini membuat saya memahami bahwa Static Analysis merupakan tahap yang sangat penting dalam Malware Analysis. Tanpa menjalankan malware, saya sudah dapat memperoleh banyak informasi mengenai karakteristik file, struktur executable, fungsi program, hingga indikasi perilaku malware.

Saya juga menyadari bahwa Static Analysis menjadi langkah awal sebelum melanjutkan ke Dynamic Analysis.

---

# Tools yang Dipelajari

- Ghidra
- PE-bear
- Detect It Easy (DIE)
- Strings
- IDA Pro

---

# Refleksi Pembelajaran

## Apa yang Saya Pahami

Saya memahami tahapan dasar Static Analysis mulai dari identifikasi jenis file, analisis struktur executable, penggunaan Symbol Tree, ekstraksi strings, hingga proses disassembly. Saya juga mengetahui bahwa metode ini dapat memberikan banyak informasi tanpa perlu menjalankan malware.

## Apa yang Masih Membingungkan

Saya masih ingin mempelajari cara membaca kode assembly dengan lebih baik agar dapat memahami logika program secara lebih mendalam. Selain itu, saya juga ingin mengetahui bagaimana membedakan malware yang menggunakan teknik obfuscation dengan malware biasa melalui Static Analysis.

---

# Kesimpulan Pribadi

Pertemuan keenam memberikan pemahaman mengenai proses Static Analysis sebagai salah satu metode utama dalam Malware Analysis. Saya memahami bahwa analisis terhadap struktur executable, strings, serta hasil disassembly dapat memberikan informasi yang sangat berguna sebelum malware dijalankan pada lingkungan analisis yang aman. Materi ini menjadi bekal sebelum mempelajari Dynamic Analysis pada pertemuan berikutnya.
