# Janji
Saya Ismail Fatih Raihan dengan NIM 2307840 mengerjakan Tugas Praktikum 1 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.  

# Aplikasi Manajemen Data Mahasiswa

## 📌 Deskripsi Program

Aplikasi ini merupakan sistem manajemen data mahasiswa berbasis GUI yang dikembangkan menggunakan **Java Swing**. Aplikasi ini memungkinkan pengguna untuk menambah, memperbarui, menghapus, dan menampilkan data mahasiswa yang terdiri dari **NIM, Nama, Jenis Kelamin, dan Jurusan**.

## 🛠️ Fitur Program

✅ **Menampilkan daftar mahasiswa** dalam tabel.

✅ **Menambahkan mahasiswa baru** dengan input NIM, Nama, Jenis Kelamin, dan Jurusan.

✅ **Memperbarui data mahasiswa** yang sudah ada.

✅ **Menghapus mahasiswa** dengan konfirmasi.

✅ **Form otomatis dibersihkan** setelah aksi dilakukan.

## 📐 Desain Program

### **Struktur Data Mahasiswa**
Setiap mahasiswa direpresentasikan dengan class `Mahasiswa`, yang memiliki atribut berikut:
- **`nim`** (String) → Nomor Induk Mahasiswa.
- **`nama`** (String) → Nama lengkap mahasiswa.
- **`jenisKelamin`** (String) → Jenis kelamin mahasiswa (Laki-laki/Perempuan).
- **`jurusan`** (String) → Program studi mahasiswa.

### **Desain GUI**
Aplikasi ini dirancang menggunakan **Java Swing** dengan komponen berikut:
- **`JTable`** → Menampilkan daftar mahasiswa.
- **`JTextField`** → Input untuk NIM dan Nama.
- **`JComboBox`** → Pilihan untuk Jenis Kelamin dan Jurusan.
- **`JButton`** → Untuk aksi tambah, perbarui, hapus, dan reset.
- **`JPanel`** → Untuk mengatur layout tampilan.
- **`JOptionPane`** → Untuk menampilkan konfirmasi dan pesan notifikasi.

Tata letak utama menggunakan **`BorderLayout`**, di mana:
- **Bagian Utama (Center)** → `JTable` untuk menampilkan data.
- **Bagian Atas (North)** → Form input (NIM, Nama, Jenis Kelamin, Jurusan).
- **Bagian Bawah (South)** → Tombol aksi (Add, Update, Delete, Clear).

## 🔄 Penjelasan Alur Program

1️⃣ **Pengguna membuka aplikasi** dan melihat tabel daftar mahasiswa.

2️⃣ **Pengguna dapat menambahkan mahasiswa baru** dengan mengisi **NIM, Nama, Jenis Kelamin, dan Jurusan**, lalu menekan tombol **Add**.

3️⃣ **Jika ingin memperbarui data**, pengguna memilih baris pada tabel, lalu mengedit dan menekan tombol **Update**.

4️⃣ **Jika ingin menghapus data**, pengguna memilih baris lalu menekan tombol **Delete**, dengan konfirmasi sebelum menghapus.

5️⃣ **Setiap perubahan langsung diperbarui di tabel**, dan **form otomatis dibersihkan** setelah aksi.


## 📷 Dokumentasi Tampilan
![Screenshot (140)](https://github.com/user-attachments/assets/f3441cd5-f9e2-4130-a528-785bd5192efc)


## 🏗️ Teknologi yang Digunakan

- **Java Swing** – untuk tampilan GUI
- **ArrayList** – untuk penyimpanan data sementara
- **JTable** – untuk menampilkan daftar mahasiswa
- **JComboBox** – untuk memilih jenis kelamin & jurusan
- **JOptionPane** – untuk konfirmasi dan pesan notifikasi

