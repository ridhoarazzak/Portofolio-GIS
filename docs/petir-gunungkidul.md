# Analisis Kalurahan Petir, Gunungkidul

![Tutupan lahan dan jalan Kalurahan Petir](../assets/images/petir-peta.jpg){ width="320" }

## Ringkasan

Gambaran awal Kalurahan Petir, Kapanewon Rongkop, dari data satelit: lahan pertanian, sumber air, penduduk, bangunan, dan tinggi di atas sungai (HAND). Dibuat untuk membantu kalurahan yang datanya terbatas, dan disampaikan sebagai perkiraan yang perlu dilengkapi data lapangan.

**Wilayah:** Kalurahan Petir, Rongkop, Gunungkidul, DIY  
**Peran:** Penyusun analisis dan laporan (pendampingan)  
**Status:** Selesai sebagai gambaran awal; menunggu data resmi dan lapangan

!!! warning "Catatan"
    Semua angka adalah perkiraan satelit, bukan data resmi. Dusun Siyono B belum dianalisis terpisah karena batas dusunnya belum tersedia.

---

## Metode dan alat

**Sumber data**

- Dynamic World dan ESA WorldCover (tutupan lahan)
- GHSL GHS-POP (penduduk), Open Buildings (bangunan)
- MERIT Hydro (sungai dan HAND), CHIRPS (curah hujan)
- OpenStreetMap (jalan dan fasilitas)

**Langkah**

1. Memuat batas kalurahan dan menjalankan analisis di dashboard Earth Engine.
2. Mengekspor ringkasan, daftar bangunan, dan statistik 12 zona Voronoi ke CSV.
3. Menghitung ulang dari CSV dan mencocokkan dengan dashboard (cek silang).
4. Menilai tingkat keyakinan tiap indikator dan menyusun rekomendasi verifikasi.

| Alat | Fungsi |
|------|--------|
| Google Earth Engine | Analisis dan dashboard interaktif |
| Excel | Ringkasan, rumus, cek silang, tautan Street View per bangunan |
| Word | Executive summary |

![Zona Voronoi](../assets/images/petir-voronoi.jpg){ width="320" }

*12 zona Voronoi dari sebaran bangunan; bukan batas dusun atau RW.*

---

## Temuan utama

- Luas wilayah sekitar 1.136 ha dengan 1.727 bangunan dan sekitar 2.349 jiwa (perkiraan GHSL 2025).
- Pertanian berkisar 0,5 ha (terbaca jelas) sampai 84,3 ha (gabungan), jadi tidak bisa dinyatakan satu angka.
- Sumber air perumahan tidak bisa dinilai karena tidak ada titik air di OSM.
- Hitungan ulang dari CSV cocok dengan dashboard (bangunan, dekat air, dekat jalan).

---

## Tautan

[Dashboard](#){ .md-button }
[Executive Summary](#){ .md-button }
[Excel](#){ .md-button }
