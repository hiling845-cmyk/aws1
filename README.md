# Dashboard Stasiun Cuaca AWS (Realtime Firebase)

File ini adalah *source code* HTML yang Anda kirimkan sebelumnya, yang sudah dikemas menjadi file siap unduh. Kode ini berfungsi untuk menampilkan data cuaca secara langsung (*realtime*) dari Firebase dengan antarmuka bergaya Stasiun Klimatologi BMKG.

## Persyaratan Menjalankan
Karena kode menggunakan *Firebase SDK versi Modular* (`<script type="module">`), file HTML ini tidak bisa langsung dijalankan dengan cara di-klik dua kali (aturan keamanan CORS browser akan memblokirnya).

**Cara membukanya:**
1. Ekstrak file zip ini ke dalam satu folder.
2. Gunakan **Local Web Server**. 
   - **Bila menggunakan VS Code:** Install ekstensi "Live Server", klik kanan pada file `index.html` dan pilih *Open with Live Server*.
   - **Bila menggunakan Python (Terminal/CMD):** Buka terminal di folder tersebut, ketik `python -m http.server`, lalu buka alamat `http://localhost:8000` di *browser*.

## Isi File
- `index.html` : Berisi struktur tampilan dashboard Stasiun Cuaca beserta integrasi JavaScript untuk Firebase Realtime Database.
- `README.md` : Instruksi penggunaan.
