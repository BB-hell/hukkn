[php.ini]curl, intl, mbstring, mysqli, fileinfo, openssl, zip, pdo_mysql

update php
1. cek versi php php -v
2. download https://downloads.php.net/~windows/releases/archives/php-8.5.4-Win32-vs17-x64.zip
3. ke folder C:\xampp, rename folder php jadi php1
4. extract yg didownload tadi ke C:\xampp\php
5. buka folder C:\xampp\php
6. rename file php.ini-production jadi php.ini, terus buka filenya
7. ctrl + f ketik zip terus enter
8. hapus titik koma yang zip, pdo_mysql, mysqli, openssl, fileinfo, intl, mbstring, curl
9. dibaris kosong tambahin extension_dir=”C:\xampp\php\ext”
10. ctrl + s buat save
11. tutup terminal terus buka lagi
12. ketik php -v pastiin versi nya 8.5.x

1. buat folder di D, misalnya "ukknasional"
2. masuk ke folder "ukknasionanl" lewat file explorer, ketik cmd diatas
3. ketik composer create-project itsazni/ukk
4. ketik cd ukk
5. ketik npm install
6. ketik code .
7. buat database di phpmyadmin (misalnya db_ukk)
8. buka file .env terus update DB_DATABASE nya jadi database yang kalian buat (db_ukk)
9. di cmd ketik php artisan migrate:fresh --seed
10. buka folder ukknasiol (di D yang kalian buat tadi)
11. ketik cmd lagi di atas kaya step nomor 2, lalu ketik cd ukk
12. ketik php artisan serve
13. di cmd satunya  (yang awal bikin, bukan cms baru) ketik npm run dev
