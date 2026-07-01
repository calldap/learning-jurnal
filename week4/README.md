# Week 04 — Metodologi, Tools, Hukum, dan Etika Reverse Engineering

## Ringkasan

Pada pertemuan keempat, saya mempelajari metodologi yang digunakan dalam proses Reverse Engineering. Materi menjelaskan tahapan analisis mulai dari pengumpulan informasi, proses analisis, hingga validasi hasil. Selain itu, saya juga dikenalkan dengan beberapa tools yang umum digunakan dalam Reverse Engineering serta memahami pentingnya aspek hukum dan etika dalam melakukan analisis perangkat lunak.

Materi ini memberikan pemahaman bahwa Reverse Engineering bukan hanya membutuhkan kemampuan teknis, tetapi juga harus dilakukan secara bertanggung jawab dengan memperhatikan peraturan dan etika yang berlaku.

---

# Pembahasan Materi

## 1. Metodologi Reverse Engineering

Reverse Engineering dilakukan melalui beberapa tahapan agar proses analisis berjalan secara sistematis.

### Information Extraction

Tahap pertama adalah mengumpulkan informasi sebanyak mungkin dari file executable tanpa melakukan perubahan terhadap file tersebut.

Informasi yang dapat diperoleh antara lain:

- Strings
- Import Function
- Export Function
- Header File
- Metadata
- Resources
- Struktur Binary

Tahap ini bertujuan memperoleh gambaran awal mengenai program yang akan dianalisis.

### Analysis / Modelling

Setelah informasi awal diperoleh, proses dilanjutkan dengan menganalisis struktur dan alur program.

Hal-hal yang biasanya dianalisis meliputi:

- Flow eksekusi program.
- Fungsi-fungsi penting.
- Algoritma yang digunakan.
- Mekanisme autentikasi.
- Teknik proteksi aplikasi.

Tahap ini merupakan inti dari Reverse Engineering karena bertujuan memahami logika program secara menyeluruh.

### Validation

Tahap terakhir adalah memastikan bahwa hasil analisis sesuai dengan perilaku program ketika dijalankan.

Validasi dapat dilakukan menggunakan:

- Debugging
- Dynamic Analysis
- Sandbox
- Proof of Concept (PoC)

Melalui proses validasi, analis dapat memastikan bahwa hasil analisis yang diperoleh sudah akurat.

---

## 2. Tools Reverse Engineering

Pada materi ini saya mempelajari beberapa tools yang sering digunakan dalam Reverse Engineering.

| Tools | Fungsi |
|--------|--------|
| IDA Pro | Interactive Disassembler untuk menganalisis executable. |
| Ghidra | Disassembler dan Decompiler yang membantu memahami struktur program. |
| OllyDbg | Debugger untuk melakukan analisis dinamis. |
| Wireshark | Menganalisis komunikasi jaringan suatu aplikasi. |

Saya memahami bahwa setiap tools memiliki fungsi yang berbeda dan saling melengkapi dalam proses analisis.

---

## 3. Aspek Hukum

Reverse Engineering harus dilakukan dengan memperhatikan aturan hukum yang berlaku.

Materi menjelaskan bahwa terdapat beberapa kondisi yang memperbolehkan Reverse Engineering, di antaranya:

- Penelitian keamanan (Security Research).
- Meningkatkan interoperabilitas perangkat lunak.
- Analisis untuk tujuan pendidikan.
- Pengujian keamanan sistem.

Saya juga diperkenalkan dengan konsep **Digital Millennium Copyright Act (DMCA)** yang mengatur perlindungan hak cipta perangkat lunak beserta beberapa pengecualian yang diizinkan.

---

## 4. Etika Reverse Engineering

Selain aspek hukum, seorang analis juga harus memahami etika profesional.

Beberapa prinsip etika yang dibahas antara lain:

- Menghormati Hak Kekayaan Intelektual (HKI).
- Tidak menggunakan hasil analisis untuk tindakan ilegal.
- Mematuhi lisensi perangkat lunak.
- Melakukan Responsible Disclosure apabila menemukan kerentanan keamanan.

Materi ini membuat saya memahami bahwa kemampuan teknis harus selalu diimbangi dengan tanggung jawab profesional.

---

## 5. Tantangan Reverse Engineering

Perkembangan teknologi membuat proses Reverse Engineering menjadi semakin kompleks.

Beberapa tantangan yang dibahas meliputi:

- Code Obfuscation.
- Anti-Debugging.
- Anti-Virtual Machine.
- Packing dan Encryption.
- Kompleksitas software modern.

Selain itu, dosen juga menjelaskan bahwa perkembangan Artificial Intelligence (AI) diperkirakan akan membantu proses Reverse Engineering melalui otomatisasi analisis dan identifikasi pola pada binary.

---

# Insight Minggu Ini

Saya memahami bahwa Reverse Engineering bukan sekadar menggunakan tools untuk membongkar aplikasi, tetapi merupakan proses analisis yang memiliki tahapan yang jelas. Saya juga menyadari bahwa penggunaan tools harus disertai dengan pemahaman terhadap hukum dan etika agar hasil analisis dapat dipertanggungjawabkan.

---

# Tools yang Dipelajari

- IDA Pro
- Ghidra
- OllyDbg
- Wireshark

---

# Refleksi Pembelajaran

## Apa yang Saya Pahami

Saya memahami tahapan utama dalam Reverse Engineering mulai dari Information Extraction, Analysis, hingga Validation. Saya juga mengetahui fungsi beberapa tools utama yang akan digunakan dalam praktikum serta pentingnya memahami aspek hukum dan etika selama melakukan analisis.

## Apa yang Masih Membingungkan

Saya masih ingin mempelajari penggunaan setiap tools secara langsung, terutama proses debugging menggunakan OllyDbg dan teknik decompiling menggunakan Ghidra. Selain itu, saya ingin memahami lebih dalam bagaimana teknik anti-debugging bekerja dan bagaimana cara mengatasinya.

---

# Kesimpulan Pribadi

Pertemuan keempat memberikan pemahaman mengenai metodologi Reverse Engineering yang sistematis, penggunaan berbagai tools analisis, serta pentingnya aspek hukum dan etika dalam proses Reverse Engineering. Materi ini menjadi dasar sebelum mempelajari analisis malware menggunakan metode static analysis dan dynamic analysis pada pertemuan selanjutnya.
