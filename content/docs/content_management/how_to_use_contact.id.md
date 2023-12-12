+++
title = "Kontak"
description = "Panduan langkah demi langkah tentang cara membuat bagian Kontak di Lontar Builder"
date = 2023-12-05T18:00:00+00:00
updated = 2023-12-05T18:00:00+00:00
draft = false
weight = 10
sort_by = "berat"
template = "docs/page.html"

[tambahan]
lead = 'Pelajari cara membuat bagian Kontak di Lontar Builder dengan berbagai macam template yang bisa digunakan'
toc = true
top = false
+++

## Macam-macam bagian Kontak di Lontar Builder
Sebelumnya perlu Anda ketahui bahwa di Lontar Builder untuk bagian kontak terdapat beberapa template, namun untuk isinya tetap sama yaitu ada *gambar*, *tulisan*, dan *deskripsi*. Berikut ini beberapa template kontak yang ada di Lontar Builder:

### FOOTER_1


[Klik di sini untuk melihat template Footer 1] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Footer 1, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Judul FOOTER_1
footer(1)_bagian_konten:
footer(1)_bagian_judul(1) - "Nama Perusahaan"
footer(1)_bagian_teks(1) - "Alamat, kota, negara Anda"
footer(1)_bagian_teks(2) - "Telepon: +123 456 789"
footer(1)_section_text(3) - "Email: info@example.com"
footer(1)_section_text(4) - "Facebook"
footer(1)_section_text(5) - "twitter"
footer(1)_section_text(6) - "Instagram"
-END
```

Penjelasan mengenai Tipe Format di atas:

1. **Judul: Footer_1**: Ini adalah format untuk membuat bagian footer menggunakan template 1.
2. **judul_bagian_isi**: Menunjukkan awal konten bagian.
3. **footer(1)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Footer atau nama lain di bagian ini.
4. **footer(1)_section_text(1-6)**: Ini adalah teks yang akan mengisi bagian footer.
5. **-END**: Menandai akhir dari bagian footer, ini harus dimasukkan di setiap bagian lalu jangan lupa untuk memasukkan setelahnya.

### FOOTER_2

[Klik di sini untuk melihat template Footer 2] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Footer 2, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Judul FOOTER_2
footer(2)_bagian_konten:
footer(2)_section_title(1) - "Nama Perusahaan"
footer(2) _section_text(1) - "Alamat"
footer(2)_section_text(2) - "Lorem ipsum dolor sit amet consectetur elit. Dignissimos corrupti nihil commodidolorum iste pariatur repudiandae quaerat."
footer(2)_section_text(3) - "Kontak"
footer(2)_section_text(4) - "Telepon: +123 456 789"
footer(2)_section_text(5) - "Email: info@example.com"
footer(2)_section_text(6) - "Media Sosial"
footer(2)_section_text(7) - "Facebook"
footer(2)_section_text(8) - "Twitter"
footer(2)_section_text(9) - "Instagram"
-END
```

Penjelasan mengenai Tipe Format di atas:

1. **Judul: Footer_2**: Ini adalah format untuk membuat bagian footer menggunakan template 1.
2. **Judul_bagian_isi**: Menunjukkan awal konten bagian.
3. **footer (2)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Footer atau nama lain di bagian ini.
4. **footer(2)_section_text(1-9)**: Ini adalah teks yang akan mengisi bagian footer.
5. **-END**: Menandai akhir dari bagian footer, ini harus dimasukkan di setiap bagian lalu jangan lupa untuk memasukkan setelahnya.

### KONTAK_3

[Klik di sini untuk melihat template Kontak 1] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Kontak 3, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Judul: KONTAK_3
kontak(3)_bagian_konten:
contact(3)_section_title(1) - "KONTAK KAMI"
contact(3)_section_text(1) - "Pertanyaan Umum"
contact(3)_section_text(2) - "Untuk pertanyaan dan informasi umum"
contact(3)_section_text(3) - "Email: info@yourcompany.com"
contact(3)_section_text(4) - "Telepon: +1 (123) 456-7890"
contact(3)_section_text(5) - "Peluang Kemitraan"
contact(3)_section_text(6) - "Tertarik untuk menjadi mitra kami?"
contact(3)_section_text(7) - "Email: partnerships@yourcompany.com"
contact(3)_section_text(8) - "Telepon: +1 (234) 567-8901"
-END
```

Penjelasan mengenai Tipe Format di atas:

1. **Judul: Kontak_3**: Ini adalah format untuk membuat bagian kontak menggunakan templat 3.
2. **judul_bagian_isi**: Menunjukkan awal konten bagian.
3. 3. **kontak(3)_judul_seksi(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Kontak atau nama lain di bagian ini.
4. **contact(3)_section_text(1-8)**: Ini adalah teks yang akan mengisi bagian kontak.
5. **-END**: Menandai akhir dari bagian kontak, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.


### KONTAK_4

[Klik di sini untuk melihat template Kontak 1] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh dari template Contact 4, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```
penurunan harga
Salin kode
Judul: CONTACT_4
kontak(4)_bagian_konten:
contact(4)_section_title(1) - "Terhubung dengan Kami"
contact(4)_section_text(1) - "Siap untuk memulai petualangan Anda berikutnya bersama kami? Hubungi kami sekarang!"
contact(4)_section_text(2) - "Hubungi Sekarang"
-END
```

Penjelasan Tipe Format di atas:

1. 2. **Judul**: Contact_4: Ini adalah format untuk membuat bagian kontak menggunakan templat 4.
2. **judul_bagian_isi**: Menunjukkan awal konten bagian.
3. 3. **kontak(4)_judul_bagian(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Kontak atau nama lain di bagian ini.
4. **contact(4)_section_text(1-3)**: Ini adalah teks yang akan mengisi bagian kontak.
5. **-END**: Menandai akhir dari bagian kontak, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.