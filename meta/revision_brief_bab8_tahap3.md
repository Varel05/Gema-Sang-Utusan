---
title: "Revision Brief Bab 8: Tahap 3 (Sentuhan Akhir)"
type: meta/revision-brief
sumber: "Review developmental editor atas repo Gema-Sang-Utusan, commit 69bf76e (2026-11-24 07:49 WIB)"
cakupan: "chapters/id/chapter_08.md dan chapters/en/chapter_08.md, catatan lore Bran"
tags:
  - meta/revisi
  - editorial
---

# Revision Brief Bab 8: Tahap 3

## 0. Cara Memakai (untuk AI)

- Ini sentuhan akhir yang kecil. Jangan mengubah hal lain di Bab 8, terutama adegan roti Azariel, gestur Kael di penutup, tanda terima sitaan, dan reaksi Tobias pada Azariel.
- Patuhi `Panduan.md`. Jangan mengubah `lore/` tanpa persetujuan Penulis.
- Nomor baris mengacu ke commit `69bf76e`. Verifikasi dulu.
- Catat di `update/changelog.md` dan sinkronkan ke versi EN.

## 1. Status

Seluruh brief tahap 2 terverifikasi terlaksana di teks: pedang tetap disita dan Tobias hanya menyerahkan tanda terima (dengan alasan hukum), penutup Kael berupa berhenti meraba pinggang kosong, pengamat nyata di balkon, Tobias bereaksi pada Azariel dan menyiratkan bilah lebih tua dari Bran, kalimat "kursi wakil Distrik Pengrajin kosong" tertanam, telling di ruang tunggu dihapus, tantangan Mira dijawab, "dingin" turun dari 20 menjadi 5, anakronisme (garnisun, parapet, tingtur, piket, verifikasi) hilang, dan kanon Garda masuk ke `lore/glossary/glossary.md`. Brief Bab 8 juga sudah dipindah ke `meta/`.

## 2. Tugas

### 2.1 Motif Tobias masih dinyatakan dua kali (Prioritas 2)

Tobias berkata, "Aku butuh kesaksian Garrett di hadapan Yang Mulia Adipati sebelum Aldric berhasil mengunci pintu dewan." Di adegan malam, Garrett mengulang: "ia ingin kesaksianku di hadapan Adipati mematahkan pengaruh Aldric."

**Tugas:** biarkan Tobias satu-satunya yang menyatakannya. Garrett cukup menyebut bahwa ada timbal balik.

- Sebelum: "...namun pria tua itu menuntut timbal balik: ia ingin kesaksianku di hadapan Adipati mematahkan pengaruh Aldric."
- Sesudah: "...namun pria tua itu menuntut timbal balik, dan kalian sudah mendengar sendiri apa harganya."

### 2.2 Pengamat balkon belum ditagih (Prioritas 2, satu kalimat)

Prajurit yang menatap dari balkon (adegan sumur) menghidupkan alibi Mira, tetapi tidak punya akibat. Padahal Tobias dan Garrett sama-sama menyebut Aldric mengawasi setiap langkah mereka.

**Tugas:** tambahkan satu kalimat di laporan Garrett: seorang prajurit balkon melaporkan tiga orang asing di dekat sumur. Ini juga menjelaskan peringatan "jangan mendekati sayap timur tanpa pengawalanku".

- Sebelum: "Peringatannya sangat tegas: jangan mendekati sayap timur kastel tanpa pengawalanku."
- Sesudah: "Peringatannya sangat tegas: jangan mendekati sayap timur kastel tanpa pengawalanku. Seorang prajurit balkon sudah melapor bahwa tiga orang asing berdiri lama di dekat sumur."

### 2.3 Nama institusi masih bercampur (Prioritas 2)

Di Bab 8 muncul: *balai majelis istana*, *majelis perbendaharaan*, *kantor perbendaharaan*, *meja perbendaharaan*, *dewan kota*, *ruang dewan*, *pintu dewan*, dan *balai istana*. Pembaca tidak bisa memastikan mana satu badan dan mana beberapa. Ini penting karena tema arc Leovard adalah kekuasaan atas versus diplomasi lewat dewan.

**Tugas (usulan penyeragaman, sesuaikan jika Penulis mau):**

| Peran | Nama tunggal | Ganti |
|-------|--------------|-------|
| Kantor Aldric | **Perbendaharaan** | "balai majelis istana" (sersan), "majelis perbendaharaan" (Garrett), "kantor perbendaharaan" (Tobias; "kantor" juga istilah modern) |
| Badan yang bersidang (tempat kursi wakil Distrik Pengrajin) | **dewan** (tanpa "kota") | "dewan kota", "ruang dewan" tetap sebagai tempat |
| Tempat Adipati menerima laporan | **balai istana** | pertahankan |

Contoh: sersan menjadi "perintah baru dikeluarkan dua jam lalu oleh Perbendaharaan", Garrett menjadi "agar Perbendaharaan bisa mengatur suara sesuka hati", Tobias menjadi "karena Perbendaharaan sedang berusaha membungkam kapten kalian".

Struktur kekuasaan lengkap (Adipati, Perbendaharaan, dewan, serikat) tetap menunggu keputusan Penulis di `lore/worldbuilding/kadipaten_leovard.md`.

### 2.4 Panjang (Prioritas 3, opsional)

3.280 kata, di bawah batas 3.500 tetapi masih ±300 di atas target 2.800-3.000. Tidak mendesak. Jika ingin dipangkas: paragraf bau dan keriuhan kota bawah, deskripsi dua belas penjaga dan menara gerbang, dan paragraf Kael tentang rasa rapuh di ruang tunggu (sebagian sudah dibawa gestur meraba pinggang).

## 3. Catatan Lore (untuk Penulis, tidak untuk dieksekusi AI)

1. **Urutan karier Bran.** `glossary.md` kini menyebut Bran "pernah berdinas" di Garda Utama dan juga di Garda Pembuka Jalur (masa muda, resimen dibubarkan ±20 musim lalu). Bab 5-6 menyebut Garrett dan Bran rekan sepuluh musim di Garda Utama. Tulis garis waktu empat baris di `lore/characters/bran.md`: kapan di Pembuka Jalur, kapan pindah ke Garda Utama, kapan pensiun (sebelum Kael lahir, ±19 musim lalu), agar angka 20 musim dan 10 musim tidak bertabrakan.
2. **Struktur kekuasaan Leovard** (Adipati, Perbendaharaan, dewan, serikat) dan apakah ada tokoh dewan yang jujur masih terbuka.
3. **Lokasi pecahan** kini jelas (di bawah bangunan penyimpanan di timur). Pastikan Bab 9 tidak mengulang "penemuan" ini.

## 4. Kriteria Selesai

- [x] Motif Tobias dinyatakan hanya oleh Tobias.
- [x] Pengamat balkon punya satu akibat di laporan Garrett.
- [x] Nama institusi konsisten di seluruh Bab 8.
- [x] (Opsional) Panjang ±3.000 kata (3.286 kata ID, di bawah batas maksimal 3.500 kata).
- [x] EN disinkronkan dan changelog diperbarui.
