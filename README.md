# SDown
**DYOR** Gunakan sesuai research kalaian pribadi agar tidak mengalami kerugian.

## Catatan
Pastikan untuk mengatur konfigurasi di file config.json. Hal yang wajib diisi adalah token, app_id, dan email.

**Cara Mendapatkan Token dan App ID**
---
1. Buka ekstensi di Chrome. 
2. Klik ikon menu di pojok kanan atas, lalu masuk ke bagian dashboard.
3. Buka Inspect (Klik Kanan > Inspect), lalu pilih tab Network.
4. Cari file yang memuat getpoint?appid=. Jika file ini belum muncul, ulangi langkah-langkah membuka    dan menutup dashboard sambil memperhatikan bagian Network di Inspect.
5. Liat contoh pada file image *dawn.png*

> **Catatan:** Jika Inspect menunjukkan undefined pada *app_id*, Anda bisa mengabaikan *app_id* atau mencoba kode tanpa memasukkannya di *config.json*.

## Cara penginstalan
---

1. **Clone Project**
   ```bash
   git clone https://github.com/zeevana/xdone.git

2. **Masuk ke Direktori**
   ```bash
   cd xdone

3. **Install Dependencies dari requirements.txt**
   ```bash
   pip3 install -r requirements.txt

4. **Install Python 3 dan pip**
   ```bash
   sudo apt update
   sudo apt install python3 python3-pip -y

5. **Jalankan Program**
   ```bash
   python3 main.py
