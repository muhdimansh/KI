# Tiga Bab, Satu Takdir — V5: Objek Interaktif & Pembetulan

## Cara kemas kini GitHub Pages

1. Ekstrak ZIP pada komputer. **Jangan upload fail .zip itu sendiri.**
2. Muat naik KANDUNGAN folder terus ke root repositori GitHub (`index.html` mesti berada di root).
3. Jika menggantikan versi lama, pilih fail yang sama untuk overwrite; kekalkan struktur `art/`, `audio/`, `puzzles/` dan `animations/`.
4. Pastikan GitHub Pages publish daripada branch `main` dan folder `/(root)`.
5. Buka semula laman menggunakan Chrome; cuba refresh jika versi lama disimpan dalam cache.

## Perubahan utama

- 36 objek PNG berilustrasi yang boleh disentuh untuk membuka puzzle secara terus.
- Papan laluan Peta Berlampu bersaiz responsif pada skrin kecil.
- Kompas menggunakan jarum yang jelas, bukan logo yang mengelirukan.
- Animasi judul kawasan tidak lagi mengganggu HUD kemajuan.
- Panel Baca Cerita boleh ditatal secara dalaman tanpa menindih hotspot.
- Semakan, petunjuk dan kawalan puzzle mengekalkan kedudukan skrol modal.
- Simpulan Terakhir diterangkan dengan anak panah dan garisan tali yang memberi maklum balas.
- Muzik latar OFF sebagai lalai, suasana lembut dan bunyi puzzle lebih kuat; muzik boleh dihidupkan sendiri.
- Kaset Rakaman Terbalik kini ada pratonton suara nombor dalam Bahasa Melayu.
- Dua puzzle Melodi yang tidak jelas telah digantikan: Penapis Gangguan dan Kod Loceng Kotak Muzik.
- Arah sambungan speaker dan arahan lain dipaparkan penuh tanpa pemotongan teks.
- Input ditaip dengan kontras gelap pada latar cerah.
- Halaman Koyak ditukar kepada 6 cebisan, bukan 4.
- Lampu ke cermin mempunyai garisan cahaya sebenar dan sejajar di 90°.
- Dua Lapisan Cerita mengandungi dua helai dan putaran yang berubah berdasarkan sudut.
- Jurnal Petunjuk untuk Halaman Terakhir menyimpan semula DAMAI / 241 / KI.
- Tandatangan surat akhir: -sayang awak.
- Perjalanan Ki: halaman yang selesai boleh dibuka semula tanpa mengubah kemajuan.
- Tiada perubahan kepada 3 hadiah, urutan bab atau hadiah/hari jadi Ki.

## QA

- 36/36 jawapan sah diperiksa dalam ujian pelayar berautomasi.
- 36/36 langkah diselesaikan berturut-turut sehingga semua hadiah dan surat akhir.
- Tiada ralat JavaScript dalam ujian tersebut.
- Papan Peta Berlampu diuji pada lebar 320, 375, 390, 430 px; tiada overflow mendatar.
- Kedudukan scroll dalam puzzle modal diuji sebelum/selepas petunjuk.
- Ujian jurnal ulang tayang tidak mengubah progress asal.
- Ujian ini dalam emulasi Chromium; sila uji juga pada iPhone sebenar.

**Nota:** Muzik kini bermula pada volum 0% secara lalai; suasana hujan/taman/perpustakaan masih boleh didengar dengan perlahan selepas Audio dihidupkan. SFX casette menggunakan suara sintetik, bukan rakaman manusia.
