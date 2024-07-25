Langkah Langkah Menjalankan Aplikasi

1. Clone atau Download Proyek
git clone https://github.com/username/project.git
cd project
2. Install Depedency
composer install
3. Buat file .env
cp .env.example .env
4. Generate Application Key
php artisan key:generate
5. Konfigurasi Database
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_database
DB_USERNAME=username
DB_PASSWORD=password
6. Migrasi dan Seeding Database
php artisan migrate:fresh --seed
7. Jalankan Server
php artisan serve


Itu saja! Proyek Laravel 9 Anda sekarang sudah berjalan dan database sudah di-migrate serta di-seed.
