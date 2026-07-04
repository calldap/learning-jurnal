# Week 08 — Perbandingan Static Analysis dan Dynamic Analysis

## Ringkasan

Pada pertemuan terakhir, saya mempelajari perbedaan antara Static Analysis dan Dynamic Analysis sebagai dua metode utama dalam Malware Analysis. Materi menjelaskan kelebihan, kekurangan, serta kondisi yang tepat untuk menggunakan masing-masing metode. Selain itu, saya melakukan refleksi terhadap seluruh materi yang telah dipelajari mulai dari dasar Reverse Engineering hingga penerapan analisis malware.

Melalui materi ini saya memahami bahwa kedua metode tersebut bukanlah metode yang saling menggantikan, melainkan saling melengkapi agar proses analisis malware menjadi lebih komprehensif.

---

# Pembahasan Materi

## 1. Static Analysis

Static Analysis merupakan metode analisis yang dilakukan tanpa menjalankan malware. Proses ini berfokus pada pemeriksaan struktur file executable untuk memperoleh informasi awal mengenai karakteristik malware.

Beberapa informasi yang dapat diperoleh melalui Static Analysis antara lain:

- Jenis file executable.
- Header file.
- Strings.
- Import dan Export Function.
- Struktur program.
- Disassembly.

### Kelebihan Static Analysis

- Aman karena malware tidak dijalankan.
- Proses analisis relatif cepat.
- Dapat memperoleh informasi awal mengenai malware.
- Risiko infeksi terhadap sistem sangat kecil.

### Kekurangan Static Analysis

- Tidak dapat melihat perilaku malware secara langsung.
- Sulit menganalisis malware yang menggunakan teknik obfuscation atau packing.
- Tidak semua aktivitas malware dapat diketahui.

---

## 2. Dynamic Analysis

Dynamic Analysis dilakukan dengan menjalankan malware pada lingkungan yang aman seperti Virtual Machine atau Sandbox.

Melalui metode ini, analis dapat mengamati perilaku malware secara langsung ketika dijalankan.

Informasi yang dapat diperoleh meliputi:

- Aktivitas proses.
- Perubahan file.
- Modifikasi registry.
- Aktivitas jaringan.
- Koneksi ke server Command and Control (C2).
- Perubahan konfigurasi sistem.

### Kelebihan Dynamic Analysis

- Menampilkan perilaku malware secara nyata.
- Memudahkan identifikasi aktivitas berbahaya.
- Dapat mengetahui komunikasi jaringan malware.
- Membantu proses investigasi insiden keamanan.

### Kekurangan Dynamic Analysis

- Memerlukan lingkungan analisis yang aman.
- Proses analisis membutuhkan waktu lebih lama.
- Beberapa malware mampu mendeteksi Virtual Machine atau Sandbox sehingga tidak menjalankan seluruh fungsinya.

---

## 3. Perbandingan Static Analysis dan Dynamic Analysis

| Aspek | Static Analysis | Dynamic Analysis |
|--------|-----------------|------------------|
| Malware dijalankan | Tidak | Ya |
| Tingkat risiko | Rendah | Lebih tinggi (dikendalikan dengan Sandbox) |
| Fokus analisis | Struktur file | Perilaku malware |
| Kecepatan analisis | Lebih cepat | Lebih lambat |
| Informasi yang diperoleh | Struktur internal | Aktivitas ketika dijalankan |

Materi ini menunjukkan bahwa kedua metode memiliki kelebihan dan kekurangan masing-masing sehingga sering digunakan secara bersamaan.

---

## 4. Hubungan Reverse Engineering dan Malware Analysis

Setelah mempelajari seluruh materi, saya memahami bahwa Reverse Engineering menjadi dasar dalam proses Malware Analysis.

Reverse Engineering membantu analis untuk:

- Memahami struktur executable.
- Mengetahui logika program.
- Mengidentifikasi fungsi penting.
- Memahami perilaku malware.

Sementara itu, Malware Analysis memanfaatkan hasil Reverse Engineering untuk mengetahui ancaman yang ditimbulkan oleh malware terhadap sistem.

---

# Insight Minggu Ini

Materi minggu terakhir membuat saya memahami bahwa Static Analysis dan Dynamic Analysis memiliki fungsi yang saling melengkapi. Static Analysis memberikan gambaran mengenai struktur malware, sedangkan Dynamic Analysis menunjukkan bagaimana malware benar-benar berperilaku ketika dijalankan.

Saya juga menyadari bahwa Reverse Engineering merupakan salah satu kemampuan yang sangat penting bagi seorang Security Engineer karena dapat digunakan dalam berbagai aktivitas seperti Malware Analysis, Digital Forensics, Vulnerability Assessment, hingga Incident Response.

---

# Tools yang Dipelajari

- Ghidra
- IDA Pro
- ANY.RUN
- Wireshark
- Virtual Machine

---

# Refleksi Pembelajaran

## Apa yang Saya Pahami

Selama delapan minggu pembelajaran, saya memperoleh pemahaman mengenai konsep dasar Reverse Engineering, ruang lingkup penerapannya, metodologi analisis, penggunaan berbagai tools, serta teknik Malware Analysis menggunakan metode Static Analysis dan Dynamic Analysis.

Saya juga memahami bahwa keberhasilan proses analisis tidak hanya bergantung pada tools yang digunakan, tetapi juga pada kemampuan analis dalam memahami struktur executable, perilaku program, serta aspek hukum dan etika yang berlaku.

## Apa yang Masih Membingungkan

Saya masih ingin mempelajari teknik Reverse Engineering yang lebih kompleks, seperti analisis malware yang menggunakan obfuscation, packing, maupun anti-debugging. Selain itu, saya juga tertarik mempelajari teknik reverse engineering pada aplikasi Android dan perangkat IoT.

---

# Kesimpulan Pribadi

Rangkaian pembelajaran Reverse Engineering selama delapan minggu memberikan saya pemahaman yang lebih luas mengenai proses analisis perangkat lunak dan malware. Saya mempelajari konsep dasar Reverse Engineering, jenis-jenisnya, berbagai penerapan dalam keamanan siber, metodologi analisis, penggunaan tools, hingga teknik Static Analysis dan Dynamic Analysis.

Materi ini menjadi bekal awal bagi saya untuk mempelajari bidang Cybersecurity, khususnya Malware Analysis dan Digital Forensics, secara lebih mendalam pada masa mendatang.
