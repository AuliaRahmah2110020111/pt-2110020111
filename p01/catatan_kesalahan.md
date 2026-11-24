# Catatan Kesalahan - Praktikum 5

| Berkas | Jenis kesalahan | Pesan yang muncul (salin baris pertamanya) | Cara kamu mengetahuinya |
| :--- | :--- | :--- | :--- |
| `k1_sintaks.cpp` | Kesalahan Sintaks | `error: expected ',' or ';' before 'std'` | Build gagal saat proses compile, compiler langsung menunjukkan baris yang kurang tanda titik koma (`;`). |
| `k2_nama.cpp` | Kesalahan Compile lainnya | `error: 'Nilai' was not declared in this scope; did you mean 'nilai'?` | Build gagal saat compile karena perbedaan huruf besar/kecil (`Nilai` vs `nilai`) dan variabel `bonus` belum dideklarasikan. |
| `k3_runtime.cpp` | Kesalahan Runtime | *(Tidak ada pesan error saat compile, program langsung berhenti/crash saat input `0`)* | Build berhasil, namun saat program dijalankan dan diberi input `0`, terjadi pembagian dengan nol (*division by zero*). |
| `k4_logika.cpp` | Kesalahan Logika | *(Tidak ada pesan error maupun warning)* | Build sukses dan program berjalan lancar, namun hasil keluaran salah (`81` padahal seharusnya `81.67`) karena pembagian integer `/ 3`. |

**Kesalahan paling berbahaya:**
Menurut saya, **kesalahan logika** adalah jenis kesalahan yang paling berbahaya karena compiler tidak memberikan peringatan atau error sama sekali sehingga program tampak berjalan normal padahal menghasilkan data yang keliru.