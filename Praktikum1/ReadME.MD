# Laporan Praktikum 1: Aplikasi Pendaftaran Event

## Identitas
- **Nama:** Muhammad Naufal Hardy
- **NIM:** 4523210077

## Deskripsi
Pada praktikum ini, telah dibuat sebuah aplikasi pendaftaran event menggunakan PHP. Aplikasi ini memungkinkan pengguna untuk mendaftar dengan mengisi nama lengkap, email, dan tanggal lahir. Data yang berhasil divalidasi akan disimpan ke dalam file `pendaftar.txt`.

## Notes Pertemuan 2
- **Konsep Constant:** Digunakan untuk nilai yang tidak berubah, seperti nama event dan nama file pendaftar.
- **Konsep Global Variable:** Variabel `$status_message` dan `$error_messages` digunakan untuk memberikan feedback kepada pengguna.
- **Konsep Fungsi & Regex:** Fungsi `validateEmail` dan `validateDate` digunakan untuk memvalidasi format email dan tanggal lahir.
- **Konsep Form Handling:** Data dari form diproses menggunakan metode POST dan divalidasi sebelum disimpan.
- **Konsep File Handling:** Data pendaftar disimpan dalam file `pendaftar.txt` menggunakan fungsi `file_put_contents`.

## Struktur File
- `index.php`: File utama aplikasi yang berisi logika PHP dan tampilan HTML.
- `pendaftar.txt`: File untuk menyimpan data pendaftar.
- `ReadME.MD`: File dokumentasi untuk laporan praktikum.

## Output
Aplikasi menampilkan daftar peserta yang sudah mendaftar dalam bentuk tabel, serta pesan error jika ada input yang tidak valid.

## Screenshot
![Form Pendaftaran Event](attachments/screenshot.png)
