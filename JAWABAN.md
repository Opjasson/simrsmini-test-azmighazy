# Jawaban Tes Debugging SIMRS Mini

Nama:Azmi Ghazy Asyrof
Tanggal:4-11-2026

Salin blok di bawah untuk setiap bug yang Anda temukan.

## Bug 1

- Gejala: tidak bisa masuk aplikasi awal setup
- Lokasi (file:baris): vendor\laravel\framework\src\Illuminate\Encryption\EncryptionServiceProvider.php**:83**
No application encryption key has been specified
- Penyebab: missing app key, first setup
- Perbaikan: php artisan key:generate -> untuk generate key setiap kali setup device developer baru


## Bug 2

- Gejala: tidak bisa masuk aplikasi awal setup
- Lokasi (file:baris): vendor\laravel\framework\src\Illuminate\Encryption\EncryptionServiceProvider.php**:83**
No application encryption key has been specified
- Penyebab: missing app key, first setup
- Perbaikan: php artisan key:generate -> untuk generate key setiap kali setup device developer baru