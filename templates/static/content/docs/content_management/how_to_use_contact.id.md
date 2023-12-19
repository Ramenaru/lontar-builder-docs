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

### KONTAK_1

<img src="../contact1.png" alt="Preview Contact 1" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Kontak 1, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Title: CONTACT_1
contact(1)_section_content:
contact(1)_section_title(1) - "OUR CONTACT"
contact(1)_section_text(1) - "Address"
contact(1)_section_text(2) - "Lorem ipsum dolor sit amet consectetur elit.Dignissimos corrupti nihil commodi
dolorum iste pariatur repudiandae quaerat."
contact(1)_section_text(3) - "Email"
contact(1)_section_text(4) - "info@example.co.id"
contact(1)_section_text(5) - "Phone"
contact(1)_section_text(6) - "+123 456 789"
-END
```

Penjelasan dari Tipe Format di atas:

1. **Title: Contact_1**: Ini adalah format untuk membuat bagian kontak menggunakan templat 1.
2. **title_section_content**: Menunjukkan awal konten bagian.
3. **contact(1)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Kontak atau nama lain di bagian ini.
4. **contact(1)_section_text(1-6)**: Ini adalah teks yang akan mengisi bagian kontak.
5. **-END**: Menandai akhir dari bagian kontak, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.

### KONTAK_2

<img src="../contact2.png" alt="Preview Contact 2" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Kontak 2, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Title: CONTACT_2
contact(2)_section_content:
contact(2)_section_title(1) - "OUR CONTACT"
contact(2)_section_text(1) - "Address"
contact(2)_section_text(2) - "Lorem ipsum dolor sit amet consectetur elit.Dignissimos corrupti nihil commodi
dolorum 2ste pariatur repudiandae quaerat."
contact(2)_section_text(3) - "Email"
contact(2)_section_text(4) - "info@example.co.id"
contact(2)_section_text(5) - "Phone"
contact(2)_section_text(6) - "+123 456 789"
-END
```

Penjelasan dari Tipe Format di atas:

1. **Title: Contact_2**: Ini adalah format untuk membuat bagian kontak menggunakan templat 2.
2. **title_section_content**: Menunjukkan awal konten bagian.
3. **contact(2)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Kontak atau nama lain di bagian ini.
4. **contact(2)_section_text(1-6)**: Ini adalah teks yang akan mengisi bagian kontak.
5. **-END**: Menandai akhir dari bagian kontak, ini harus dimasukkan di setiap bagian lalu jangan lupa untuk memasukkan setelahnya.

### KONTAK_3

<img src="../contact3.png" alt="Preview Contact 3" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh template Contact 3, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Title: CONTACT_3
contact(3)_section_content:
contact(3)_section_title(1) - "OUR CONTACT"
contact(3)_section_text(1) - "General Inquiries"
contact(3)_section_text(2) - "For general questions and information"
contact(3)_section_text(3) - "Email: info@yourcompany.com"
contact(3)_section_text(4) - "Phone: +1 (123) 456-7890"
contact(3)_section_text(5) - "Partnership Opportunities"
contact(3)_section_text(6) - "Interested in becoming our partner?"
contact(3)_section_text(7) - "Email: partnerships@yourcompany.com"
contact(3)_section_text(8) - "Phone: +1 (234) 567-8901"
-END
```

Penjelasan mengenai Tipe Format di atas:

1. **Title: Contact_3**: Ini adalah format untuk membuat bagian kontak menggunakan templat 3.
2. **title_section_content**: Menunjukkan awal konten bagian.
3. **contact(3)_section_title(1)**: Ini digunakan untuk memasukkan nama judul, apakah akan diberi nama Kontak atau nama lain di bagian ini.
4. **contact(3)_section_text(1-8)**: Ini adalah teks yang akan mengisi bagian kontak.
5. **-END**: Menandai akhir dari bagian kontak, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.


### KONTAK_4

<img src="../contact4.png" alt="Preview Contact 4" style="max-width: 100%; margin-bottom: 12px"/>

Gambar di atas adalah contoh dari template Contact 4, untuk membuatnya Anda dapat menggunakan perintah di bawah ini:

```markdown
Copy code
Title: CONTACT_4
contact(4)_section_content:
contact(4)_section_title(1) - "Connect with Us"
contact(4)_section_text(1) - "Ready to start your next adventure with us? Contact us now!"
contact(4)_section_text(2) - "Contact Now"
-END
```

Penjelasan Tipe Format di atas:

1. **Title: Contact_4**: Ini adalah format untuk membuat bagian kontak menggunakan templat 4.
2. **title_section_content**: Menunjukkan awal konten bagian.
3. **contact(4)_section_title(1)**: Ini digunakan untuk memasukkan 4.nama judul, apakah akan diberi nama Kontak atau nama lain dibagian ini.
4. **contact(4)_section_text(1-2)**: Ini adalah teks yang akan mengisi bagian kontak.
5. **-END**: Menandai akhir dari bagian kontak, ini harus dimasukkan di setiap bagian kemudian jangan lupa untuk memasukkan setelahnya.