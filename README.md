
# PBO LKS — Portofolio Praktikum

- Nama  : Zaharatussita
- NIM   : H1101251044
- Kelas : ...
- Mata Kuliah : Pemrograman Berbasis Objek (PBO)
- Dosen : Syahru Rahmayuda, M.Kom

## Fitur

- REST API Perpustakaan (PHP 8, PSR-4, Composer)
- CRUD Buku dan CRUD Kategori
- Arsitektur MVC + Repository, Service, Dependency Injection, Front Controller
- Konfigurasi via `.env`, database MySQL
- Validasi input dan error handling (404, 405, 422)
- Frontend terpisah (Tailwind CSS, JavaScript ES Module)

## Cara Menjalankan

### 1. Backend

```bash
cd rest-api-perpustakaan
composer install
cp .env.example .env        # lalu isi DB_USERNAME dan DB_PASSWORD
mysql -u root -p < database/schema.sql
php -S localhost:8000 -t public
```

### 2. Frontend (terminal baru)

```bash
cd frontend-perpustakaan
php -S localhost:3000
```

Buka http://localhost:3000

## Screenshot Aplikasi

![Dashboard](screenshot-final/dashboard.png)
![Buku](screenshot-final/halaman-buku.png)
![Kategori](screenshot-final/halaman-kategori.png)

## Daftar Pertemuan

- [X] Pertemuan 1 — Setup & Database ([langkah 1–5](pertemuan-01/))
- [X] Pertemuan 2 — Core OOP ([langkah 6–9](pertemuan-02/))
- [X] Pertemuan 3 — Framework & Routing ([langkah 10–11](pertemuan-03/))
- [X] Pertemuan 4 — Testing Backend ([langkah 12](pertemuan-04/))
- [X] Pertemuan 5 — CRUD Kategori ([langkah 13–15](pertemuan-05/))
- [X] Pertemuan 6 — Frontend ([langkah 16–18](pertemuan-06/))
- [X] Pertemuan 7 — Integrasi & Finalisasi ([langkah 19–20](pertemuan-07/))
