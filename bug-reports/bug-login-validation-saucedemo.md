# Bug Report – Validasi Login SauceDemo

## Judul Bug
Pesan validasi login hanya menampilkan error username saat password sudah diisi

## Environment
- Aplikasi: SauceDemo
- URL: https://www.saucedemo.com/
- Browser: Google Chrome (versi terbaru)
- Sistem Operasi: Windows 10

## Langkah Reproduksi
1. Buka halaman login SauceDemo
2. Biarkan field Username kosong
3. Masukkan password "secret_sauce"
4. Klik tombol Login

## Hasil yang Diharapkan
Pesan validasi menampilkan informasi yang jelas mengenai field yang harus diisi

## Hasil Aktual
Pesan error yang muncul:
Epic sadface: Username is required

## Severity
Medium

## Priority
Medium

## Status
Open

## Catatan
Pesan error berpotensi membingungkan pengguna karena hanya menampilkan error username meskipun password telah diisi.
