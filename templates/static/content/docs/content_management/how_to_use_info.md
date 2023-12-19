+++
title = "Informasi Section"
description = "Panduan langkah demi langkah tentang cara membuat bagian Informasi di Lontar Builder"
date = 2023-12-11T18:00:00+00:00
updated = 2023-12-11T18:00:00+00:00
draft = false
weight = 10
sort_by = "berat"
template = "docs/page.html"

[extra]
lead = 'Pelajari cara membuat bagian Informasi di Lontar Builder dengan berbagai macam template yang bisa di gunakan'
toc = true
top = false
+++

## Macam-macam bagian Informasi di Lontar Builder
Sebelumnya perlu anda ketahui bahwa di Lontar Builder untuk bagian Informasi ada beberapa template. Berikut ini beberapa macam template Informasi yang ada di Lontar Builder:

### INFO_1

<img src="../info_1.png" alt="Preview template 1" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Informasi 1, untuk membuat itu dapat menggunakan perintah dibawah ini:

```markdown
Title: INFO_1
info(1)_section_content:
info(1)_section_count - "6"
info(1)_section_title(1) - "INFORMATIONS"
info(1)_section_part(1)_text(1) - "Prosedur dan Persyaratan Pendaftaran Haji: Panduan Lengkap untuk Calon Jamaah."
info(1)_section_part(1)_link(1) - "https://target.com/link"
info(1)_section_part(1)_image(1) - "https://i.pinimg.com/564x/1c/d8/2c/1cd82c32b1d0fb32739f0d3467d401ff.jpg"

info(1)_section_part(2)_text(1) - "Manfaat dan Makna Spiritual Umroh: Perjalanan Ibadah yang Menginspirasi"
info(1)section_part(2)_link(1) - "https://target.com/link"
info(1)_section_part(2)_image(1) - "https://i.pinimg.com/564x/a1/e2/69/a1e2699adc41a718d4a2fccf60debd23.jpg"

info(1)_section_part(3)_text(1) - "Destinasi Terpopuler untuk Umroh: Menelusuri Keindahan Kota Suci"
info(1)_section_part(3)_link(1) - "https://target.com/link"
info(1)_section_part(3)_image(1) - "https://i.pinimg.com/564x/a0/60/1b/a0601b1b16c91a6c5fcc7073230e7bee.jpg"

info(1)_section_part(4)_text(1) - "Tata Cara Pelaksanaan Ibadah Haji: Langkah Demi Langkah Menuju Tanah Suci"
info(1)_section_part(4)_link(1) - "https://target.com/link"
info(1)_section_part(4)_image(1) - "https://i.pinimg.com/564x/72/76/32/727632deda15d99e0df6fc4fdb395dd1.jpg"

info(1)_section_part(5)_text(1) - "Peran Teknologi dalam Meningkatkan Pengalaman Haji dan Umroh"
info(1)section_part(5)_link(1) - "https://target.com/link"
info(1)_section_part(5)_image(1) - "https://i.pinimg.com/564x/c1/3d/d2/c13dd20c8132e7c2b1b7e8347e2278e9.jpg"

info(1)_section_part(6)_text(1) - "Aspek Kesehatan dalam Perjalanan Ibadah Haji: Tips dan Tindakan Pencegahan"
info(1)section_part(6)_link(1) - "https://target.com/link"
info(1)_section_part(6)_image(1) - "https://i.pinimg.com/564x/ee/5a/1b/ee5a1bea610ebfcd90fd20c2d5c30fe3.jpg"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: INFO_1**: Ini merupakan format untuk membuat bagian Informasi menggunakan template 1
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **info(1)_section_count**: Digunakan untuk menentukan jumlah card.
4. **info(1)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan dikasih nama Informasi atau yang lainnya pada bagian ini.
5. **info(1)_section_part(1)_text(1)**: Ini digunakan untuk memasukan judul informasi pada card 1.
6. **info(1)_section_part(1)_link(1)**: Ini digunakan untuk memasukan link informasi pada card 1.
7. **info(1)_section_part(1)_image(1)**: Ini digunakan untuk memasukan lokasi gambar informasi pada card 1. Kenapa card 1, karena disana tertulis **part(1)** yang menandakan bahwa ini adalah bagian dari card 1. begitupun seterusnya untuk **part(2)**, **part(3)**, **part(4)**,  **part(5)**, **part(6)**,
8. **-END**: Menandai akhir dari bagian Informasi, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya.

### INFO_2

<img src="../info_2.png" alt="Preview template 2" style="max-width: 100%; margin-bottom: 12px"/>

The image above is an example of an Information 2 template, to create it you can use the command below:

```markdown
Title: INFO_2
info(2)_section_content:
info(2)_section_count - "6"
info(2)_section_title(1) - "INFORMATIONS"
info(2)_section_part(1)_text(1) - "The Best Preparation for Carrying out the Hajj and Umrah Pilgrimage"
info(2)_section_part(1)_link(1) - "https://target.com/link"
info(2)_section_part(1)_image(1) - "https://i.pinimg.com/564x/33/9d/6d/339d6db1dc0ea063795d38c27da7c1c9.jpg"

info(2)_section_part(2)_text(1) - "Procedures for Performing Umrah Correctly and Completely"
info(2)section_part(2)_link(1) - "https://target.com/link"
info(2)_section_part(2)_image(1) - "https://img.freepik.com/free-vector/realistic-islamic-pilgrimage_23-2148555081.jpg?w=740&t=st=1702279301~exp=1702279901~ hmac=1365f99a7a667d3d7b54280bcf81c0d2628560e2da3cc4c8f0030b29386fea74"

info(2)_section_part(3)_text(1) - "Safe and Comfortable Tips During the Hajj and Umrah"
info(2)_section_part(3)_link(1) - "https://target.com/link"
info(2)_section_part(3)_image(1) - "https://img.freepik.com/free-vector/passenger-airplane-isolated_1284-41822.jpg?w=740&t=st=1702279405~exp=1702280005~ hmac=a07b70acf455ed940895cb75e644cfa7a0f6480f1d1256ca31a9132147acafca"

info(2)_section_part(4)_text(1) - "The Importance of a Financial Plan for Performing the Hajj"
info(2)_section_part(4)_link(1) - "https://target.com/link"
info(2)_section_part(4)_image(1) - "https://img.freepik.com/free-photo/portrait-cheerful-man-holding-dollar-bills-white-background_1150-63585.jpg?w= 360&t=st=1702279561~exp=1702280161~hmac=bc82e2530ae7650094be4e51c17df3024f4c45e73532eb6bdef8dd737feb418b"

info(2)_section_part(5)_text(1) - "Spiritual Destinations: The Hajj Experience in the Holy Land"
info(2)section_part(5)_link(1) - "https://target.com/link"
info(2)_section_part(5)_image(1) - "https://img.freepik.com/free-photo/sheikh-zayed-grand-mosque-sunlight-blue-sky-abu-dhabi-united-arab- emirates_181624-48033.jpg?w=360&t=st=1702279639~exp=1702280239~hmac=99bbf705d81067759125422d752a702c5c37a4baf14582d8ca8bfbf80027e143"

info(2)_section_part(6)_text(1) - "Ramadan Umrah: Understanding the Special Features of Worship in the Holy Month"
info(2)section_part(6)_link(1) - "https://target.com/link"
info(2)_section_part(6)_image(1) - "https://img.freepik.com/free-photo/close-up-hands-holding-crucifix_23-2149301765.jpg?w=360&t=st=1702279709~ exp=1702280309~hmac=10771a3ce35ae85165ea2044425675b23f19cf22ae593e91244863b9bf39714e"
-END
```
Explanation of the Format Type above:

1. **Title: INFO_2**: This is the format for creating an Information section using template 2
2. **title_section_content**: Indicates the beginning of the section content.
3. **info(1)_section_count**: Used to determine the number of cards.
4. **info(2)_section_title(1)**: This is used to enter the name of the title, whether it will be named Information or something else in this section.
5. **info(2)_section_part(1)_text(1)**: This is used to enter the information title on card 1.
6. **info(2)_section_part(1)_link(1)**: This is used to enter the information link on card 1.
7. **info(2)_section_part(1)_image(1)**: This is used to enter the location of the information image on card 1. Why card 1, because it says **part(1)** which indicates that this is part of card 1. and so on for **part(2)**, **part(3)**, **part(4)**, **part(5)**, **part(6) **,
8. **-END**: Marks the end of the Information section, this must be entered in every section then don't forget to enter enter afterwards.

### INFO_3

<img src="../info_3.png" alt="Preview template 3" style="max-width: 100%; margin-bottom: 12px"/>

The image above is an example of an Information 3 template, to create it you can use the command below:

```markdown
Title: INFO_3
info(3)_section_content:
info(3)_section_count - "2"
info(3)_section_title(1) - "INFORMATIONS"
info(3)_section_part(1)_text(1) - "Inspirational Stories from Hajj Pilgrims: Spiritual Journey to Baitullah"
info(3)_section_part(1)_text(2) - "In "Inspirational Stories from Hajj Pilgrims: A Spiritual Journey to Baitullah," we will explore the meaningful journey of individuals who have completed the Hajj. Through each story, we will absorb spiritual experiences, perseverance, and epic moments involving a journey to Baitullah, Islam's holy land"
info(3)_section_part(1)_link(1) - "https://target.com/link"
info(3)_section_part(1)_image(1) - "https://img.freepik.com/free-photo/muslim-women-using-tablet_23-2147796254.jpg?w=740&t=st=1702280470~exp= 1702281070~hmac=d5d58e43a78b404fa539bd54bc269a34bba88c799458d412f34895bf008d3e7c"

info(3)_section_part(2)_text(1) - "Procedures for Performing Umrah Correctly and Completely"
info(3)_section_part(2)_text(2) - "The correct and complete procedure for performing Umrah involves several important steps. First, prospective pilgrims need to prepare travel documents such as passports and visas. Next, they must undergo a health examination to ensure their condition physically adequate."
info(3)section_part(2)_link(1) - "https://target.com/link"
info(3)_section_part(2)_image(1) - "https://img.freepik.com/free-vector/realistic-islamic-pilgrimage_23-2148555081.jpg?w=740&t=st=1702279301~exp=1702279901~ hmac=1365f99a7a667d3d7b54280bcf81c0d2628560e2da3cc4c8f0030b29386fea74"
-END
```
Explanation of the Format Type above:

1. **Title: INFO_3**: This is the format for creating an Information section using template 3
2. **title_section_content**: Indicates the beginning of the section content.
3. **info(1)_section_count**: Used to determine the number of cards.
4. **info(3)_section_title(1)**: This is used to enter the name of the title, whether it will be named Information or something else in this section.
5. **info(3)_section_part(1)_text(1)**: This is used to enter the information title on card 1.
6. **info(3)_section_part(1)_text(2)**: This is used to enter a description of the information on card 1.
7. **info(3)_section_part(1)_link(1)**: This is used to enter the information link on card 1.
8. **info(3)_section_part(1)_image(1)**: This is used to enter the location of the information image on card 1. Why card 1, because it says **part(1)** which indicates that this is part of card 1. and so on for **part(2)**.
9. **-END**: Marks the end of the Information section, this must be entered in every section then don't forget to enter enter afterwards.

### INFO_4

<img src="../info_4.png" alt="Preview template 4" style="max-width: 100%; margin-bottom: 12px"/>

The image above is an example of an Information 4 template, to create it you can use the command below:

```markdown
Title: INFO_4
info(2)_section_content:
info(2)_section_count - "3"
info(2)_section_title(1) - "INFORMATIONS"
info(2)_section_part(1)_text(1) - "Booking Options"
info(2)_section_part(1)_text(2) - "Choose from a variety of booking options tailored to your preferences."

info(2)_section_part(2)_text(1) - "Booking Details"
info(2)_section_part(2)_text(2) - "Find information on booking procedures and available packages."

info(2)_section_part(3)_text(1) - "Safety Guidelines"
info(2)_section_part(3)_text(2) - "Your safety is our priority. Find information on safety guidelines during adventures."
-END
```
Explanation of the Format Type above:

1. **Title: INFO_2**: This is the format for creating an Information section using template 2
2. **title_section_content**: Indicates the beginning of the section content.
3. **info(1)_section_count**: Used to determine the number of cards.
4. **info(2)_section_title(1)**: This is used to enter the name of the title, whether it will be named Information or something else in this section.
5. **info(2)_section_part(1)_text(1)**: This is used to enter the information title on card 2.
6. **info(2)_section_part(1)_text(2)**: This is used to enter a description of the information on card 1. Why card 1, because it says **part(1)** which indicates that this is a section from card 1. and so on for **part(2)**, **part(3)**, **part(4)**, **part(5)**, **part(6)* *,
7. **-END**: Marks the end of the Information section, this must be entered in every section then don't forget to enter enter afterwards.