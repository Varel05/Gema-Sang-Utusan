---
title: "Revision Brief Bab 7: Tahap 2 (Sisa Perbaikan)"
type: meta/revision-brief
sumber: "Review developmental editor atas repo Gema-Sang-Utusan, commit a2d661a (2026-11-02 10:36 WIB)"
cakupan: "chapters/id/chapter_07.md dan chapters/en/chapter_07.md, plus satu catatan lore"
tags:
  - meta/revisi
  - editorial
---

# Revision Brief Bab 7: Tahap 2

## 0. Cara Memakai Dokumen Ini (untuk AI)

- Brief ini hanya memuat **sisa** perbaikan setelah revisi tahap 1. Jangan mengulang pekerjaan yang sudah selesai (POV per adegan, Lingkaran Diam tanpa khotbah, agensi Azariel, motif Haldor, penutup Vane, istilah anakronistik).
- Patuhi `Panduan.md`: Strict POV, Mortal Sensory Realism, penyaringan istilah anakronistik, anti-em-dash.
- **Jangan mengubah `lore/` tanpa persetujuan Penulis.** Tandai perubahan kanon sebagai `[USULAN KANON BARU]`.
- Nomor baris mengacu ke commit `a2d661a`. Verifikasi sebelum menyunting.
- Contoh *before/after* adalah arah, bukan teks final.
- Kerjakan per tugas, catat di `update/changelog.md`, lalu sinkronkan ke versi EN.
- Jika sebuah temuan ternyata keliru terhadap teks, sampaikan secara jujur kepada Penulis.

## 1. Status Singkat

Tahap 1 berhasil. Yang tersisa adalah satu konflik umur, penumpukan tema, beberapa istilah, dan penutup bab.

**Jangan diubah:** karavan abu dan hening serangga; sepatu kecil Garrett; Kael membentengi Azariel; gesekan Mira-Azariel di Lingkaran Diam; getaran Pecahan #2 yang kini sensorik; Garrett berbisik "Vane" dan bunyi sarung tangan berdecit.

## 2. Tugas

### 2.1 Konflik umur: siapa "prajurit perbatasan tua"? (Prioritas 1, butuh keputusan Penulis)

Garrett bercerita bahwa saat ia masih bocah, seorang prajurit tua menemani ayahnya wafat, dan lambang di zirah prajurit itu sama dengan lambang pedang Kael. `meta/outline.md` menyebut ini petunjuk bahwa itu **Bran**. Tetapi Bran dan Garrett adalah rekan sebaya yang bertugas bersama sepuluh musim di dinding utara. Saat Garrett masih bocah, Bran juga masih kanak-kanak. Maka prajurit itu tidak bisa Bran.

**Pilihan (Penulis memutuskan):**
- **A:** Prajurit itu adalah **ayah Bran (kakek Kael)**. Ini menambah lapisan garis keturunan, selaras dengan tema pelindung, dan memberi Garrett alasan lebih dalam untuk percaya pada Kael. `[USULAN KANON BARU]`
- **B:** Lambang itu hanyalah lambang umum Garda Utama, dan tidak ada petunjuk khusus soal Bran. Perbaiki baris di `outline.md` yang menyebut "petunjuk lambang zirah yang sama dengan pedang Bran".

**Tugas setelah keputusan:**
- Pastikan teks Bab 7 tidak menyiratkan identitas yang bertentangan dengan pilihan itu.
- Jika memilih A, pastikan Kael tidak langsung mengenali kakeknya dari lambang saja (ia tidak boleh tahu lebih dari yang bisa ia tahu).
- Perbaiki frasa **"pedang peninggalan ayahnya"** (adegan api unggun) menjadi "pedang pemberian ayahnya", karena "peninggalan" terbaca seolah Bran sudah wafat.

### 2.2 Tema diucapkan tiga kali berturut-turut (Prioritas 1)

Di adegan api unggun, gagasan "datang terlambat tetapi tetap melangkah" diucapkan oleh tiga orang:
1. Garrett: "...agar aku memiliki kecepatan untuk menjadi orang yang datang lebih cepat".
2. Kael: "...pelindung sejati adalah yang tidak berhenti melangkah setelah terlambat".
3. Azariel: "...tidak ada yang namanya terlambat".

**Tugas:**
- Pertahankan Garrett (motivasinya memang ia yang menyatakan).
- **Kael tidak menuntaskan kalimatnya.** Biarkan ia terbata atau berhenti di tengah ("Ayah bilang... yang penting bukan... Ah, aku tidak pandai merangkainya, Kapten"). Kejujuran yang canggung lebih tepat untuk usia 19 dan tidak menumpuk tema.
- **Azariel tidak berbicara di sini.** Biarkan ia hanya menggeser sepotong bara ke bawah abu perapian, tanpa komentar. Pesan sampai lewat gerakan.

*Contoh arah:*
- Sebelum: "Bara itu belum mati, Mira... hanya tertimbun abu. Selama masih ada hangat yang tersisa di dalamnya, tidak ada yang namanya terlambat."
- Sesudah: Azariel menggeser sebutir bara yang hampir padam ke bawah abu dengan ujung ranting, lalu menutupnya. Mira melihatnya, dan tidak bertanya apa pun.

### 2.3 Dua aforisme Azariel bersaing (Prioritas 2)

Kalimat Azariel di Lingkaran Diam ("Sesuatu yang masih sanggup tumbuh di tanah mati layak diberi kesempatan bernapas, Mira") dan baris bara di atas sama-sama berbentuk slogan.

**Tugas:** pertahankan **satu**. Jika 2.2 diterapkan (Azariel diam di perapian), kalimat di Lingkaran Diam otomatis menjadi satu-satunya. Pastikan ia tidak terlalu rapi: Azariel bukan penyair (kelemahan utamanya adalah kekakuan emosi), jadi pertimbangkan jawaban yang lebih pendek dan canggung.

### 2.4 Istilah dan konsistensi (Prioritas 2)

| Lokasi | Masalah | Perbaikan |
|--------|---------|-----------|
| "para carter garam", "rami carter" (3 kali) | Kata Inggris dalam prosa | Ganti dengan "para pengangkut garam" atau "penarik pedati" |
| Simpul di batu kerikil | Dijelaskan dua kali: narator ("simpul sederhana... agar bekal tidak terlepas") dan Garrett ("simpul doa") | Pilih satu. Disarankan hanya Garrett yang menyebut "simpul doa", dan narator tidak menafsirkan |
| "jalan prioritas" (penutup bab) | Istilah modern | Ganti dengan "jalan lebih dulu" atau "hak jalan" |
| "tombak" | Dipakai ganda: senjata dan satuan jarak ("sepuluh tombak di depan") | Ganti satuan jarak (mis. "belasan langkah") |
| "The Husks" (2 kali) | Penulisan Inggris dengan huruf kapital | Putuskan kebijakan "The Husk/The Husks" atau "para Husk" dan seragamkan di seluruh bab dan lore (butuh keputusan Penulis) |

### 2.5 Sisa POV (Prioritas 3)

Adegan Kael (karavan): "Dua rekannya tewas di ngarai utara beberapa hari lalu, dan... membakar amarahnya" memuat isi hati dan latar Haldor yang tidak bisa diketahui Kael.

**Tugas:** ubah menjadi gestur dan ucapan yang teramati. Latar bisa disampaikan Haldor sendiri lewat bentakannya.

*Contoh arah:*
- Sebelum: "Dua rekannya tewas di ngarai utara beberapa hari lalu, dan melihat pemuda bertudung asing ini berkeliaran menyentuh batu terkutuk membakar amarahnya."
- Sesudah: Haldor bertubuh kurus, matanya cekung, dan tangannya bergetar di gagang tombak. "Dua kawanku ada di bawah abu sana," desisnya. "Apakah pemuda ini harus menyentuh setiap batu di jalan ini?"

### 2.6 Penutup bab (Prioritas 2)

Dua paragraf terakhir meringkas dari luar adegan: "hembusan napasnya yang berat dan pandangannya... menyiratkan bahwa di balik tembok-tembok kokoh kadipaten, perang dingin yang penuh kecurigaan telah menanti kedatangan mereka."

**Tugas:** akhiri pada gambar atau tindakan, bukan ringkasan. Pilihan: berhenti pada kalimat Kael tentang Vane, atau pada sarung tangan Garrett yang berdecit, dengan satu baris sensorik dari Azariel (dentang dingin dari bawah benteng yang menguat).

### 2.7 Motif Vane (Prioritas 3)

Kael menyebut Vane "mencemooh Kakek... dipimpin orang-orang tua yang terlalu banyak berdoa". Itu ejekan, bukan klaim kepemimpinan. `lore/characters/vane.md` memuat ambisi menggulingkan keluarga Tetua dan menjadi Pemimpin Desa.

**Tugas:** tambahkan satu kalimat yang menyentuh suksesi (garis keluarga Tetua dianggap sudah habis; Mira dianggap terlalu belia). Satu kalimat cukup, dan bisa diucapkan Kael atau Mira.

## 3. Catatan Lore (untuk Penulis, tidak untuk dieksekusi AI)

Revisi Bab 7 memperkenalkan kanon baru yang belum ada di `lore/`:
- **Lingkaran Diam:** area bersih dari pembusukan, tiga tunas pinus, simpul doa.
- Azariel bisa **menopang** tunas dengan bara dari dadanya, dengan harga kebas di tangan kanan.
- Pertanyaan terbuka: apakah lingkaran mati jika Azariel pergi? Apakah ketulusan doa atau kehadiran bara yang menentukan? Apakah ini aturan umum untuk Corrosion?

Jangan menulis berkas lore baru sebelum Penulis memutuskan.

## 4. Urutan Kerja

1. Tunggu keputusan Penulis untuk 2.1 dan istilah Husk (2.4).
2. Terapkan 2.2, 2.3, 2.6 (adegan api unggun dan penutup).
3. Terapkan 2.4, 2.5, 2.7 (istilah, POV, motif).
4. Sinkronkan ke `chapters/en/chapter_07.md` dan perbarui `update/changelog.md`.

## 5. Kriteria Selesai

- [ ] Identitas "prajurit tua" diputuskan, dan `outline.md` serta teks tidak bertentangan dengan umur Bran dan Garrett.
- [ ] Tema "terlambat" hanya dinyatakan satu kali secara lugas (oleh Garrett).
- [ ] Hanya ada satu aforisme Azariel di bab ini.
- [ ] Kata "carter" hilang, "peninggalan ayahnya" dan "jalan prioritas" diperbaiki, dan satuan jarak tidak lagi ambigu.
- [ ] Batin Haldor tidak lagi dibaca dari POV Kael.
- [ ] Penutup bab berakhir pada gambar atau tindakan.
- [ ] Satu kalimat suksesi Vane ditanam.
- [ ] EN disinkronkan dan changelog diperbarui.
