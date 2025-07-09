# Proyek Web Cek Kelas SDIT Al Mumtaz Pontianak

Ini adalah proyek web sederhana satu halaman yang dibuat untuk menampilkan informasi kelas. Dibuat menggunakan HTML dan Tailwind CSS (via CDN).

## Cara Deploy ke GitHub Pages

Untuk membuat aplikasi ini online menggunakan layanan gratis dari GitHub Pages, ikuti langkah-langkah berikut:

1.  **Inisialisasi Git**
    Pastikan Anda berada di direktori proyek (`C:\Users\Administrator\cek-kelas-sdit`), lalu jalankan perintah berikut di terminal atau command prompt:
    ```bash
    git init
    git add .
    git commit -m "Initial commit: Menambahkan file dasar proyek"
    ```

2.  **Buat Repositori di GitHub**
    - Buka [GitHub](https://github.com) dan buat sebuah repositori baru. Beri nama repositori sesuai keinginan Anda (misalnya, `cek-kelas-sdit`).
    - Jangan inisialisasi dengan `README` atau `.gitignore` dari sisi GitHub.

3.  **Hubungkan Proyek Lokal ke Repositori GitHub**
    - Salin URL repositori yang baru saja Anda buat.
    - Kembali ke terminal Anda dan jalankan perintah berikut (ganti `<URL_REPOSITORI_ANDA>` dengan URL yang Anda salin):
    ```bash
    git remote add origin <URL_REPOSITORI_ANDA>
    git branch -M main
    git push -u origin main
    ```

4.  **Aktifkan GitHub Pages**
    - Di halaman repositori GitHub Anda, klik tab **Settings**.
    - Di menu sebelah kiri, pilih **Pages**.
    - Di bawah "Build and deployment", pada bagian "Source", pilih **Deploy from a branch**.
    - Pastikan branch yang dipilih adalah `main` dan foldernya adalah `/(root)`.
    - Klik **Save**.

5.  **Selesai!**
    - Tunggu beberapa menit hingga proses build selesai. GitHub akan memberikan URL publik untuk situs Anda (contoh: `https://<username>.github.io/<nama-repo>/`).
    - Anda dapat mengunjungi URL tersebut untuk melihat aplikasi web Anda secara online.

