# Benchmarking

## Website yang Dibandingkan

### Website A: Website Resmi Desa Sepandan

- **URL:** `https://desasepandan.id/` _(sesuaikan dengan URL asli)_
- **Halaman sejenis:** Beranda (_Landing Page_) instansi publik yang memuat profil, informasi layanan, dan sambutan pimpinan.
- **Kelebihan:**
  - Memiliki penanda halaman aktif (_active state_ garis bawah pada menu `Home`) sehingga lokasi navigasi jelas.
  - Menyediakan tombol pintasan mengambang (_floating CTA_) untuk layanan **Pengaduan** dan fitur **Aksesibilitas** di bagian bawah layar.
  - Menampilkan bagian **Sambutan Pimpinan** lengkap dengan foto dan profil singkat di bawah _hero section_, membangun kepercayaan pengunjung[cite: 3, 4].
- **Kekurangan:**
  - _Hero banner_ memakan satu layar penuh tanpa tombol aksi utama (_Call-to-Action_) di bagian tengah.
  - Elemen mengambang di pojok kiri dan kanan bawah berpotensi menutupi konten saat halaman digulir pada layar kecil[cite: 3, 4].
- **Screenshot:**
  ![Website A](../assets/benchmark-a.png)

---

### Website B: Website Resmi Desa Ponggok

- **URL:** `https://desaponggok.id/` _(sesuaikan dengan URL asli)_
- **Halaman sejenis:** Beranda (_Landing Page_) portal informasi publik yang menampilkan _hero section_ dan daftar berita terkini.
- **Kelebihan:**
  - Memiliki tombol CTA utama yang menonjol di tengah _hero banner_ serta garis bawah pada menu aktif (`DESA PONGGOK`).
  - Bagian berita (**Ponggok Hari Ini**) memiliki judul seksi yang jelas, kapitalisasi judul artikel yang konsisten (_Title Case_), serta metadata berbahasa Indonesia (_"Diperbarui pada..."_)[cite: 5, 6].
- **Kekurangan:**
  - Kontras warna logo di pojok kiri atas menyatu dengan latar langit gelap sehingga sulit terbaca.
  - _Thumbnail_ gambar pada seluruh kartu berita gagal dimuat (hanya tampil kotak abu-abu kosong)[cite: 5, 6].
- **Screenshot:**
  ![Website B](../assets/benchmark-b.png)

---

## Perbandingan Fitur

| Fitur                                    | Website Target (SMAN 1 Kudus) | Website A (Desa Sepandan)  | Website B (Desa Ponggok)    | Desain Ulang Kami |
| ---------------------------------------- | ----------------------------- | -------------------------- | --------------------------- | ----------------- |
| Indikator Menu Aktif                     | ❌ Tidak ada                  | ✅ Ada                     | ✅ Ada                      | ✅ (Rencana)      |
| Tombol CTA di _Hero Section_             | ❌ Tidak ada                  | ❌ Tidak ada               | ✅ Ada                      | ✅ (Rencana)      |
| Sambutan Kepala Sekolah / Profil Singkat | ❌ Tidak ada                  | ✅ Ada                     | ❌ Tidak ada                | ✅ (Rencana)      |
| Konsistensi Kartu Berita & _Thumbnail_   | ⚠️ Sebagian (1 tanpa gambar)  | ➖ Tidak ditampilkan       | ⚠️ Sebagian (gambar kosong) | ✅ (Rencana)      |
| Pintasan Bantuan / Kontak Cepat          | ❌ Tidak ada (di _footer_)    | ✅ Ada (_floating button_) | ⚠️ Sebagian (via medsos)    | ✅ (Rencana)      |
| Konsistensi Bahasa Indonesia pada UI     | ⚠️ Sebagian (campur Inggris)  | ⚠️ Sebagian (`Home`)       | ✅ Ada                      | ✅ (Rencana)      |

---

## Pelajaran dari Benchmarking:

1. **Praktik terbaik yang ingin diadopsi:** Menambahkan indikator garis bawah pada menu navigasi aktif, menyertakan tombol CTA utama di _hero section_ (seperti informasi SPMB), serta menampilkan bagian sambutan kepala sekolah/profil singkat agar beranda tidak langsung berisi daftar berita saja.
2. **Hal yang perlu dihindari:** Menghindari penempatan terlalu banyak tombol mengambang (_floating widget_) di sudut layar yang mengganggu keterbacaan, serta mencegah _thumbnail_ kosong dengan menyiapkan gambar _placeholder_ bawaan.
3. **Kesempatan untuk diferensiasi:** Menggabungkan tata letak berita yang rapi dengan _badge_ kategori (_Prestasi_, _Agenda_, _Pengumuman_), kontras teks yang tinggi, dan tombol pintasan layanan sekolah yang terintegrasi rapi tanpa menutupi konten.
