
# README – Sistem Event Organizer

## Deskripsi
Aplikasi ini dibangun menggunakan Node.js dan Express.js sebagai backend, dan HTML, CSS, Javascript sebagai front end. Juga menggunakan SQL server sebagai database.

## Struktur Folder

```
.
├── index.js             -> Kode dan Logika Backend
├── db.js                -> Konfigurasi koneksi ke SQL Server
├── views/               -> Template tampilan berbasis EJS
├── public/              -> Asset statis (CSS, JS, gambar)
├── package.json         -> Konfigurasi dan dependensi proyek
├── .gitignore           -> File yang diabaikan oleh Git
```

## Cara Menjalankan Aplikasi

1. **Clone repository**
```
git clone https://github.com/username/nama-repo.git
cd nama-repo
```

2. **Install dependensi**
```
npm install
```

3. **Konfigurasi koneksi database**
Ubah konfigurasi database di file db.js sesuai dengan yang ada di local

4. **Jalankan server**
```
node index.js
```

Buka browser dan akses aplikasi di:  
`http://localhost:3000`

## Dependensi Utama
- express
- ejs
- express-session
- connect-flash
- mssql
- body-parser 

## Catatan
- Semua file `node_modules` diabaikan melalui `.gitignore`

