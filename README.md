# Pemrograman Terstruktur - Pertemuan 1

## Deklarasi AI
AI 0, tidak memakai AI.

## Pertemuan 2 - Deklarasi AI
- **Label:** AI 1
- **Alat yang dipakai:** Gemini
- **Tujuan penggunaan:** Meminta penjelasan pemilihan tipe data (`string` untuk NPM dan `double` untuk nilai), penggunaan `getline(cin, nama)` untuk input nama berspasi, serta mengecek kesesuaian kode `sinilai_v01.cpp` dengan aturan kelas.
- **Cara memeriksa kebenaran:** Mengompilasi ulang dengan flag `g++ -std=c++20 -Wall -Wextra -Wpedantic -g sinilai_v01.cpp -o sinilai_v01` hingga bersih dari error/warning, lalu menguji keluaran program menggunakan berkas `contoh_masukan.txt`.

## Pertemuan 3 - Deklarasi AI
- **Label:** AI 1
- **Alat yang dipakai:** Gemini
- **Tujuan penggunaan:** Meminta penjelasan mengenai penggunaan konstanta bobot (`const double`), prioritas evaluasi ekspresi aritmetika, serta cara menghindari pembagian bilangan bulat saat menghitung `rerata_polos` di `sinilai_v02.cpp`.
- **Cara memeriksa kebenaran:** Mengompilasi ulang kode dengan flag `g++ -std=c++20 -Wall -Wextra -Wpedantic -g sinilai_v02.cpp -o sinilai_v02` hingga bebas error dan warning, lalu memverifikasi hasil perhitungan (`83.975` dan `85.875`) menggunakan berkas `contoh_masukan.txt` serta mengecek ulang dengan kalkulator.

## Pertemuan 4 - Deklarasi AI
- **Label:** AI 1
- **Alat yang dipakai:** Gemini
- **Tujuan penggunaan:** Meminta penjelasan struktur `if-else` bertingkat dari batas tertinggi ke terendah tanpa syarat ganda, penugasan ekspresi boolean langsung pada `bool lulus`, serta penggunaan `switch` pada `huruf_mutu[0]` bertipe `char` di `sinilai_v03.cpp`.
- **Cara memeriksa kebenaran:** Mengompilasi ulang dengan flag `g++ -std=c++20 -Wall -Wextra -Wpedantic -g sinilai_v03.cpp -o sinilai_v03` hingga bebas error dan warning, lalu menguji ketujuh kasus batas (`83.975`, `80`, `79.9`, `60`, `59.9`, `50`, dan `30`) dan mencocokkannya dengan tabel uji pada modul.

## Pertemuan 5 - Deklarasi AI
- **Label:** AI 1
- **Alat yang dipakai:** Gemini
- **Tujuan penggunaan:** Meminta penjelasan struktur perulangan `do-while` untuk validasi jumlah mahasiswa, perulangan `for` dengan dua akumulator (`total_nilai` dan `jumlah_lulus`) di luar loop, serta penggunaan `getline(cin >> ws, nama)` untuk membersihkan sisa newline antar mahasiswa di `sinilai_v04.cpp`.
- **Cara memeriksa kebenaran:** Mengompilasi ulang kode dengan flag `g++ -std=c++20 -Wall -Wextra -Wpedantic -g sinilai_v04.cpp -o sinilai_v04` hingga bebas error dan warning, lalu mengujinya dengan `./sinilai_v04 < contoh_masukan.txt` serta mencocokkan nilai akhir tiap mahasiswa dan rekap kelas dengan tabel modul.

## Pertemuan 6 - Deklarasi AI
- **Label:** AI 1
- **Alat yang dipakai:** Gemini
- **Tujuan penggunaan:** Meminta penjelasan pengaturan format kolom menggunakan `fixed`, `setprecision(2)`, `left`, `right`, dan `setw`, penggunaan `switch` pada `huruf_mutu[0]` untuk menghitung distribusi huruf mutu, pola pelacakan nilai tertinggi, serta perulangan bersarang untuk menggambar batang `#` pada `sinilai_v05.cpp`.
- **Cara memeriksa kebenaran:** Mengompilasi ulang kode dengan flag `g++ -std=c++20 -Wall -Wextra -Wpedantic -g sinilai_v05.cpp -o sinilai_v05` hingga bebas error dan warning, lalu mengujinya dengan `./sinilai_v05 < contoh_masukan.txt` dan mencocokkan enam baris data mahasiswa, laporan rekap kelas, serta grafik batang sebaran huruf mutu dengan tabel modul.