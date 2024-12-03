# Christmas Invitation Website

[![CodeFactor](https://www.codefactor.io/repository/github/danielwidhiarto/christmasinvitationwebsite/badge)](https://www.codefactor.io/repository/github/danielwidhiarto/christmasinvitationwebsite)

## Deskripsi

**Christmas Invitation Website** adalah platform interaktif yang dirancang untuk menyampaikan undangan perayaan Natal dengan fitur-fitur menarik dan responsif. Website ini mencakup hitung mundur menuju acara utama, informasi acara, galeri gambar, tanda tangan resmi, dan lokasi acara menggunakan Google Maps.

## Fitur

- **Countdown Interaktif**: Hitung mundur menuju acara Natal dengan tampilan yang estetis.
- **Detail Acara Utama**: Informasi lengkap tentang waktu, tanggal, dan lokasi acara.
- **Galeri Gambar**: Koleksi gambar kegiatan untuk memberikan gambaran acara.
- **Tanda Tangan Resmi**: Tanda tangan Ketua Panitia, Sekretaris, dan Ketua IBI untuk validasi resmi.
- **Lokasi Acara**: Peta interaktif melalui integrasi Google Maps.
- **Audio Latar Belakang**: Suasana hangat ditambah dengan musik latar yang diputar otomatis.

## Link Website

Akses website melalui tautan berikut: [Christmas Invitation Website](https://).

## Memulai

Ikuti langkah-langkah berikut untuk menjalankan website secara lokal:

1. **Clone Repository**  
   Salin repository ke komputer Anda:
   ```bash
   git clone https://github.com/saylendrayasin/invitation-ibi.git
   ```
2. **Buka File HTML**  
   Navigasikan ke direktori project dan buka file `index.html` di browser pilihan Anda.
3. **Eksplorasi Website**  
   Jelajahi fitur-fitur seperti hitung mundur, tanda tangan resmi, galeri, dan lokasi acara.

## Cara Penggunaan

### Penyesuaian Undangan Berdasarkan URL

1. **Nama Undangan**  
   Anda dapat menyesuaikan ucapan undangan dengan menambahkan parameter ke URL:

   - `?mr=John+Doe` → "Kami Mengundang Bapak John Doe, Pada Acara"
   - `?mrs=Jane+Doe` → "Kami Mengundang Ibu Jane Doe, Pada Acara"

2. **Prioritas Parameter**  
   Jika URL mengandung kedua parameter `mr` dan `mrs`, maka parameter `mr` akan diutamakan.

3. **Contoh URL**
   - Dengan `mr`:
     ```
     http://127.0.0.1:5500/index.html?mr=John+Doe
     ```
   - Dengan `mrs`:
     ```
     http://127.0.0.1:5500/index.html?mrs=Jane+Doe
     ```
   - Tanpa parameter:
     ```
     http://127.0.0.1:5500/index.html
     ```

### Fitur Interaktif

- **Countdown**: Lihat waktu tersisa menuju acara.
- **Galeri Gambar**: Nikmati gambar kegiatan pendahuluan acara.
- **Tanda Tangan Resmi**: Temukan tanda tangan Ketua Panitia, Sekretaris, dan Ketua IBI.
- **Lokasi Acara**: Gunakan peta Google Maps untuk menemukan lokasi acara.

## Struktur Kode

- **HTML**: Struktur website, termasuk elemen `#hero`, galeri, dan peta Google Maps.
- **CSS**: Gaya responsif yang dirancang untuk desktop, tablet, dan perangkat mobile.
- **JavaScript**: Fitur interaktif seperti hitung mundur, efek salju, dan mengganti teks berdasarkan URL.

## Kontribusi

Kami menyambut kontribusi untuk pengembangan **Christmas Invitation Website**. Fork repository ini dan kirimkan pull request untuk ide atau perbaikan Anda.

## Dukungan dan Masalah

Jika Anda membutuhkan dukungan atau ingin melaporkan masalah, silakan buka issue di [repository GitHub kami](https://github.com/danielwidhiarto/christmas-invitation-website).

## Lisensi

Proyek ini tersedia sebagai open source di bawah [Lisensi MIT](LICENSE).
