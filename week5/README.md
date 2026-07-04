# Week 05 — Pengenalan Malware Analysis

## Ringkasan

Pada pertemuan kelima, saya mulai mempelajari Malware Analysis sebagai salah satu penerapan Reverse Engineering dalam bidang keamanan siber. Materi menjelaskan tujuan dilakukannya analisis malware, tahapan umum analisis, serta dua pendekatan utama yang digunakan, yaitu Static Analysis dan Dynamic Analysis.

Melalui materi ini saya memahami bahwa proses analisis malware bertujuan untuk mengetahui perilaku suatu malware tanpa membahayakan sistem yang digunakan. Oleh karena itu, proses analisis harus dilakukan pada lingkungan yang aman seperti Virtual Machine atau Sandbox.

---

# Pembahasan Materi

## 1. Pengertian Malware Analysis

Malware Analysis merupakan proses untuk mempelajari karakteristik dan perilaku suatu malware agar dapat diketahui cara kerja, tujuan, serta dampak yang ditimbulkan terhadap sistem.

Proses analisis dilakukan untuk memperoleh informasi seperti:

- Cara malware dijalankan.
- Aktivitas yang dilakukan malware.
- Dampak terhadap sistem.
- Teknik penyebaran malware.
- Indikator yang dapat digunakan untuk mendeteksi malware.

Melalui materi ini saya memahami bahwa Malware Analysis merupakan bagian penting dalam proses investigasi keamanan siber.

---

## 2. Tujuan Malware Analysis

Beberapa tujuan utama Malware Analysis antara lain:

- Memahami cara kerja malware.
- Mengidentifikasi ancaman terhadap sistem.
- Menentukan metode pencegahan.
- Membantu proses investigasi insiden keamanan.
- Mengembangkan signature untuk antivirus atau sistem deteksi.

Analisis yang dilakukan tidak hanya bertujuan mengetahui nama malware, tetapi juga memahami perilaku yang ditimbulkan ketika malware dijalankan.

---

## 3. Metode Malware Analysis

Materi menjelaskan bahwa terdapat dua metode utama dalam melakukan analisis malware.

### Static Analysis

Static Analysis dilakukan tanpa menjalankan malware.

Analisis difokuskan pada:

- Struktur file.
- Strings.
- Header.
- Import Function.
- Disassembly.

### Dynamic Analysis

Dynamic Analysis dilakukan dengan menjalankan malware pada lingkungan yang aman sehingga perilaku malware dapat diamati secara langsung.

Informasi yang diperoleh antara lain:

- Aktivitas proses.
- Perubahan registry.
- Aktivitas file.
- Koneksi jaringan.
- Perubahan sistem.

Saya memahami bahwa kedua metode tersebut saling melengkapi untuk memperoleh hasil analisis yang lebih komprehensif.

---

## 4. Pentingnya Lingkungan Analisis

Materi juga menjelaskan bahwa malware tidak boleh dijalankan langsung pada sistem utama.

Beberapa lingkungan yang dapat digunakan antara lain:

- Virtual Machine (VM)
- Sandbox
- Lingkungan laboratorium yang terisolasi

Hal ini bertujuan untuk mencegah malware menyebar maupun merusak sistem yang digunakan untuk analisis.

---

# Insight Minggu Ini

Pada minggu kelima saya memahami bahwa Malware Analysis merupakan salah satu penerapan utama Reverse Engineering dalam bidang keamanan siber. Saya juga mengetahui bahwa proses analisis harus dilakukan secara aman menggunakan lingkungan yang terisolasi agar malware tidak membahayakan sistem utama.

---

# Tools yang Dipelajari

- Virtual Machine
- Sandbox
- Ghidra
- Wireshark

---

# Refleksi Pembelajaran

## Apa yang Saya Pahami

Saya memahami tujuan Malware Analysis serta dua metode utama yang digunakan, yaitu Static Analysis dan Dynamic Analysis. Saya juga mengetahui pentingnya menggunakan lingkungan yang aman ketika melakukan analisis malware.

## Apa yang Masih Membingungkan

Saya masih ingin mempelajari bagaimana memilih metode analisis yang paling sesuai untuk berbagai jenis malware serta bagaimana mempersiapkan lingkungan analisis yang aman.

---

# Kesimpulan Pribadi

Pertemuan kelima memberikan pemahaman dasar mengenai Malware Analysis sebagai salah satu penerapan Reverse Engineering. Saya memahami bahwa proses analisis malware bertujuan mengetahui karakteristik dan perilaku malware sehingga dapat digunakan untuk meningkatkan keamanan sistem dan membantu proses investigasi insiden keamanan.
