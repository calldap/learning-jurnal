# Week 07 — Dynamic Analysis Malware

## Ringkasan

Pada pertemuan ketujuh, saya mempelajari metode **Dynamic Analysis**, yaitu teknik analisis malware dengan menjalankan malware pada lingkungan yang aman untuk mengamati perilakunya secara langsung. Berbeda dengan Static Analysis yang hanya menganalisis file tanpa dieksekusi, Dynamic Analysis memungkinkan analis melihat aktivitas malware ketika sedang berjalan.

Pada materi ini juga diperkenalkan penggunaan **ANY.RUN** sebagai platform sandbox yang dapat digunakan untuk mengamati aktivitas malware secara real-time tanpa membahayakan sistem utama.

---

# Pembahasan Materi

## 1. Pengertian Dynamic Analysis

Dynamic Analysis merupakan metode analisis malware dengan cara menjalankan malware di lingkungan yang terisolasi sehingga seluruh aktivitasnya dapat diamati secara langsung.

Melalui metode ini, analis dapat memperoleh informasi yang tidak dapat diketahui hanya melalui Static Analysis, seperti perilaku malware setelah dieksekusi.

Beberapa tujuan Dynamic Analysis antara lain:

- Mengamati perilaku malware saat dijalankan.
- Mengetahui perubahan yang dilakukan terhadap sistem.
- Mengidentifikasi koneksi jaringan yang dibuat malware.
- Mengetahui proses yang dijalankan malware.

---

## 2. Penggunaan Sandbox

Untuk menghindari penyebaran malware ke sistem utama, proses Dynamic Analysis dilakukan menggunakan **Sandbox**.

Sandbox merupakan lingkungan virtual yang dirancang agar malware dapat dijalankan secara aman tanpa memengaruhi komputer asli.

Keuntungan menggunakan Sandbox antara lain:

- Sistem utama tetap aman.
- Aktivitas malware dapat direkam.
- Mempermudah proses investigasi.
- Hasil analisis dapat didokumentasikan.

---

## 3. Platform ANY.RUN

Pada materi ini saya dikenalkan dengan **ANY.RUN**, yaitu platform sandbox berbasis cloud yang banyak digunakan dalam analisis malware.

Melalui ANY.RUN, analis dapat mengamati berbagai aktivitas malware seperti:

- Process Tree
- Aktivitas File
- Registry Changes
- Network Connections
- DNS Request
- HTTP Request
- Proses yang dibuat malware

Platform ini juga menyediakan laporan analisis yang memudahkan analis memahami perilaku malware.

---

## 4. Informasi yang Diperoleh dari Dynamic Analysis

Ketika malware dijalankan, beberapa informasi penting yang dapat diamati antara lain:

- Process yang dibuat.
- File yang ditambahkan atau diubah.
- Registry yang dimodifikasi.
- Koneksi ke server tertentu.
- Aktivitas jaringan.
- Perubahan pada sistem operasi.

Informasi tersebut dapat digunakan untuk mengetahui tujuan serta tingkat bahaya dari malware yang sedang dianalisis.

---

## 5. Peran Dynamic Analysis

Dynamic Analysis memiliki peran penting dalam Malware Analysis karena mampu memperlihatkan perilaku malware yang tidak dapat diketahui hanya melalui analisis statis.

Dengan menggabungkan hasil Static Analysis dan Dynamic Analysis, seorang analis dapat memperoleh gambaran yang lebih lengkap mengenai karakteristik malware.

---

# Insight Minggu Ini

Pada minggu ini saya memahami bahwa Dynamic Analysis merupakan pelengkap dari Static Analysis. Jika Static Analysis membantu memahami struktur malware, maka Dynamic Analysis membantu memahami bagaimana malware benar-benar bekerja ketika dijalankan.

Saya juga mengetahui pentingnya penggunaan Sandbox agar proses analisis dapat dilakukan dengan aman tanpa membahayakan perangkat yang digunakan.

---

# Tools yang Dipelajari

- ANY.RUN
- Virtual Machine
- Wireshark
- Process Monitor (ProcMon)

---

# Refleksi Pembelajaran

## Apa yang Saya Pahami

Saya memahami konsep Dynamic Analysis beserta tujuan penggunaannya dalam Malware Analysis. Saya juga mengetahui bagaimana Sandbox seperti ANY.RUN digunakan untuk mengamati perilaku malware secara langsung serta informasi apa saja yang dapat diperoleh selama proses analisis.

## Apa yang Masih Membingungkan

Saya masih ingin mempelajari bagaimana malware dapat mendeteksi bahwa dirinya sedang dijalankan di lingkungan virtual atau sandbox. Selain itu, saya juga ingin mengetahui teknik yang digunakan analis untuk mengatasi mekanisme anti-virtual machine maupun anti-sandbox.

---

# Kesimpulan Pribadi

Pertemuan ketujuh memberikan pemahaman mengenai Dynamic Analysis sebagai metode untuk mengamati perilaku malware ketika dijalankan. Dengan memanfaatkan Sandbox seperti ANY.RUN, proses analisis dapat dilakukan secara aman sehingga berbagai aktivitas malware dapat diamati tanpa membahayakan sistem utama. Materi ini melengkapi pemahaman saya mengenai proses Malware Analysis yang sebelumnya telah dipelajari melalui Static Analysis.
