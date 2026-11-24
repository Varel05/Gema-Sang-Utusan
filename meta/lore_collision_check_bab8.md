---
title: "Pemeriksaan Tabrakan Lore Pasca Bab 8"
type: meta/revision-brief
sumber: "Review developmental editor atas repo Gema-Sang-Utusan, commit a886ea3 (2026-11-24 08:19 WIB)"
cakupan: "lore/characters/bran.md, garrett.md, tobias.md; lore/worldbuilding/geography/kadipaten_leovard.md; lore/glossary/glossary.md; meta/shards_tracker.md; chapters/id/chapter_04-08.md"
tags:
  - meta/revisi
  - lore
  - editorial
---

# Pemeriksaan Tabrakan Lore Pasca Bab 8

## 0. Cara Memakai Dokumen Ini (untuk AI)

- Dokumen ini memuat **tabrakan** antara lore baru (commit `a886ea3`) dan teks atau lore lama. Jangan mengubah `lore/` atau teks bab sebelum Penulis memilih opsi di Bagian 3.
- Patuhi `Panduan.md`. Tandai usulan kanon sebagai `[USULAN KANON BARU]`.
- Nomor baris mengacu ke commit `a886ea3`. Verifikasi dulu.
- Jika temuan ternyata keliru terhadap teks, sampaikan secara jujur kepada Penulis.

## 1. Status Revisi Bab 8 Tahap 3

Terverifikasi di teks (3.286 kata): motif Tobias hanya diucapkan Tobias (Garrett: "kalian sudah mendengar sendiri apa harganya"), pengamat balkon ditagih di laporan Garrett, nama institusi seragam (Perbendaharaan, dewan, balai istana). Sisa kecil: lihat 2.8.

## 2. Temuan Tabrakan

### Prioritas 1: tabrakan yang merusak logika

**2.1 Linimasa Bran bertabrakan dengan dirinya sendiri** (`bran.md` L44-47)
- Langkah 2 menyatakan Garda Pembuka Jalur dibubarkan ±20 musim lalu, lalu Bran **kemudian** dimutasi ke Garda Utama dan bertugas **sepuluh musim** bersama Garrett. Itu membawa dinasnya hingga ±10 musim lalu.
- Langkah 3 menyatakan ia pensiun ±20-19 musim lalu, **sebelum Kael lahir**. Keduanya tidak bisa benar bersamaan.
- Rentang "~28-20 musim lalu" juga hanya delapan musim, bukan sepuluh.

**2.2 Angka dinas Garrett dan Bran tidak cocok** (`chapter_05.md` L119, `chapter_06.md` L38 dan L132)
- Bab 5: Garrett dan Bran "sepuluh musim berbagi darah dan ransum di dinding utara".
- Bab 6: Garrett "dua puluh lima musim aku berdinas di Garda Utama".
- Bran pensiun ≥19 musim lalu. Jika Garrett baru berdinas 25 musim lalu, tumpang tindih maksimal hanya ±6 musim, bukan sepuluh.
- Bab 6 (Bran): pedang menemaninya "sepuluh musim menjaga celah cadas utara". Itu tugas Garda Pembuka Jalur menurut glosarium, bukan Garda Utama, tetapi lore menaruh sepuluh musim itu di Garda Utama bersama Garrett.

**2.3 Satuan kakek Kael tidak konsisten** (`bran.md` L39 vs `glossary.md`, `chapter_08.md` L112)
- `bran.md` L39: kakek Kael adalah veteran **Garda Perbatasan**.
- Glosarium dan Tobias (Bab 8): kesatuan kakek (dan Bran muda) adalah **Garda Pembuka Jalur**.
- Glosarium juga mendefinisikan Garda Perbatasan sebagai kesatuan terpisah yang kini **dipimpin Garrett**.

**2.4 Tempat Bran ditempa** (`bran.md` L38, `kadipaten_leovard.md` L39)
- Teks lama: Bran "prajurit elit di ibu kota Leovard", "ditempa" di markas kadipaten.
- Linimasa baru (`bran.md` L44): masa muda di **tapal batas utara**, bukan di ibu kota.
- Bab 8: Kael diceritakan ibunya bahwa Bran "pernah menjadi prajurit di kota benteng ini". Ini sah hanya jika Bran bertugas di Leovard setelah masa mudanya.

**2.5 Jabatan Garrett** (`garrett.md` L21, L27 vs `glossary.md`, `chapter_08.md`)
- `garrett.md`: "Kepala Prajurit **Garnisun** Kadipaten Leovard", afiliasi Garda Utama.
- Glosarium: **Garda Dalam** adalah garnisun benteng, sedangkan Garda Perbatasan dipimpin Garrett.
- Bab 8: Garrett "komandan patroli perbatasan sektor ngarai utara". Hubungan Garda Perbatasan dengan Garda Utama belum dinyatakan (satuan terpisah atau detasemen).

### Prioritas 2

**2.6 Pedang: warisan atau sudah lama bersama Kael?**
- Bab 6: Bran memberikan pedang pusaka kepada Kael pada fajar keberangkatan (pertama kali). `bran.md` L47 menyatakan hal yang sama.
- Bab 4: Kael sudah memakai pedang di pinggang (mis. L71, L147).
- Bab 8: "Selama tujuh musim ia ditempa oleh ayahnya... pedang itu adalah pelindung dan bagian dari dirinya", dan Kael mencari "hulu pedang yang biasa menemaninya setiap hari".
- Perlu penjelasan: pedang di Bab 4 adalah pedang latihan (bukan pusaka), dan kalimat Bab 8 diubah agar tidak menyiratkan pusaka sudah tujuh musim bersamanya.

**2.7 Aldric tidak punya halaman lore**
- `[[aldric]]` ditautkan di `kadipaten_leovard.md`, tetapi `aldric.md` tidak ada. Aldric adalah antagonis utama arc Leovard, dan motifnya (hubungannya dengan Vane, sabotase dua kursi dewan) hanya hidup di teks.

**2.8 Pecahan #2: lokasi dan akses**
- Lore (`kadipaten_leovard.md`): "tersimpan di bawah fondasi benteng... terkunci di balik pintu besi... dijaga empat prajurit". Bab 8: Azariel merasakannya "berpuluh-puluh hasta" di bawah cadas fondasi. Brankas di balik pintu besi biasanya ruangan, bukan kedalaman puluhan hasta. Perlu jelas: pintu besi membuka ke tangga atau lorong turun, atau pecahan berada di batuan di bawah bangunan.
- `shards_tracker.md` L27 masih menyebut "brankas perbendaharaan".
- Lore lama menyebut pecahan "dianggap relik permata bernilai tinggi" (dihapus). Belum diputuskan apakah Adipati dan Aldric tahu hakikatnya.
- Bab 8: narasi "sebuah kehadiran yang tertidur kaku" (L158) dan dialog Azariel "Ia tidak tidur, Mira" (L174) saling bertentangan.

**2.9 Medali Segel dalam shards_tracker sudah usang** (`shards_tracker.md` L27)
- "Resolusi krisis Leovard menganugerahkan Medali Segel Perlindungan Kadipaten **dari Garrett**." Seorang kapten tidak berwenang menganugerahkan medali kadipaten, dan arc kini diputuskan lewat dewan atau keputusan politik resmi (lihat `outline.md` baris `09+`).

### Prioritas 3

**2.10** Tobias (Bab 8) menyebut Bran "membuang baju zirahnya demi memetik gandum di lembah". Bran adalah pemburu dan ketua patroli, bukan petani gandum (itu Joran). Bisa dibiarkan jika Tobias hanya berbicara kiasan.

**2.11** Lingkaran Diam, simpul doa, dan kemampuan Azariel menopang tunas (Bab 7) belum dikodifikasi di `lore/` (masih terbuka dari tinjauan sebelumnya).

## 3. Usulan Rekonsiliasi (Penulis memilih)

### Opsi A (disarankan): satu rentang dinas, perubahan terkecil di teks

Usia Bran dan Garrett ~46-47 (sebaya, sesuai "~40-an").

| Kapan (musim lalu) | Peristiwa |
|--------------------|-----------|
| ~30 | Bran (±17) masuk Garda Pembuka Jalur di dinding utara. Garrett (±17) masuk Garda Utama di dinding utara yang sama |
| ~30 hingga ~20 | Mereka rekan sepuluh musim di dinding utara. Pedang Pembuka Jalur menemani Bran "sepuluh musim menjaga celah cadas utara" |
| ~20 | Garda Pembuka Jalur dibubarkan. Bran (±27) pensiun, menikahi Elora, pindah ke lembah |
| ~19 | Kael lahir |
| sekarang | Garrett genap ±30 musim berdinas |

Perubahan yang diperlukan:
- `bran.md`: hapus "dimutasi ke Garda Utama" dan ganti dengan "Pembuka Jalur dan Garda Utama bertugas berdampingan di dinding utara". Perbaiki L38 dan L39 (lihat 2.3, 2.4).
- `chapter_06.md` L132: Garrett "Dua puluh lima musim" menjadi "Tiga puluh musim".
- `kadipaten_leovard.md` L39: "tempat ia ditempa" menjadi "tempat ia pernah berdinas dan mengenal para pejabatnya" (agar Tobias dan ibu Kael bisa mengenalnya).
- `garrett.md`: sesuaikan jabatan (lihat 2.5).
- `glossary.md`: Garda Pembuka Jalur "bertugas berdampingan dengan Garda Utama sebelum dibubarkan ±20 musim silam".
- `chapter_08.md`: ubah "pernah menjadi prajurit di kota benteng ini" menjadi "di kadipaten ini" agar sesuai dengan masa mudanya di dinding utara.

### Opsi B: pertahankan angka teks, ubah lore

- Garrett tetap 25 musim; Bab 5 "sepuluh musim" menjadi "enam musim"; tetapkan Garda Pembuka Jalur berlangsung sepuluh musim sebelum Bran berpindah. Lebih banyak teks yang berubah (Bab 5 dan Bab 6).

### Hubungan satuan (berlaku di kedua opsi)

- Garda Perbatasan = **detasemen utara Garda Utama**, dipimpin Garrett. Garda Pembuka Jalur = resimen rakyat jelata yang bertugas di dinding utara dan dibubarkan ±20 musim lalu. Garda Dalam = garnisun benteng.

## 4. Perbaikan Lain yang Disarankan (setelah keputusan)

1. **Pedang:** jelaskan di `chapter_04.md` bahwa itu pedang latihan. Ubah kalimat Bab 8 menjadi, mis., "Pedang pusaka itu baru beberapa hari di tangannya, tetapi ia telah menjadi bagian dari dirinya."
2. **Buat `lore/characters/aldric.md`**: peran (Sekretaris Perbendaharaan), motif, hubungan dengan Vane, sabotase dua kursi dewan, apa yang ia ketahui tentang pecahan. `[USULAN KANON BARU]`, motif butuh keputusan Penulis.
3. **Pecahan #2:** tetapkan akses (tangga turun di balik pintu besi, atau pecahan di batuan di bawah bangunan) dan apakah Adipati atau Aldric tahu hakikatnya. Perbarui `shards_tracker.md` agar tidak menyebut "brankas".
4. **Bab 8 L158:** ganti "tertidur kaku" menjadi "diam dan kaku" agar tidak bertentangan dengan "Ia tidak tidur".
5. **Medali Segel:** ubah menjadi "dari Dewan atau Adipati, diserahkan melalui Garrett" di `shards_tracker.md`.
6. **Opsional (Bab 7):** jika "prajurit perbatasan tua" dipakai untuk kakek Kael, pertimbangkan "veteran", karena pada masa Garrett kecil (±35 musim lalu) kakek Kael baru berusia pertengahan tiga puluhan.

## 5. Keputusan yang Perlu Diambil Penulis

1. Opsi A atau B untuk linimasa.
2. Garda Perbatasan = detasemen Garda Utama (disarankan) atau kesatuan terpisah?
3. Akses dan hakikat Pecahan #2 yang diketahui kadipaten.
4. Motif Aldric dan apakah ia tahu apa itu pecahan.

## 6. Kriteria Selesai

- [x] Satu linimasa Bran dan Garrett (Opsi A) tertulis di `bran.md` dan `garrett.md`, dan angka di Bab 5, 6, dan 8 cocok.
- [x] Satuan kakek Kael konsisten (Garda Pembuka Jalur) di `bran.md` dan glosarium.
- [x] Hubungan Garda Perbatasan dengan Garda Utama ditulis di glosarium (Garda Perbatasan sebagai detasemen utara Garda Utama di bawah Garrett).
- [x] Penjelasan pedang latihan (Bab 4) dan kalimat Bab 8 diperbaiki (ID & EN).
- [x] `aldric.md` dibuat setelah motif diputuskan (ambisi kekuasaan ekonomi mutlak, kongsi dengan Vane untuk melengserkan Tetua Desa).
- [x] Akses Pecahan #2 dan baris `shards_tracker.md` diperbarui (brankas pusaka kerajaan timur), serta "tertidur" di Bab 8 diganti menjadi "diam dan kaku".
- [x] EN disinkronkan dan changelog diperbarui.
