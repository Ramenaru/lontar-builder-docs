+++
title = "Footer"
description = "Panduan langkah demi langkah tentang cara membuat bagian Footer di Lontar Builder"
date = 2023-12-05T18:00:00+00:00
updated = 2023-12-05T18:00:00+00:00
draft = false
weight = 10
sort_by = "berat"
template = "docs/page.html"

[tambahan]
lead = 'Pelajari cara membuat bagian Footer di Lontar Builder dengan berbagai macam template yang bisa digunakan'
toc = true
top = false
+++

## Macam-macam bagian Footer di Lontar Builder
Sebelumnya perlu Anda ketahui bahwa di Lontar Builder untuk bagian footer terdapat beberapa template, namun untuk isinya tetap sama yaitu ada *gambar*, *tulisan*, dan *deskripsi*. Berikut ini beberapa template footer yang ada di Lontar Builder:

### FOOTER_1

[Klik di sini untuk melihat template Footer 1] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Footer 1, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Title: FOOTER_1
footer(1)_section_content:
footer(1)_section_title(1) - "Company Name"
footer(1)_section_text(1) - "Your address, city, country"
footer(1)_section_text(2) - "Phone: +123 456 789"
footer(1)_section_text(3) - "Email: info@example.com"
footer(1)_section_text(4) - "Facebook"
footer(1)_section_text(5) - "twitter"
footer(1)_section_text(6) - "Instagram"
-END
```

Penjelasan tentang Tipe Format di atas:

1. **Title: Footer_1**: Ini adalah format untuk membuat bagian footer menggunakan template 1.
2. **title_section_content**: Menunjukkan awal konten bagian.
3. **footer(1)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Footer atau nama lain di bagian ini.
4. **footer(1)_section_text(1-6)**: Ini adalah teks yang akan mengisi bagian footer.
5. **-END**: Menandai akhir dari bagian footer, ini harus dimasukkan di setiap bagian lalu jangan lupa untuk memasukkan setelahnya.

### FOOTER_2

[Klik di sini untuk melihat template Footer 2] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Footer 2, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Title: FOOTER_2
footer(2)_section_content:
footer(2)_section_title(1) - "Company Name"
footer(2)_section_text(1) - "Address"
footer(2)_section_text(2) - "Lorem ipsum dolor sit amet consectetur elit. Dignissimos corrupti nihil commodidolorum iste pariatur repudiandae quaerat."
footer(2)_section_text(3) - "Contact"
footer(2)_section_text(4) - "Phone: +123 456 789"
footer(2)_section_text(5) - "Email: info@example.com"
footer(2)_section_text(6) - "Social Media"
footer(2)_section_text(7) - "Facebook"
footer(2)_section_text(8) - "Twitter"
footer(2)_section_text(9) - "Instagram"
-END
```

Penjelasan dari Tipe Format di atas:

1. **Title: Footer_2**: Ini adalah format untuk membuat bagian footer menggunakan template 1.
2. **title_section_content**: Menunjukkan awal konten bagian.
3. **footer(2)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Footer atau nama lain di bagian ini.
4. **footer(2)_section_text(1-9)**: Ini adalah teks yang akan mengisi bagian footer.
5. **-END**: Menandai akhir dari bagian footer, ini harus dimasukkan di setiap bagian lalu jangan lupa untuk memasukkan setelahnya.

### FOOTER_3

[Klik di sini untuk melihat template Footer 3] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Footer 3, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Title: FOOTER_3
footer(3)_section_content:
footer(3)_section_title(1) - "Contact Us"
footer(3)_section_text(1) - "123 Main Street, Cityville, Country"
footer(3)_section_text(2) - "Email: info@example.com"
footer(3)_section_text(3) - "Phone: +123 456 789"
footer(3)_section_text(4) - "© 2023 Your Company. All rights reserved."
footer(3)_section_text(5) - "A leading company in innovative solutions for your needs."
footer(3)_section_image(1) - "https://imgur.com/1bJQs4i"
footer(3)_section_image(2) - "https://imgur.com/1bJQs4i"
-END
```

Penjelasan tentang Tipe Format di atas:

1. **Title: Footer_3**: Ini adalah format untuk membuat bagian footer menggunakan template 3.
2. **title_section_content**: Menunjukkan awal konten bagian.
3. **footer(3)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Footer atau nama lain di bagian ini.
4. **footer(3)_section_image(1-5)**: Ini adalah teks yang akan mengisi bagian footer.
5. **footer(3)_section_image(1&2)**: Ini digunakan untuk memasukkan url gambar di bagian footer. Jika Anda memiliki gambar yang tersimpan di komputer lokal Anda, Anda dapat menggunakan layanan berbagi gambar seperti [imgur] (https://imgur.com/), [imgbb] (https://id.imgbb.com/), dan lainnya.
6. **-END**: Menandai akhir dari bagian footer, ini harus dimasukkan di setiap bagian lalu jangan lupa untuk memasukkan setelahnya.

### FOOTER_4

[Klik di sini untuk melihat template Footer 4] (https://imgur.com/trQ6SXD)

Gambar di atas adalah contoh template Footer 4, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Title: FOOTER_4
footer(4)_section_content:
footer(4)_section_title(1) - "© 2023 Adventure Seekers. All rights reserved."
footer(4)_section_text(1) - "Facebook"
footer(4)_section_text(2) - "Twitter"
footer(4)_section_text(3) - "Instagram"
-END
```

Penjelasan dari Tipe Format di atas:

1. **Title: Footer_4**: Ini adalah format untuk membuat bagian footer dengan menggunakan template 4.
2. **title_section_content**: Menunjukkan awal konten bagian.
3. **footer(4)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Footer atau nama lain di bagian ini.
4. **footer(4)_section_text(1-3)**: Ini adalah teks yang akan mengisi bagian footer.
5. **-END**: Menandai akhir dari bagian footer, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk Menambahkan setelahnya.