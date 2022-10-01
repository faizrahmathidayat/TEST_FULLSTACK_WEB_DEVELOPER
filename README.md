====== Petunjuk Installasi ======

- buat folder di "C:\xampp\htdocs\" (Untuk Windows).
- Ekstrak File Zip didalam folder yang sudah dibuat.
- Import database (DB Terlampir pada file zip).
- ubah konfigurasi database.php (disesuaikan):

  'hostname' => 'localhost',
	'username' => 'db_username',
	'password' => 'db_password',
	'database' => 'db_name',

jalankan dibrowser anda "http://localhost/{nama_folder}"

routing customer : "http://localhost/{nama_folder}/booking"
routing admin : "http://localhost/{nama_folder}"
  - username : admin
  - password : admin
