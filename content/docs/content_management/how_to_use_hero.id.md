+++
title = "Hero"
description = "Panduan langkah demi langkah tentang cara membuat bagian Hero di Lontar Builder"
date = 2023-12-05T18:00:00+00:00
updated = 2023-12-05T18:00:00+00:00
draft = false
weight = 10
sort_by = "berat"
template = "docs/page.html"

[extra]
lead = 'Pelajari cara membuat bagian Hero di Lontar Builder dengan berbagai macam template yang bisa di gunakan'
toc = true
top = false
+++

## Macam-macam bagian Hero di Lontar Builder
Sebelumnya perlu anda ketahui bahwa di Lontar Builder untuk bagian hero ada beberapa template, tetapi untuk content nya tetap sama yaitu ada *gambar* , *judul* , dan *deskripsi* . Berikut ini beberapa macam template hero yang ada di Lontar Builder:

### HERO_1

<img src="../hero_1.png" alt="Preview template 1" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Hero 1, untuk membuat itu dapat menggunakan perintah dibawah ini:
```markdown
itle: HERO_1
hero(1)_section_content:
hero(1)_section_image(1) - "https://imgur.com/1bJQs4i"
hero(1)_section_title(1) - "Lorem ipsum dolor sit amet."
hero(1)_section_text(1) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt, accusantium."
hero(1)_section_text(2) - "More Information"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: Hero_1**: Ini merupakan format untuk membuat bagian hero menggunakan template 1
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **hero(1)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan diberi nama Hero atau yang lainnya pada bagian ini
4. **hero(1)_section_text(1&2)**: Ini merupakan text yang akan mengisi bagian-bagian hero
5. **-END**: Menandai akhir dari bagian hero, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya

### HERO_2

<img src="../hero_4.png" alt="Preview template 4" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Hero 2, untuk membuat itu dapat menggunakan perintah dibawah ini:
```markdown
Title: HERO_2
hero(2)_section_content:
hero(1)_section_image(1) - "https://imgur.com/1bJQs4i"
hero(2)_section_title(1) - "Welcome to Our Website"
hero(2)_section_text(1) - "Discover the best Lorem ipsum dolor sit amet, consectetur adipiscing elit."
hero(2)_section_text(2) - "More Information""
-END
```
Penjelasan Tipe Format di atas:

1. **Title: Hero_2**: Ini merupakan format untuk membuat bagian hero menggunakan template 2
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **hero(2)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan diberi nama Hero atau yang lainnya pada bagian ini
4. **hero(2)_section_text(1&2)**: Ini merupakan text yang akan mengisi bagian-bagian hero
5. **-END**: Menandai akhir dari bagian hero, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya

### HERO_3

<img src="../hero_4.png" alt="Preview template 4" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Hero 3, untuk membuat itu dapat menggunakan perintah dibawah ini:
```markdown
Title: HERO_3
hero(3)_section_content:
hero(3)_section_image(1) - "https://imgur.com/0PKM7eN"
hero(3)_section_title(1) - "Lorem ipsum dolor sit amet."
hero(3)_section_text(1) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt, accusantium."
hero(3)_section_text(2) - "More Information"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: Hero_3**: Ini merupakan format untuk membuat bagian hero menggunakan template 3
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **hero(3)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan diberi nama Hero atau yang lainnya pada bagian ini
4. **hero(3)_section_text(1&2)**: Ini merupakan text yang akan mengisi bagian-bagian hero
5. **-END**: Menandai akhir dari bagian hero, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya

### HERO_4

<img src="../hero_4.png" alt="Preview template 4" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Hero 4, untuk membuat itu dapat menggunakan perintah dibawah ini:
```markdown
Title: HERO_4
hero(4)_section_content:
hero(4)_section_image(1) - "https://source.unsplash.com/1600x900/?adventure"
hero(4)_section_title(1) - "Embark on Your Next Adventure"
hero(4)_section_text(1) - "Explore the world and create unforgettable memories with Adventure Seekers."
hero(4)_section_text(2) - "Start Your Journey"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: Hero_4**: Ini merupakan format untuk membuat bagian hero menggunakan template 4
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **hero(4)_section_image(1)**: ini digunakan untuk memanggil gambar yang nantinya akan muncul di halaman hero
4. **hero(4)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan diberi nama Hero atau yang lainnya pada bagian ini
5. **hero(4)_section_text(1&2)**: Ini merupakan text yang akan mengisi bagian-bagian hero
6. **-END**: Menandai akhir dari bagian hero, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya



    