<h1 align="center">Selamat datang di Tiket!</h1>

## Apa itu Ticket?

## Fitur apa saja yang tersedia di Ticket?

-   Autentikasi Admin
-   User & CRUD
-   Rute & CRUD
-   Transportasi & CRUD
-   Category & CRUD
-   Pemesanan Ticket
-   Dan lain-lain


## Default Account for testing

**Admin Default Account**

-   username: admin
-   Password: admin123

---

## Install

1. **Clone Repository**

```bash
git@github.com:adenexplore/project_tiket_laravel.git
cd Ticket-Laravel
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan website**

```bash
php artisan serve
```

