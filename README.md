# Pertemuan 03 Seleksi Python

Nama: Alfitrah Zahra Ameliya
NIM: 2225250181
Kelas: 3B

## Tujuan

Menulis program seleksi if, if-else, kondisi majemuk, dan nested if.

## Cara Menjalankan

python3 tugas/analisis_persamaan_kuadrat.py

## Algoritma Tugas

1. Membaca nilai koefisien a, b, dan c.
2. Memeriksa apakah nilai a sama dengan 0.
3. Jika a sama dengan 0, program menampilkan bahwa input bukan persamaan kuadrat.
4. Jika a tidak sama dengan 0, menghitung diskriminan dengan rumus D = b² - 4ac.
5. Jika D lebih besar dari 0, program menghitung dan menampilkan dua akar real.
6. Jika D sama dengan 0, program menghitung dan menampilkan satu akar real kembar.
7. Jika D kurang dari 0, program menampilkan bahwa tidak ada akar real.

## Hasil Pengujian

| No | Input (a, b, c) | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| 1 | (1, -5, 6) | Dua akar real: 3 dan 2 | Dua akar real: x1 = 3.00, x2 = 2.00 | Berhasil |
| 2 | (1, 2, 1) | Akar kembar: -1 | Akar real kembar: x = -1.00 | Berhasil |
| 3 | (1, 0, 1) | Tidak ada akar real | Tidak ada akar real. | Berhasil |
| 4 | (0, 2, 3) | Bukan persamaan kuadrat | Bukan persamaan kuadrat. | Berhasil |

## Refleksi

Kesalahan logika yang perlu diperhatikan adalah menentukan kondisi dan operator perbandingan dengan tepat. Pengujian beberapa test case membantu memastikan setiap cabang program berjalan sesuai dengan kondisi yang ditentukan.