+++
title = "Service Section"
description = "Step by step guide on how to create a Service section in Lontar Builder"
date = 2023-12-11T18:00:00+00:00
updated=2023-12-11T18:00:00+00:00
draft = false
weight = 10
sort_by = "weight"
template="docs/page.html"

[extra]
lead = 'Learn how to create an Information section in Lontar Builder with various templates that can be used'
toc = true
top = false
+++

## Various service sections in Lontar Builder
First you need to know that in Lontar Builder for the Service section there are several templates. The following are several types of service templates available in Lontar Builder:

### SERVICE_1

<img src="../service1.png" alt="Preview template 1" style="max-width: 100%; margin-bottom: 12px"/>

The image above is an example of a Service 1 template, to create it you can use the command below:

```markdown
Title: SERVICE_1
service(1)_section_content:
service(1)_section_count - "3"
service(1)_section_title(1) - "OUR SERVICES"
service(1)_section_part(1)_text(1) - "Lorem"
service(1)_section_part(1)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed aka nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(1)_section_part(1)_link(1) - "https://target.com/link"
service(1)_section_part(1)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(1)_section_part(2)_text(1) - "Ipsum"
service(1)_section_part(2)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus soluta omnis eos nobis sapiente, vero commodi eaque, repellat nisi aliquam non! Provident nemo tempore quos labore doloremque magnam velit beatae, consequuntur , modi natus distinctio! Cum qui numquam sapiente pariatur non."
service(1)section_part(2)_link(1) - "https://target.com/link"
service(1)_section_part(2)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(1)_section_part(3)_text(1) - "Dolor"
service(1)_section_part(3)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(1)_section_part(3)_link(1) - "https://target.com/link"
service(1)_section_part(3)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"
-END
```
Explanation of the Format Type above:

1. **Title: SERVICE_1**: This is the format for creating a Service section using template 1
2. **title_section_content**: Indicates the beginning of the section content.
3. **service(1)_section_count**: Used to determine the number of cards.
4. **service(1)_section_title(1)**: This is used to enter the name of the title, whether it will be named OUR SERVICES or something else in this section.
5. **service(1)_section_part(1)_text(1)**: This is used to enter the Service title on card 1.
6. **service(1)_section_part(1)_text(2)**: This is used to enter a service description on card 1.
7. **service(1)_section_part(1)_link(1)**: This is used to enter links related to Service on card 1.
8. **service(1)_section_part(1)_image(1)**: This is used to enter the location of the Service image on card 1. Why card 1, because it says **part(1)** which indicates that this is part of card 1. and so on for **part(2)**, **part(3)**, **part(4)**, **part(5)**, **part(6) **.
9. **-END**: Marks the end of the Information section, this must be entered in every section then don't forget to enter enter afterwards.

### SERVICE_2

<img src="../service2.png" alt="Preview template 2" style="max-width: 100%; margin-bottom: 12px"/>

The image above is an example of a Service 2 template, to create it you can use the command below:

```markdown
Title: SERVICE_2
service(2)_section_content:
service(2)_section_count - "6"
service(2)_section_title(1) - "OUR SERVICES"
service(2)_section_part(1)_text(1) - "Lorem"
service(2)_section_part(1)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed aka nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
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
service(2)_section_part(4)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed aka nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(4)_link(1) - "https://target.com/link"
service(2)_section_part(4)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(2)_section_part(5)_text(1) - "Lorem"
service(2)_section_part(5)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed alias nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(5)_link(1) - "https://target.com/link"
service(2)_section_part(5)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"

service(2)_section_part(6)_text(1) - "Lorem"
service(2)_section_part(6)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis sed aka nobis dolore fugiat, eligendi perspiciatis amet dolorem aperiam quidem. Nesciunt, quis, non accusantium ea asperiores corrupti, ipsam neque tenetur laborum cumque eius soluta omnis debitis voluptatibus deleniti libero ipsa."
service(2)_section_part(6)_link(1) - "https://target.com/link"
service(2)_section_part(6)_image(1) - "https://i.pinimg.com/564x/2f/7b/26/2f7b260ee9fbd2165f71e3eed93ab1d1.jpg"
-END
```
Explanation of the Format Type above:

1. **Title: SERVICE_2**: This is the format for creating a Service section using template 1
2. **title_section_content**: Indicates the beginning of the section content.
3. **service(2)_section_count**: Used to determine the number of cards.
4. **service(2)_section_title(1)**: This is used to enter the name of the title, whether it will be named OUR SERVICES or something else in this section.
5. **service(2)_section_part(1)_text(1)**: This is used to enter the Service title on card 1.
6. **service(2)_section_part(1)_text(2)**: This is used to enter a service description on card 1.
7. **service(2)_section_part(1)_link(1)**: This is used to enter links related to Service on card 1.
8. **service(2)_section_part(1)_image(1)**: This is used to enter the location of the Service image on card 1. Why card 1, because it says **part(1)** which indicates that this is part of card 1. and so on for **part(2)**, **part(3)**, **part(4)**, **part(5)**, **part(6) **.
9. **-END**: Marks the end of the Information section, this must be entered in every section then don't forget to enter enter afterwards.

### SERVICE_3

<img src="../service3.png" alt="Preview template 3" style="max-width: 100%; margin-bottom: 12px"/>

The image above is an example of a Service 3 template, to create it you can use the command below:

```markdown
Title: SERVICE_3
service(3)_section_content:
service(3)_section_count - "4"
service(3)_section_title(1) - "OUR SERVICES"
service(3)_section_part(1)_text(1) - "Lorem"
service(3)_section_part(1)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(3)_section_part(1)_link(1) - "https://target.com/link"

service(3)_section_part(2)_text(1) - "Umrah"
service(3)_section_part(2)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(3)_section_part(2)_link(1) - "https://target.com/link"

service(3)_section_part(3)_text(1) - "Umrah"
service(3)_section_part(3)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(3)_section_part(3)_link(1) - "https://target.com/link"

service(3)_section_part(4)_text(1) - "Lorem"
service(3)_section_part(4)_text(2) - "Lorem ipsum dolor sit amet consectetur adipisicing elit. Non velit animi nam nobis est, impedit beatae neque perferendis, iure voluptates consectetur voluptas eaque, autem aliquam aliquid aspernatur voluptatibus dolor. Voluptatem blanditiis incidunt, saepe totam dolores temporibus. Voluptate labore modi recusandae!"
service(3)_section_part(4)_link(1) - "https://target.com/link"
-END
```
Explanation of the Format Type above:

1. **Title: SERVICE_3**: This is the format for creating a Service section using template 3.
2. **title_section_content**: Indicates the beginning of the section content.
3. **service(3)_section_count**: Used to determine the number of cards.
4. **service(3)_section_title(1)**: This is used to enter the name of the title, whether it will be named OUR SERVICES or something else in this section.
5. **service(3)_section_part(1)_text(1)**: This is used to enter the Service title on card 1.
6. **service(3)_section_part(1)_text(2)**: This is used to enter a service description on card 1.
7. **service(3)_section_part(1)_link(1)**: This is used to enter links related to Service on card 1. Why card 1, because it says **part(1)** which indicates that this is part of card 1. and so on for **part(2)**, **part(3)**, **part(4)**.
8. **-END**: Marks the end of the Information section, this must be entered in every section then don't forget to enter enter afterwards.

### SERVICE_4

<img src="../service4.png" alt="Preview template 3" style="max-width: 100%; margin-bottom: 12px"/>

The image above is an example of a Service 4 template, to create it you can use the command below:

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
service(4)_section_part(3)_text(2) - "Camp under the stars in the most scenic location."
-END
```
Explanation of the Format Type above:

1. **Title: SERVICE_4**: This is the format for creating a Service section using template 4.
2. **title_section_content**: Indicates the beginning of the section content.
3. **service(4)_section_count**: Used to determine the number of cards.
4. **service(4)_section_title(1)**: This is used to enter the name of the title, whether it will be named OUR SERVICES or something else in this section.
5. **service(4)_section_part(1)_text(1)**: This is used to enter the Service title on card 1.
6. **service(4)_section_part(1)_text(2)**: This is used to enter the Service description on card 1.
7. **service(4)_section_part(1)_link(1)**: This is used to enter links related to Service on card 1. Why card 1, because it says **part(1)** which indicates that this is part of card 1. and so on for **part(2)**, **part(3)**, **part(4)**.
8. **-END**: Marks the end of the Information section, this must be entered in every section then don't forget to enter enter afterwards.