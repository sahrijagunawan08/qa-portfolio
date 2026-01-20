# Test Case Login – SauceDemo

## Informasi Aplikasi
- Nama Aplikasi: SauceDemo
- URL: https://www.saucedemo.com/
- Fitur yang Diuji: Login
- Tester: Sahrija Gunawan

---

## TC-LOGIN-001
**Skenario:** Login dengan username dan password valid  

**Data Uji:**
- Username: standard_user  
- Password: secret_sauce  

**Langkah Pengujian:**
1. Buka halaman login SauceDemo
2. Masukkan username valid
3. Masukkan password valid
4. Klik tombol Login

**Expected Result:**  
Pengguna berhasil login dan diarahkan ke halaman Products

---

## TC-LOGIN-002
**Skenario:** Login dengan username valid dan password tidak valid  

**Langkah Pengujian:**
1. Buka halaman login
2. Masukkan username valid
3. Masukkan password tidak valid
4. Klik tombol Login

**Expected Result:**  
Pesan error ditampilkan bahwa username atau password tidak sesuai

---

## TC-LOGIN-003
**Skenario:** Login dengan username tidak terdaftar  

**Langkah Pengujian:**
1. Buka halaman login
2. Masukkan username tidak valid
3. Masukkan password valid
4. Klik tombol Login

**Expected Result:**  
Pesan error ditampilkan bahwa user tidak ditemukan

---

## TC-LOGIN-004
**Skenario:** Login dengan username dan password kosong  

**Langkah Pengujian:**
1. Buka halaman login
2. Biarkan field username kosong
3. Biarkan field password kosong
4. Klik tombol Login

**Expected Result:**  
Pesan error “Username is required” ditampilkan

---

## TC-LOGIN-005
**Skenario:** Login dengan password kosong  

**Langkah Pengujian:**
1. Buka halaman login
2. Masukkan username valid
3. Biarkan password kosong
4. Klik tombol Login

**Expected Result:**  
Pesan error “Password is required” ditampilkan

---

## TC-LOGIN-006
**Skenario:** Verifikasi input password tersembunyi  

**Langkah Pengujian:**
1. Buka halaman login
2. Masukkan password pada field password

**Expected Result:**  
Karakter password ditampilkan dalam bentuk tersembunyi (masking)

---

## TC-LOGIN-007
**Skenario:** Login menggunakan akun locked out  

**Data Uji:**
- Username: locked_out_user  
- Password: secret_sauce  

**Langkah Pengujian:**
1. Buka halaman login
2. Masukkan username locked out
3. Masukkan password
4. Klik tombol Login

**Expected Result:**  
Pesan error ditampilkan bahwa user telah dikunci
