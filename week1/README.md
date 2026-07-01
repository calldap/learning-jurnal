# Week 01 — Introduction to Reverse Engineering

## Ringkasan

Pada pertemuan pertama, saya mempelajari konsep dasar Reverse Engineering (RE) sebagai proses untuk memahami cara kerja suatu perangkat lunak atau sistem tanpa memiliki source code asli. Materi juga membahas ruang lingkup Reverse Engineering, penerapannya dalam keamanan siber, interoperabilitas perangkat lunak, analisis malware, metodologi yang digunakan, hingga aspek hukum dan etika yang harus dipatuhi.

Selain memahami konsep dasar, saya juga mulai mengenal berbagai tools yang umum digunakan dalam Reverse Engineering seperti IDA Pro, Ghidra, OllyDbg, dan Wireshark. Materi minggu ini memberikan gambaran mengenai pentingnya Reverse Engineering sebagai salah satu kemampuan yang dibutuhkan dalam bidang keamanan siber.

---

# Pembahasan Materi

## 1. Pendahuluan Reverse Engineering

Reverse Engineering (RE) adalah proses membongkar atau mengkaji ulang suatu perangkat lunak, perangkat keras, maupun protokol komunikasi untuk memahami cara kerjanya. Tujuan utama dari Reverse Engineering bukan hanya memperoleh informasi mengenai struktur internal suatu sistem, tetapi juga memahami logika dan mekanisme yang digunakan oleh sistem tersebut.

Melalui materi ini saya memahami bahwa proses analisis dilakukan terhadap executable atau binary tanpa harus memiliki dokumentasi maupun source code asli.

---

## 2. Definisi dan Ruang Lingkup

Pada pertemuan ini saya mempelajari bahwa Reverse Engineering memiliki ruang lingkup yang cukup luas, yaitu:

### Software Reverse Engineering
Melakukan analisis terhadap executable atau binary untuk memahami struktur program dan logika yang digunakan.

### Hardware Reverse Engineering
Menganalisis perangkat keras guna mengetahui desain maupun cara kerja komponen fisiknya.

### Protocol Reverse Engineering
Mempelajari format komunikasi data agar perangkat yang berbeda dapat saling berkomunikasi.

Saya memahami bahwa Reverse Engineering tidak hanya digunakan pada software, tetapi juga pada berbagai sistem teknologi lainnya.

---

## 3. Area Penerapan Reverse Engineering

Materi menjelaskan beberapa bidang utama yang memanfaatkan Reverse Engineering.

### Keamanan Siber

Dalam bidang keamanan siber, Reverse Engineering digunakan untuk:

- Mencari kerentanan (vulnerability research).
- Melakukan penetration testing terhadap aplikasi.
- Mengaudit keamanan aplikasi untuk memastikan tidak terdapat backdoor.

### Interoperabilitas

Reverse Engineering juga digunakan untuk:

- Memahami API yang tidak terdokumentasi.
- Memungkinkan perangkat lunak lama tetap berjalan pada platform baru.
- Membantu driver perangkat keras dapat digunakan pada sistem operasi yang berbeda.

### Analisis Malware

Pada analisis malware, Reverse Engineering dimanfaatkan untuk:

- Membongkar kode berbahaya.
- Mengidentifikasi server Command and Control (C2).
- Menentukan metode penyebaran malware.
- Menemukan teknik persistence yang digunakan malware.

Dari materi ini saya memahami bahwa Reverse Engineering merupakan salah satu teknik utama dalam malware analysis.

---

## 4. Metodologi dan Alat Reverse Engineering

Saya mempelajari bahwa proses Reverse Engineering umumnya terdiri dari beberapa tahapan.

### Disassembler

Digunakan untuk mengubah machine code menjadi bahasa assembly sehingga lebih mudah dipahami.

### Decompiler

Digunakan untuk mengubah binary menjadi pseudo-code yang menyerupai bahasa tingkat tinggi.

### Debugger

Digunakan untuk menjalankan program secara dinamis sehingga perilaku aplikasi dapat diamati ketika sedang berjalan.

Tools yang diperkenalkan pada minggu pertama meliputi:

| Tools | Fungsi |
|--------|--------|
| IDA Pro | Interactive Disassembler |
| Ghidra | Disassembler dan Decompiler |
| OllyDbg | Debugger |
| Wireshark | Analisis lalu lintas jaringan |

---

## 5. Aspek Hukum

Materi juga membahas aspek hukum yang berkaitan dengan Reverse Engineering, khususnya Digital Millennium Copyright Act (DMCA).

Beberapa pengecualian yang diperbolehkan antara lain:

- Reverse Engineering untuk interoperabilitas perangkat lunak.
- Penelitian keamanan (security research).
- Modifikasi perangkat lunak untuk kebutuhan aksesibilitas.

Saya memahami bahwa kegiatan Reverse Engineering harus dilakukan sesuai aturan hukum yang berlaku.

---

## 6. Etika Reverse Engineering

Selain aspek hukum, dosen juga menjelaskan pentingnya etika dalam melakukan Reverse Engineering.

Beberapa prinsip etika yang harus diterapkan adalah:

- Menghormati Hak Kekayaan Intelektual (HAKI).
- Tidak menggunakan hasil Reverse Engineering untuk pembajakan perangkat lunak.
- Mematuhi kebijakan lisensi perangkat lunak.
- Melakukan responsible disclosure apabila menemukan kerentanan keamanan.

Materi ini mengingatkan saya bahwa kemampuan teknis harus selalu diimbangi dengan tanggung jawab profesional.

---

## 7. Tantangan dan Masa Depan Reverse Engineering

Pada bagian akhir materi dijelaskan beberapa tantangan yang dihadapi dalam Reverse Engineering.

### Tantangan Saat Ini

- Obfuscation (pengaburan kode).
- Teknik Anti-Debugging.

### Masa Depan

Perkembangan Artificial Intelligence (AI) diperkirakan akan membantu proses analisis binary menjadi lebih cepat melalui otomatisasi dan analisis yang lebih efisien.

---

# Insight Minggu Ini

Dari materi minggu pertama saya memahami bahwa Reverse Engineering bukan hanya proses membongkar software, tetapi merupakan proses analisis yang sistematis untuk memahami cara kerja suatu sistem. Reverse Engineering memiliki banyak penerapan dalam keamanan siber, interoperabilitas, maupun analisis malware. Selain kemampuan teknis, saya juga menyadari pentingnya memahami aspek hukum dan etika agar proses analisis dilakukan secara bertanggung jawab.

---

# Tools yang Dipelajari

- IDA Pro
- Ghidra
- OllyDbg
- Wireshark

---

# Refleksi Pembelajaran

## Apa yang Saya Pahami

Saya memahami pengertian Reverse Engineering, ruang lingkup penerapannya, manfaat dalam keamanan siber, serta metodologi dasar yang digunakan dalam proses analisis. Saya juga mulai mengenal beberapa tools yang akan digunakan pada praktikum berikutnya.

## Apa yang Masih Membingungkan

Saya masih ingin memahami bagaimana proses disassembler mengubah machine code menjadi assembly, bagaimana decompiler menghasilkan pseudo-code, serta bagaimana melakukan analisis executable secara langsung menggunakan Ghidra maupun IDA Pro.

---

# Kesimpulan Pribadi

Materi minggu pertama memberikan fondasi yang kuat mengenai Reverse Engineering, mulai dari konsep dasar, area penerapan, metodologi, tools, hingga aspek hukum dan etika. Dengan memahami materi ini, saya memiliki gambaran awal mengenai proses analisis software yang akan dipelajari lebih mendalam pada pertemuan selanjutnya.
