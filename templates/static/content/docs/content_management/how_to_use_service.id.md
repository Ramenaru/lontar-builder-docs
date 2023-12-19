+++
title = "Service Section"
description = "Panduan langkah demi langkah tentang cara membuat bagian Service di Lontar Builder"
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

## Macam-macam bagian Service di Lontar Builder
Sebelumnya perlu anda ketahui bahwa di Lontar Builder untuk bagian Service ada beberapa template. Berikut ini beberapa macam template Service yang ada di Lontar Builder:

### SERVICE_1

<img src="../service1.png" alt="Preview template 1" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Service 1, untuk membuat itu dapat menggunakan perintah dibawah ini:

```markdown
Title: SERVICE_1
service(1)_section_content:
service(1)_section_count - "3"
service(1)_section_title(1) - "OUR SERVICES"
service(1)_section_part(1)_text(1) - "Lorem"
service(1)_section_part(1)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed alias nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(1)_section_part(1)_link(1) - "https://target.com/link"
service(1)_section_part(1)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(1)_section_part(2)_text(1) - "Ipsum"
service(1)_section_part(2)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus soluta omnis eos nobis sapiente, vero commodi eaque, repellat nisi aliquam non! Provident nemo tempore quos labore doloremque magnam velit beatae, consequuntur, modi natus distinctio! Cum qui numquam sapiente pariatur non."
service(1)section_part(2)_link(1) - "https://target.com/link"
service(1)_section_part(2)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(1)_section_part(3)_text(1) - "Dolor"
service(1)_section_part(3)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(1)_section_part(3)_link(1) - "https://target.com/link"
service(1)_section_part(3)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: SERVICE_1**: Ini merupakan format untuk membuat bagian Service menggunakan template 1
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **service(1)_section_count**: Digunakan untuk menentukan jumlah card.
4. **service(1)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan dikasih nama OUR SERVICES atau yang lainnya pada bagian ini.
5. **service(1)_section_part(1)_text(1)**: Ini digunakan untuk memasukan judul Service pada card 1.
6. **service(1)_section_part(1)_text(2)**: Ini digunakan untuk memasukan deskripsi Service pada card 1.
7. **service(1)_section_part(1)_link(1)**: Ini digunakan untuk memasukan link terkait Service pada card 1.
8. **service(1)_section_part(1)_image(1)**: Ini digunakan untuk memasukan lokasi gambar Service pada card 1. Kenapa card 1, karena disana tertulis **part(1)** yang menandakan bahwa ini adalah bagian dari card 1. begitupun seterusnya untuk **part(2)**, **part(3)**, **part(4)**,  **part(5)**, **part(6)**.
9. **-END**: Menandai akhir dari bagian Informasi, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya.

### SERVICE_2

<img src="../service2.png" alt="Preview template 2" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Service 2, untuk membuat itu dapat menggunakan perintah dibawah ini:

```markdown
Title: SERVICE_2
service(2)_section_content:
service(2)_section_count - "6"
service(2)_section_title(1) - "OUR SERVICES"
service(2)_section_part(1)_text(1) - "Lorem"
service(2)_section_part(1)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed alias nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(1)_link(1) - "https://target.com/link"
service(2)_section_part(1)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(2)_section_part(2)_text(1) - "Lorem"
service(2)_section_part(2)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed alias nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(2)_link(1) - "https://target.com/link"
service(2)_section_part(2)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(2)_section_part(3)_text(1) - "Lorem"
service(2)_section_part(3)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed alias nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(3)_link(1) - "https://target.com/link"
service(2)_section_part(3)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(2)_section_part(4)_text(1) - "Lorem"
service(2)_section_part(4)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed alias nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(4)_link(1) - "https://target.com/link"
service(2)_section_part(4)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(2)_section_part(5)_text(1) - "Lorem"
service(2)_section_part(5)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed alias nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(5)_link(1) - "https://target.com/link"
service(2)_section_part(5)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(2)_section_part(6)_text(1) - "Lorem"
service(2)_section_part(6)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed alias nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(6)_link(1) - "https://target.com/link"
service(2)_section_part(6)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: SERVICE_2**: Ini merupakan format untuk membuat bagian Service menggunakan template 1
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **service(2)_section_count**: Digunakan untuk menentukan jumlah card.
4. **service(2)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan dikasih nama OUR SERVICES atau yang lainnya pada bagian ini.
5. **service(2)_section_part(1)_text(1)**: Ini digunakan untuk memasukan judul Service pada card 1.
6. **service(2)_section_part(1)_text(2)**: Ini digunakan untuk memasukan deskripsi Service pada card 1.
7. **service(2)_section_part(1)_link(1)**: Ini digunakan untuk memasukan link terkait Service pada card 1.
8. **service(2)_section_part(1)_image(1)**: Ini digunakan untuk memasukan lokasi gambar Service pada card 1. Kenapa card 1, karena disana tertulis **part(1)** yang menandakan bahwa ini adalah bagian dari card 1. begitupun seterusnya untuk **part(2)**, **part(3)**, **part(4)**,  **part(5)**, **part(6)**.
9. **-END**: Menandai akhir dari bagian Informasi, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya.

### SERVICE_3

<img src="../service3.png" alt="Preview template 3" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Service 3, untuk membuat itu dapat menggunakan perintah dibawah ini:

```markdown
Title: SERVICE_3
service(3)_section_content:
service(3)_section_count - "4"
service(3)_section_title(1) - "OUR SERVICES"
service(3)_section_part(1)_text(1) - "Lorem"
service(3)_section_part(1)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(3)_section_part(1)_link(1) - "https://target.com/link"

service(3)_section_part(2)_text(1) - "Umroh"
service(3)_section_part(2)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(3)_section_part(2)_link(1) - "https://target.com/link"

service(3)_section_part(3)_text(1) - "Umroh"
service(3)_section_part(3)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(3)_section_part(3)_link(1) - "https://target.com/link"

service(3)_section_part(4)_text(1) - "Lorem"
service(3)_section_part(4)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(3)_section_part(4)_link(1) - "https://target.com/link"
-END
```
Penjelasan Tipe Format di atas:

1. **Title: SERVICE_3**: Ini merupakan format untuk membuat bagian Service menggunakan template 3.
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **service(3)_section_count**: Digunakan untuk menentukan jumlah card.
4. **service(3)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan dikasih nama OUR SERVICES atau yang lainnya pada bagian ini.
5. **service(3)_section_part(1)_text(1)**: Ini digunakan untuk memasukan judul Service pada card 1.
6. **service(3)_section_part(1)_text(2)**: Ini digunakan untuk memasukan deskripsi Service pada card 1.
7. **service(3)_section_part(1)_link(1)**: Ini digunakan untuk memasukan link terkait Service pada card 1. Kenapa card 1, karena disana tertulis **part(1)** yang menandakan bahwa ini adalah bagian dari card 1. begitupun seterusnya untuk **part(2)**, **part(3)**, **part(4)**.
8. **-END**: Menandai akhir dari bagian Informasi, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya.

### SERVICE_4

<img src="../service4.png" alt="Preview template 3" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Service 4, untuk membuat itu dapat menggunakan perintah dibawah ini:

```markdown
Title: SERVICE_4
service(4)_section_content:
service(4)_section_count - "3"
service(4)_section_title(1) - "Discover Our Services"
service(4)_section_part(1)_text(1) - "Adventure Tours"
service(4)_section_part(1)_text(2) - "Experience thrilling adventures guided by experts."

service(4)_section_part(2)_text(1) - "Nature Photography"
service(4)_section_part(2)_text(2) - "Capture the beauty of nature through your lens."

service(4)_section_part(3)_text(1) - "Camping Expeditions"
service(4)_section_part(3)_text(2) - "Camp under the stars in the most scenic locations."
-END
```
Penjelasan Tipe Format di atas:

1. **Title: SERVICE_4**: Ini merupakan format untuk membuat bagian Service menggunakan template 4.
2. **title_section_content**: Menunjukkan awal dari konten bagian.
3. **service(4)_section_count**: Digunakan untuk menentukan jumlah card.
4. **service(4)_section_title(1)**: Ini digunakan untuk memasukan nama judulnya, apakah akan dikasih nama OUR SERVICES atau yang lainnya pada bagian ini.
5. **service(4)_section_part(1)_text(1)**: Ini digunakan untuk memasukan judul Service pada card 1.
6. **service(4)_section_part(1)_text(2)**: Ini digunakan untuk memasukan deskripsi Service pada card 1.
7. **service(4)_section_part(1)_link(1)**: Ini digunakan untuk memasukan link terkait Service pada card 1. Kenapa card 1, karena disana tertulis **part(1)** yang menandakan bahwa ini adalah bagian dari card 1. begitupun seterusnya untuk **part(2)**, **part(3)**, **part(4)**.
8. **-END**: Menandai akhir dari bagian Informasi, ini wajib dimasukan di setiap bagian manapun lalu jangan lupa di kasih enter setelahnya.


