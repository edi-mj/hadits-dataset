# Dataset Hadits dengan Terjemahan Bahasa Indonesia

Selamat datang di repositori Dataset Hadits. Repositori ini berisi kumpulan hadits dari berbagai kitab yang dilengkapi dengan terjemahan dalam Bahasa Indonesia.

Dataset ini dihasilkan melalui proses *web scraping* dari situs **[hadits.tazkia.ac.id](https://hadits.tazkia.ac.id/)**, sebuah sumber daya publik yang luar biasa untuk studi hadits. Tujuan dari repositori ini adalah untuk menyediakan data hadits dalam format yang terstruktur (CSV) agar mudah diakses dan diolah untuk berbagai keperluan, seperti penelitian, analisis teks (NLP), pengembangan aplikasi, atau sekadar untuk pembelajaran pribadi.

## Tentang Dataset

Dataset ini mencakup ribuan hadits dari kitab-kitab utama, antara lain:
- Shahih Bukhari
- Shahih Muslim
- Sunan Abu Daud
- Sunan Tirmidzi
- Sunan Nasa'i
- Sunan Ibnu Majah
- Dan lainnya sesuai yang tersedia di situs sumber.

Setiap file CSV dinamai sesuai dengan kitab haditsnya dan berisi data yang telah dibersihkan sebatas kemampuan proses scraping.

## Struktur Data

Setiap baris dalam file `.csv` merepresentasikan satu hadits dan memiliki kolom-kolom berikut:

-   `nomor_hadits`: Judul atau nomor hadit yang mencakup nama perawi dan nomor urutnya.
-   `teks_arab`: Matan (teks utama) hadits dalam tulisan Arab.
-   `terjemahan`: Terjemahan lengkap hadits dalam Bahasa Indonesia.

## 📜 Etika Penggunaan dan Disclaimer

**PENTING:** Mohon perhatikan poin-poin berikut sebelum menggunakan dataset ini.

1.  **Sumber Utama:** Dataset ini **bukanlah sumber primer**. Semua data berasal dan merupakan hak milik dari **[hadits.tazkia.ac.id](https://hadits.tazkia.ac.id/)**. Repositori ini hanya bertindak sebagai penyedia data dalam format yang berbeda.

2.  **Tanpa Jaminan Akurasi:** Proses *web scraping* rentan terhadap kesalahan. Meskipun telah diupayakan untuk menjaga integritas data, tidak ada jaminan bahwa 100% data akurat dan bebas dari kesalahan. Untuk keperluan studi akademis yang serius atau fatwa, **wajib melakukan verifikasi kembali** dengan merujuk ke sumber aslinya atau kitab-kitab hadits yang terverifikasi.

3.  **Tujuan Non-Komersial:** Dataset ini dibagikan untuk tujuan pendidikan, penelitian, dan pengembangan non-komersial. Dilarang keras menggunakan dataset ini untuk tujuan komersial yang dapat merugikan pihak manapun.

4.  **Hargai Sumber Asli:** Jika Anda menggunakan dataset ini, kami sangat menganjurkan Anda untuk memberikan atribusi (menyebutkan sumber) tidak hanya ke repositori ini, tetapi juga dan terutama kepada **[hadits.tazkia.ac.id](https://hadits.tazkia.ac.id/)** sebagai sumber data primer.

5.  Ucapan Terima Kasih
Apresiasi tertinggi dan ucapan terima kasih kami sampaikan kepada tim di balik Institut Tazkia dan situs hadits.tazkia.ac.id yang telah menyediakan sumber daya ilmu yang sangat berharga dan mudah diakses oleh publik. Semoga menjadi amal jariyah yang tak terputus.

Lisensi
Repositori dan skrip di dalamnya berada di bawah Lisensi MIT. Namun, data hadits itu sendiri tunduk pada hak dan aturan dari sumber aslinya. Harap gunakan dengan bijak dan bertanggung jawab.
