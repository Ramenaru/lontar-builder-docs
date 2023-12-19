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

Gambar di atas adalah contoh template Informasi 2, untuk membuat itu dapat menggunakan perintah dibawah ini:

```markdown
Title: INFO_2
info(2)_section_content:
info(2)_section_count - "6"
info(2)_section_title(1) - "INFORMATIONS"
info(2)_section_part(1)_text(1) - "Persiapan Terbaik untuk Melaksanakan Ibadah Haji dan Umroh"
info(2)_section_part(1)_link(1) - "https://target.com/link"
info(2)_section_part(1)_image(1) - "https://i.pinimg.com/564x/33/9d/6d/339d6db1dc0ea063795d38c27da7c1c9.jpg"

info(2)_section_part(2)_text(1) - "Tata Cara Pelaksanaan Umroh yang Benar dan Lengkap"
info(2)section_part(2)_link(1) - "https://target.com/link"
info(2)_section_part(2)_image(1) - "https://img.freepik.com/free-vector/realistic-islamic-pilgrimage_23-2148555081.jpg?w=740&t=st=1702279301~exp=1702279901~hmac=1365f99a7a667d3d7b54280bcf81c0d2628560e2da3cc4c8f0030b29386fea74"

info(2)_section_part(3)_text(1) - "Tips Aman dan Nyaman Selama Menjalani Ibadah Haji dan Umroh"
info(2)_section_part(3)_link(1) - "https://target.com/link"
info(2)_section_part(3)_image(1) - "https://img.freepik.com/free-vector/passenger-airplane-isolated_1284-41822.jpg?w=740&t=st=1702279405~exp=1702280005~hmac=a07b70acf455ed940895cb75e644cfa7a0f6480f1d1256ca31a9132147acafca"

info(2)_section_part(4)_text(1) - "Pentingnya Rencana Keuangan untuk Menunaikan Ibadah Haji"
info(2)_section_part(4)_link(1) - "https://target.com/link"
info(2)_section_part(4)_image(1) - "https://img.freepik.com/free-photo/portrait-cheerful-man-holding-dollar-bills-white-background_1150-63585.jpg?w=360&t=st=1702279561~exp=1702280161~hmac=bc82e2530ae7650094be4e51c17df3024f4c45e73532eb6bdef8dd737feb418b"

info(2)_section_part(5)_text(1) - "Destinasi Spiritual: Pengalaman Ibadah Haji di Tanah Suci"
info(2)section_part(5)_link(1) - "https://target.com/link"
info(2)_section_part(5)_image(1) - "https://img.freepik.com/free-photo/sheikh-zayed-grand-mosque-sunlight-blue-sky-abu-dhabi-united-arab-emirates_181624-48033.jpg?w=360&t=st=1702279639~exp=1702280239~hmac=99bbf705d81067759125422d752a702c5c37a4baf14582d8ca8bfbf80027e143"

info(2)_section_part(6)_text(1) - "Umroh Ramadhan: Memahami Keistimewaan Ibadah di Bulan Suci"
info(2)section_part(6)_link(1) - "https://target.com/link"
info(2)_section_part(6)_image(1) - "https://img.freepik.com/free-photo/close-up-hands-holding-crucifix_23-2149301765.jpg?w=360&t=st=1702279709~exp=1702280309~hmac=10771a3ce35ae85165ea2044425675b23f19cf22ae593e91244863b9bf39714e"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: INFO_2**: Ini merupakan format untuk membuat bagian Informasi menggunakan template 2
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **info(1)_section_count**: Digunakan untuk menentukan jumlah card.
4. **info(2)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan dikasih nama Informasi atau yang lainnya pada bagian ini.
5. **info(2)_section_part(1)_text(1)**: Ini digunakan untuk memasukan judul informasi pada card 1.
6. **info(2)_section_part(1)_link(1)**: Ini digunakan untuk memasukan link informasi pada card 1.
7. **info(2)_section_part(1)_image(1)**: Ini digunakan untuk memasukan lokasi gambar informasi pada card 1. Kenapa card 1, karena disana tertulis **part(1)** yang menandakan bahwa ini adalah bagian dari card 1. begitupun seterusnya untuk **part(2)**, **part(3)**, **part(4)**,  **part(5)**, **part(6)**,
8. **-END**: Menandai akhir dari bagian Informasi, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya.

### INFO_3

<img src="../info_3.png" alt="Preview template 3" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Informasi 3, untuk membuat itu dapat menggunakan perintah dibawah ini:

```markdown
Title: INFO_3
info(3)_section_content:
info(3)_section_count - "2"
info(3)_section_title(1) - "INFORMATIONS"
info(3)_section_part(1)_text(1) - "Kisah Inspiratif dari Para Jamaah Haji: Perjalanan Spiritual ke Baitullah"
info(3)_section_part(1)_text(2) - "Dalam "Kisah Inspiratif dari Para Jamaah Haji: Perjalanan Spiritual ke Baitullah," kita akan menjelajahi perjalanan penuh makna dari individu yang telah menunaikan ibadah haji. Melalui setiap kisah, kita akan meresapi pengalaman spiritual, ketekunan, dan momen epik yang melibatkan perjalanan ke Baitullah, tanah suci umat Islam"
info(3)_section_part(1)_link(1) - "https://target.com/link"
info(3)_section_part(1)_image(1) - "https://img.freepik.com/free-photo/muslim-women-using-tablet_23-2147796254.jpg?w=740&t=st=1702280470~exp=1702281070~hmac=d5d58e43a78b404fa539bd54bc269a34bba88c799458d412f34895bf008d3e7c"

info(3)_section_part(2)_text(1) - "Tata Cara Pelaksanaan Umroh yang Benar dan Lengkap"
info(3)_section_part(2)_text(2) - "Tata cara pelaksanaan umroh yang benar dan lengkap melibatkan beberapa langkah penting. Pertama, calon jamaah perlu mempersiapkan dokumen perjalanan seperti paspor dan visa. Selanjutnya, mereka harus menjalani pemeriksaan kesehatan untuk memastikan kondisi fisik yang memadai."
info(3)section_part(2)_link(1) - "https://target.com/link"
info(3)_section_part(2)_image(1) - "https://img.freepik.com/free-vector/realistic-islamic-pilgrimage_23-2148555081.jpg?w=740&t=st=1702279301~exp=1702279901~hmac=1365f99a7a667d3d7b54280bcf81c0d2628560e2da3cc4c8f0030b29386fea74"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: INFO_3**: Ini merupakan format untuk membuat bagian Informasi menggunakan template 3
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **info(1)_section_count**: Digunakan untuk menentukan jumlah card.
4. **info(3)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan dikasih nama Informasi atau yang lainnya pada bagian ini.
5. **info(3)_section_part(1)_text(1)**: Ini digunakan untuk memasukan judul informasi pada card 1.
6. **info(3)_section_part(1)_text(2)**: Ini digunakan untuk memasukan deskripsi informasi pada card 1.
7. **info(3)_section_part(1)_link(1)**: Ini digunakan untuk memasukan link informasi pada card 1.
8. **info(3)_section_part(1)_image(1)**: Ini digunakan untuk memasukan lokasi gambar informasi pada card 1. Kenapa card 1, karena disana tertulis **part(1)** yang menandakan bahwa ini adalah bagian dari card 1. begitupun seterusnya untuk **part(2)**.
9. **-END**: Menandai akhir dari bagian Informasi, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya.

### INFO_4

<img src="../info_4.png" alt="Preview template 4" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Informasi 4, untuk membuat itu dapat menggunakan perintah dibawah ini:

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
Penjelasan Tipe Format di atas:

1. **Title: INFO_2**: Ini merupakan format untuk membuat bagian Informasi menggunakan template 2
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **info(1)_section_count**: Digunakan untuk menentukan jumlah card.
4. **info(2)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan dikasih nama Informasi atau yang lainnya pada bagian ini.
5. **info(2)_section_part(1)_text(1)**: Ini digunakan untuk memasukan judul informasi pada card 2.
6. **info(2)_section_part(1)_text(2)**: Ini digunakan untuk memasukan deskripsi informasi pada card 1. Kenapa card 1, karena disana tertulis **part(1)** yang menandakan bahwa ini adalah bagian dari card 1. begitupun seterusnya untuk **part(2)**, **part(3)**, **part(4)**,  **part(5)**, **part(6)**,
7. **-END**: Menandai akhir dari bagian Informasi, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya.
