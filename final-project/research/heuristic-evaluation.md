# Riset UI/UX — Proyek Akhir

## Informasi Umum

- **Nama Website:** [SMAN 1 Kudus]
- **URL:** [https://www.sma1kudus.sch.id/]
- **Halaman yang diriset:** [informasi kegiatan]
- **Tanggal Riset:** [tanggal]
- **Anggota Kelompok:**
  - [Nama 1] — [peran]
  - [Nama 2] — [peran]
  - [Nama 3] — [peran]

# Heuristic Evaluation — SMAN 1 Kudus (`sma1kudus.sch.id`)

## Heuristic #1: Visibility of System Status

**Skor Pelanggaran (0–4):** 2
**Temuan:**

- Menu aktif (`HOME`) di navbar tidak memiliki penanda visual (garis bawah/warna berbeda) untuk menunjukkan lokasi halaman pengguna saat ini[cite: 1, 2].
  **Screenshot Bukti:**
  ![Screenshot](../assets/heuristic-1.png)
  **Dampak ke Pengguna:**
- Pengguna kurang sadar sedang berada di halaman mana saat menjelajah menu.
  **Kaitan dengan Rekomendasi Desain:**
- Tambahkan indikator _active state_ (garis bawah atau _highlight_) pada item navigasi yang sedang dibuka.

---

## Heuristic #2: Match Between System and Real World

**Skor Pelanggaran (0–4):** 1
**Temuan:**

- Sebagian metadata dan istilah navigasi masih mencampur bahasa Inggris dan Indonesia (`By J&D SMASAKU`, `Posted on`, `HOME`, `INFO`)[cite: 1, 2].
  **Screenshot Bukti:**
  ![Screenshot](../assets/heuristic-1.png)
  **Dampak ke Pengguna:**
- Terasa kurang selaras dengan konteks situs sekolah resmi berbahasa Indonesia.
  **Kaitan dengan Rekomendasi Desain:**
- Gunakan bahasa Indonesia secara konsisten pada seluruh elemen UI (misal: _Beranda_, _Dipublikasikan pada_).

---

## Heuristic #3: Consistency and Standards

**Skor Pelanggaran (0–4):** 3
**Temuan:**

- Penulisan judul kartu berita tidak konsisten (sebagian ALL CAPS, sebagian _Title Case_)[cite: 1, 2].
- Salah satu kartu berita tidak memiliki gambar _thumbnail_, sehingga tata letak grid tampak tidak sejajar[cite: 2].
  **Screenshot Bukti:**
  ![Screenshot](../assets/heuristic-1.png)
  **Dampak ke Pengguna:**
- Tampilan terlihat kurang rapi dan mengganggu alur pemindaian mata (_visual scanning_).
  **Kaitan dengan Rekomendasi Desain:**
- Standarisasi gaya kapitalisasi judul (_Title Case_) dan sediakan _placeholder_ gambar otomatis jika artikel tidak memiliki _thumbnail_.

---

## Heuristic #4: Recognition Rather Than Recall

**Skor Pelanggaran (0–4):** 2
**Temuan:**

- Kartu berita tidak menampilkan label kategori (misal: _Prestasi_, _Agenda_, _Pengumuman_) maupun tombol/tautan _"Baca selengkapnya"_, serta ringkasan teks terpotong mendadak[cite: 1, 2].
  **Screenshot Bukti:**
  ![Screenshot](../assets/heuristic-2.png)
  **Dampak ke Pengguna:**
- Pengguna harus membaca isi cuplikan untuk menebak jenis informasi dan tidak mendapat isyarat jelas bahwa kartu dapat diklik.
  **Kaitan dengan Rekomendasi Desain:**
- Tambahkan _badge_ kategori di setiap kartu, akhiri ringkasan dengan elipsis (`...`), dan beri tautan _"Baca selengkapnya →"_.

---

## Heuristic #5: Aesthetic and Minimalist Design

**Skor Pelanggaran (0–4):** 2
**Temuan:**

- Teks metadata (`By J&D SMASAKU Posted on...`) menggunakan warna abu-abu sangat terang sehingga kontrasnya rendah dan sulit dibaca[cite: 1, 2].
- _Hero banner_ memakan ruang vertikal cukup besar namun minim informasi[cite: 2].
  **Screenshot Bukti:**
  ![Screenshot](../assets/heuristic-2.png)
  **Dampak ke Pengguna:**
- Informasi tanggal publikasi sulit terbaca sekilas dan ruang layar atas kurang efektif.
  **Kaitan dengan Rekomendasi Desain:**
- Tingkatkan kontras warna teks metadata agar memenuhi standar aksesibilitas (WCAG AA) dan padatkan proporsi _hero section_.

---

## Ringkasan Heuristic Evaluation

| #         | Heuristik                           | Skor   | Jumlah Temuan |
| --------- | ----------------------------------- | ------ | ------------- |
| 1         | Visibility of System Status         | 2      | 1             |
| 2         | Match Between System and Real World | 1      | 1             |
| 3         | Consistency and Standards           | 3      | 2             |
| 4         | Recognition Rather Than Recall      | 2      | 1             |
| 5         | Aesthetic and Minimalist Design     | 2      | 2             |
| **Total** |                                     | **10** | **7**         |

### Top 3 Pain Point Terbesar:

1. **Inkonsistensi visual kartu berita (Heuristic #3):** Perbedaan kapitalisasi judul (ALL CAPS vs _Title Case_) dan hilangnya _thumbnail_ pada salah satu kartu membuat tata letak grid terlihat tidak rapi[cite: 1, 2].
2. **Kontras metadata rendah & proporsi _hero banner_ kurang efektif (Heuristic #5):** Teks tanggal publikasi sulit terbaca karena warna abu-abu yang terlalu pudar, serta _hero banner_ memakan ruang vertikal cukup besar tanpa memuat informasi ringkas[cite: 1, 2].
3. **Ketiadaan label kategori & indikator klik pada kartu (Heuristic #4):** Kartu berita tidak menampilkan _badge_ kategori maupun tautan _"Baca selengkapnya"_, sehingga pengguna kesulitan mengenali jenis informasi secara sekilas[cite: 1, 2].
