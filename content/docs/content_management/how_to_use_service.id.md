+++
title = "Layanan"
description = "Panduan langkah demi langkah tentang cara membuat bagian Layanan di Lontar Builder"
date = 2023-12-05T18:00:00+00:00
updated = 2023-12-05T18:00:00+00:00
draft = false
weight = 10
sort_by = "berat"
template = "docs/page.html"

[tambahan]
lead = 'Pelajari cara membuat bagian Layanan di Lontar Builder dengan berbagai macam template yang bisa digunakan'
toc = true
top = false
+++

## Macam-macam bagian Layanan di Lontar Builder
Sebelumnya perlu Anda ketahui bahwa di Lontar Builder untuk bagian layanan terdapat beberapa template, namun untuk isinya tetap sama yaitu ada *gambar*, *teks*, dan *deskripsi*. Berikut ini beberapa template layanan yang ada di Lontar Builder:

### LAYANAN_1

[Klik di sini untuk melihat template Layanan 1] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Layanan 1, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Judul: LAYANAN_1
layanan(1)_bagian_konten:
layanan(1)_judul_bagian(1) - "Nama Perusahaan"
service(1) _section_text(1) - "Alamat, kota, negara Anda"
service(1)_section_text(2) - "Telepon: +123 456 789"
service(1)_section_text(3) - "Email: info@example.com"
service(1)_section_text(4) - "Facebook"
service(1)_section_text(5) - "twitter"
service(1)_section_text(6) - "Instagram"
-END
```

Penjelasan mengenai Tipe Format di atas:

1. **Judul: Layanan_1**: Ini adalah format untuk membuat bagian layanan menggunakan templat 1.
2. **judul_bagian_isi**: Menunjukkan awal konten bagian.
3. 3. **layanan(1)_judul_bagian(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Layanan atau nama lain di bagian ini.
4. **service(1)_section_text(1-6)**: Ini adalah teks yang akan mengisi bagian layanan.
5. **-END**: Menandai akhir dari bagian layanan, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.

### LAYANAN_2

[Klik di sini untuk melihat templat Layanan 2] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Layanan 2, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Judul: LAYANAN_2
layanan(2)_bagian_konten:
layanan(2)_judul_bagian(1) - "Nama Perusahaan"
service(2)_section_text(1) - "Alamat"
service(2)_section_text(2) - "Lorem ipsum dolor sit amet consectetur elit. Dignissimos corrupti nihil commodidolorum iste pariatur repudiandae quaerat."
service(2)_section_text(3) - "Kontak"
service(2)_section_text(4) - "Telepon: +123 456 789"
service(2)_section_text(5) - "Email: info@example.com"
service(2)_section_text(6) - "Media Sosial"
service(2)_section_text(7) - "Facebook"
service(2)_section_text(8) - "Twitter"
service(2)_section_text(9) - "Instagram"
-END
```
Penjelasan mengenai Tipe Format di atas:

1. **Judul: Layanan_2**: Ini adalah format untuk membuat bagian layanan menggunakan templat 1.
2. **judul_bagian_isi**: Menunjukkan awal konten bagian.
3. 3. **layanan(2)_judul_bagian(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Layanan atau nama lain di bagian ini.
4. **service(2)_section_text(1-9)**: Ini adalah teks yang akan mengisi bagian layanan.
5. **-END**: Menandai akhir dari bagian layanan, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.

### LAYANAN_3

[Klik di sini untuk melihat template Layanan 3] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh dari template Layanan 3, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Judul: LAYANAN_3
layanan(3)_bagian_konten:
service(3)_section_title(1) - "Hubungi Kami"
service(3)_section_text(1) - "123 Main Street, Cityville, Country"
service(3)_section_text(2) - "Email: info@example.com"
service(3)_section_text(3) - "Telepon: +123 456 789"
service(3)_section_text(4) - "© 2023 Perusahaan Anda. Semua hak cipta dilindungi undang-undang."
service(3)_section_text(5) - "Perusahaan terkemuka dalam solusi inovatif untuk kebutuhan Anda."
service(3)_section_image(1) - "https://imgur.com/1bJQs4i"
service(3)_section_image(2) - "https://imgur.com/1bJQs4i"
-END
```
Penjelasan dari Tipe Format di atas:

1. **Judul: Layanan_3**: Ini adalah format untuk membuat bagian layanan menggunakan templat 3.
2. **judul_bagian_isi**: Menunjukkan awal konten bagian.
3. 3. **layanan(3)_judul_bagian(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Layanan atau nama lain di bagian ini.
4. **service(3)_section_text(1-5)**: Ini adalah teks yang akan mengisi bagian layanan.
5. **service(3)_section_image(1&2)**: Ini digunakan untuk memasukkan url gambar di bagian layanan. Jika Anda memiliki gambar yang tersimpan di komputer lokal, Anda dapat menggunakan layanan berbagi gambar seperti imgur, imgbb, dan lainnya.
6. **-END**: Menandai akhir dari bagian layanan, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.

### LAYANAN_4

[Klik di sini untuk melihat template Layanan 4] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh dari template Layanan 4, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Judul: LAYANAN_4
layanan(4)_bagian_konten:
service(4)_section_title(1) - "© 2023 Para Pencari Petualangan. Semua hak cipta dilindungi undang-undang."
service(4)_section_text(1) - "Facebook"
service(4)_section_text(2) - "Twitter"
service(4)_section_text(3) - "Instagram"
-END
```

Penjelasan mengenai Tipe Format di atas:

1. **Judul: Layanan_4**: Ini adalah format untuk membuat bagian layanan menggunakan templat 4.
2. **judul_bagian_isi**: Menunjukkan awal konten bagian.
3. 3. **layanan(4)_judul_bagian(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Layanan atau nama lain di bagian ini.
4. **service(4)_section_text(1-3)**: Ini adalah teks yang akan mengisi bagian layanan.
5. **-END**: Menandai akhir dari bagian layanan, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.