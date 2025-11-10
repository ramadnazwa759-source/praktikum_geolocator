## PRAKTIKUM GEOLOCATOR

**Tugas 1**: Geocoding (Alamat dari Koordinat)
Saat ini kita hanya menampilkan Lat/Lng. Buatlah agar aplikasi menampilkan alamat
(nama jalan, kota, dll) dari koordinat yang didapat.
Petunjuk:

## 1. Anda sudah menambahkan paket geocoding di pubspec.yaml.
<img width="609" height="185" alt="image" src="https://github.com/user-attachments/assets/3dd00bdb-c466-48f2-b123-5cb62ca72a86" />

## 2. Import paketnya: import ’package:geocoding/geocoding.dart’;
<img width="641" height="170" alt="image" src="https://github.com/user-attachments/assets/56ff433f-2f34-4b4e-895a-746ef9a20a04" />

Paket ini digunakan untuk mengubah koordinat dari Latitude dan longitude menjadi bentuk string.

## 3. Buat variabel String? currentAddress; di MyHomePageState.
<img width="830" height="184" alt="image" src="https://github.com/user-attachments/assets/621ac47e-5dbe-400c-97c9-7bc76870dc18" />

## 4. Buat fungsi baru getAddressFromLatLng(Position position).
<img width="1433" height="552" alt="image" src="https://github.com/user-attachments/assets/4036294b-8826-4a02-b50f-1eaba03bb7b8" />

## 5. Panggil fungsi getAddressFromLatLng( currentPosition!) di dalam getLocation dan startTracking (di dalam .listen()) setelah setState untuk currentPosition.
- Pada getLocation
<img width="1021" height="501" alt="image" src="https://github.com/user-attachments/assets/6c89cacb-0eff-4906-8704-c251fbbff56b" />

- Pada startTracking
<img width="895" height="776" alt="image" src="https://github.com/user-attachments/assets/d0f491b7-9fe4-4778-9203-6d7478fdf599" />

11. Tampilkan currentAddress di UI Anda, di bawah Lat/Lng.
<img width="562" height="274" alt="image" src="https://github.com/user-attachments/assets/983c8daf-7dae-44a5-9af1-5d4325e02806" />

## Hasil Implementasi
