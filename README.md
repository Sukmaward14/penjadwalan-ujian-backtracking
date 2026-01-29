# penjadwalan-ujian-backtracking

## 📌 Deskripsi Proyek
Sistem Penjadwalan Ujian ini merupakan aplikasi yang dirancang untuk membantu proses penyusunan jadwal ujian secara otomatis dan terstruktur. Sistem ini menggunakan **algoritma backtracking** untuk menghindari konflik jadwal, seperti bentrok mata kuliah, ruangan, dan sesi ujian.

Aplikasi ini bertujuan untuk menghasilkan jadwal ujian yang optimal, efisien, dan sesuai dengan batasan (constraint) yang telah ditentukan.

---

## 🎯 Tujuan
- Mengimplementasikan algoritma **backtracking** dalam penyusunan jadwal ujian.
- Menghindari konflik jadwal ujian antar mata kuliah.
- Membantu admin dalam mengelola data mata kuliah, ruangan, dan sesi ujian.
- Menyediakan sistem penjadwalan ujian berbasis web yang mudah digunakan.

---

## 🧠 Algoritma yang Digunakan
**Backtracking**

Algoritma backtracking bekerja dengan cara:
1. Menempatkan mata kuliah ke dalam slot jadwal tertentu.
2. Mengecek apakah penempatan tersebut melanggar aturan.
3. Jika terjadi konflik, sistem akan kembali (backtrack) ke langkah sebelumnya dan mencoba kemungkinan lain.
4. Proses berlanjut hingga semua mata kuliah mendapatkan jadwal yang valid.

---

## 🧩 Fitur Aplikasi
- Login dan autentikasi pengguna
- Manajemen data mata kuliah
- Manajemen data ruangan
- Penentuan sesi ujian
- Proses penjadwalan ujian otomatis
- Tampilan jadwal ujian
- Pengujian sistem menggunakan **Black Box Testing**

---

## 🧪 Pengujian Sistem
Metode pengujian yang digunakan adalah **Black Box Testing**, yang berfokus pada:
- Pengujian fungsi login
- Pengelolaan data mata kuliah
- Proses penjadwalan ujian
- Kesesuaian output dengan input yang diberikan

Hasil pengujian menunjukkan bahwa seluruh fitur utama sistem berjalan dengan baik dan sesuai dengan kebutuhan pengguna.

---
