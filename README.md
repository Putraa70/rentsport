# RentSport - Sistem Pemesanan Lapangan Olahraga

**RentSport** adalah aplikasi berbasis web yang memungkinkan pengguna untuk melakukan **pemesanan lapangan olahraga** (seperti futsal, badminton, dan tenis) dengan sistem yang terintegrasi. Aplikasi ini memungkinkan pengguna untuk **melakukan reservasi lapangan**, melakukan **pembayaran online**, serta memberi **rating dan review** lapangan yang mereka sewa.

## Fitur Utama

1. **Login dan Registrasi**
   - Pengguna dapat **login** menggunakan akun yang terdaftar atau melakukan **registrasi** untuk membuat akun baru.
   - Terdapat dua jenis akun: **Pengguna** (penyewa lapangan) dan **Admin** (pemilik lapangan yang mengelola lapangan).

2. **Dashboard Pengguna**
   - Pengguna dapat memilih **jenis lapangan** yang tersedia (futsal, badminton, tenis).
   - Melakukan **pemeriksaan ketersediaan lapangan** berdasarkan waktu dan tanggal.
   - Melakukan **reservasi lapangan** dan **pembayaran online** untuk konfirmasi pemesanan.
   - Mendapatkan **notifikasi otomatis** jika pemesanan berhasil atau ada perubahan jadwal.

3. **Dashboard Admin**
   - Admin dapat **mengelola jadwal lapangan**, menambah atau mengubah lapangan yang tersedia.
   - Admin dapat **melihat reservasi yang masuk**, serta **mengonfirmasi atau menolak pemesanan**.
   - Admin juga dapat melihat **laporan transaksi** terkait pemesanan lapangan.

4. **Backup Database**
   - Sistem melakukan **backup database otomatis** secara berkala, termasuk data pemesanan, transaksi, dan review lapangan.
   - **Script backup otomatis** menggunakan timestamp untuk menyimpan file backup dengan nama yang berbeda setiap kali.

---

## Teknologi yang Digunakan

- **Backend**: PHP, MySQL
- **Frontend**: HTML, CSS (Bootstrap), JavaScript.
- **Database**: MySQL
- **Fitur Lain**:
  - **Stored Procedures**: Untuk transaksi pemesanan dan konfirmasi.
  - **Stored Functions**: Untuk perhitungan biaya sewa lapangan.
  - **Triggers**: Untuk mengirimkan notifikasi atau memperbarui status secara otomatis.

---

## Instalasi

1. **Clone Repository**
   - Clone repositori ini ke komputer lokal:
     ```bash
     git clone https://github.com/username/rentsport.git
     ```

2. **Masuk ke Direktori Proyek**
   ```bash
   cd rentsport
