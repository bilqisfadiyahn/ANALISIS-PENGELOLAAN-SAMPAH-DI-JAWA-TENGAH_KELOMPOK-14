# ANALISIS-PENGELOLAAN-SAMPAH-DI-JAWA-TENGAH_KELOMPOK-14
Project Data Wrangling

## Tentang Dataset

Dataset ini menyajikan informasi detail mengenai komposisi sampah berdasarkan jenisnya serta metode pembuangan sampah yang dominan di berbagai Kabupaten/Kota di Provinsi Jawa Tengah.

### Struktur Kolom

| Nama Kolom | Deskripsi | Satuan |
|------------|-----------|--------|
| `tahun` | Tahun pendataan | Tahun |
| `provinsi` | Nama Provinsi | Teks |
| `kabupaten_kota` | Nama Kabupaten atau Kota | Teks |
| `sisa_makanan` | Komposisi sampah sisa makanan | Persen (%) |
| `kayu_ranting` | Komposisi sampah kayu/ranting | Persen (%) |
| `kertas_karton` | Komposisi sampah kertas/karton | Persen (%) |
| `plastik` | Komposisi sampah plastik | Persen (%) |
| `logam` | Komposisi sampah logam | Persen (%) |
| `kain` | Komposisi sampah kain/tekstil | Persen (%) |
| `karet_kulit` | Komposisi sampah karet/kulit | Persen (%) |
| `kaca` | Komposisi sampah kaca | Persen (%) |
| `lainnya` | Komposisi sampah lainnya | Persen (%) |
| `tpa` | Jumlah desa yang membuang sampah ke TPA | Frekuensi (Jumlah Desa) |
| `dibakar` | Jumlah desa yang membakar sampah | Frekuensi (Jumlah Desa) |
| `dibuang_sungai`| Jumlah desa yang membuang sampah ke sungai | Frekuensi (Jumlah Desa) |
| `jumlah_desa` | Total desa di kabupaten/kota tersebut | Frekuensi (Jumlah Desa) |
| `pct_tpa` | Persentase desa akses TPA | Persen (%) |
| `pct_dibakar` | Persentase desa melakukan pembakaran | Persen (%) |
| `pct_dibuang_sungai` | Persentase desa membuang ke sungai | Persen (%) |

> **Catatan:** Nilai pada kolom komposisi sampah (`sisa_makanan` s/d `lainnya`) jika dijumlahkan per baris akan mendekati nilai 100%.
