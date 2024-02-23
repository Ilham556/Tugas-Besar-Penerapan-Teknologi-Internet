# QuakeVigilant - Aplikasi Pemantauan Gempa Bumi

## Nama Anggota Kelompok:
- Muhammad Ilham Gymnastiar - 10121124
- Abdul Azis Alghifari - 10121125
- Acep Alinurdin - 10121140

### Tentang QuakeVigilant
QuakeVigilant adalah aplikasi berbasis web yang dibangun menggunakan framework Python bernama Streamlit. Aplikasi ini bertujuan untuk membantu masyarakat dalam mitigasi bencana gempa bumi. Nama "QuakeVigilant" diambil dari kata "quake" yang berarti gempa dan "vigilant" yang berarti waspada, sehingga secara harfiah dapat diartikan sebagai "Waspada terhadap gempa bumi".

### Fitur untuk Pengguna
- Pemantauan gempa bumi secara real-time.
- Informasi daerah rawan gempa bumi.
- Grafik visualisasi gempa bumi.
- Download data gempa bumi.
- Artikel mengenai mitigasi gempa bumi.
- Login dan logout.
- Edit profil pengguna.

### Fitur untuk Admin
- Dashboard ringkasan data gempa bumi, pengguna, dan artikel.
- CRUD (Create, Read, Update, Delete) data gempa bumi.
- CRUD pengguna.
- CRUD artikel.
- Login dan logout.
- Edit profil admin.

### Tutorial Penggunaan
1. Install semua library yang diperlukan dengan menjalankan perintah:
   ```
   cd <lokasi_folder>
   pip install -r requirements.txt
   ```

2. Import database dengan langkah-langkah berikut:
   - Buat database dengan perintah:
     ```
     create database db_quakevigilant
     ```
   - Gunakan database yang baru dibuat:
     ```
     use database db_quakevigilant
     ```
   - Import database dari file `mysql/db_quakevigilant.sql` dengan perintah:
     ```
     source path/to/your/database mysql/db_quakevigilant.sql
     ```

3. Jalankan aplikasi dengan perintah:
   ```
   cd <lokasi_folder>
   streamlit run main.py
   ```

Dengan adanya QuakeVigilant, diharapkan dapat memberikan kontribusi dalam usaha mitigasi bencana gempa bumi dan memberikan informasi yang berguna kepada masyarakat.
