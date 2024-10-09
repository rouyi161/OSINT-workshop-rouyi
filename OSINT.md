 # Project Write-Up: Questions and Answers

This document contains answers to six key questions from the https://tryhackme.com/jr/workshoposint.

## Question 1: RawSEC

**Question:**  
*RawSEC aktif dalam mengedalikan acara CTF di seluruh Malaysia. Mereka telah berjaya mengadakan beberapa siri CTF yang telah berlangsung di Utara, Selantan, Sentral dan juga Pantai Timur. Apakah nama CTF paling terbaru diadakan oleh RawSEC dan di manakah acara itu berlangsung?                                                                                                     Format flag: 3108{namactf_namatempat}*

**Answer:**  
As in the question has mention RawSEC so I go to LInkedln and search about RawSEC and get the flag.  
[![Image Description](https://live.staticflickr.com/65535/54047517603_163cf5f7d9_c.jpg)](https://www.flickr.com/photos/201584002@N06)

**Flag:** 3108{rembulan_UCTATI}


---

## Question 2: Malayan Union

**Question:**  
*KAMI BANTAH! KAMI BANTAH!

Malayan Union perlu dihapuskan! Kami mahu Raja-Raja kami semula! Mesej bergambar ini untuk menyampaikan berita ini kepada pihak atasan!

Format Flag: 3108{nama_tempat}         

https://postimg.cc/7fWKJdsW*

Hint: JOHOR

**Answer:**  
On this question it gives this picture.
![Sejarah Penubuhan UMNO](https://i.postimg.cc/sDfWnRJY/sejarah-penubuhan-umno-5.jpg)

As the hint given is Johor, so I go to ChatGPT and ask about the location of the Malayan Union protest in Johor.
![Image Description](https://i.postimg.cc/x8Z9yHRF/Malayan-Union.png)

**Flag:** 3108{Istana_Besar}

---

## Question 3: Gallery

**Question:**  
*Where am I ? 

Spaces in the gallery name should be replaced with underscores (_). For example, if the gallery is named National Art Gallery, the flag should be written as: CTF{National_Art_Gallery}.

Format Flag: CTF{Gallery_Name}

https://drive.google.com/file/d/1aw66UkDVQWr13KBuShpJriacNxZD0ccp/view?usp=sharing*

**Answer:**  
On this question it give this picture.
![Image Description](https://i.postimg.cc/8cJ2GYRt/IMG20240409135215.jpg)

I used Google to search for this image and found similar images related to Ilham Gallery.
![Image Description](https://i.postimg.cc/6QSsPwRy/gallery.jpg)

**Flag:** CTF{Ilham_Gallery}

---

## Question 4: Gallery2

**Question:**  
*Could you find the model of the camera used to take the image in question?  

This question is a follow-up to the previous one. Please refer to the image provided in Question 3.

For example, if the model is Samsung Galaxy S21, the flag should be written as: CTF{Samsung_Galaxy_S21}.

Format Flag: CTF{Model}*

Hint: Use appropriate tools to identify the camera model from the metadata of the image provided. 

**Answer:**  
Since the hint mentioned that this question is about metadata, I used Exif Pilot as a tool to discover the image's metadata. By viewing the properties and selecting the Exif tab, all the image details were displayed.
![Image Description](https://i.postimg.cc/1XMH3k6D/model.png) 

**Flag:** CTF{OPPO_A76}

---

## Question 5: Gallery3

**Question:**  
*Which date and time was the photo taken? 

This question is a follow-up to the previous one. Please refer to the image provided in Question 3.

Format Flag: CTF{YYYY-MM-DD_HH:MM:SS}

Note: HH is the hour in 24-hour format, MM is minutes, and SS is seconds.*

**Answer:**  
For this question also same, date and time also display in Exif.So, I already get the flag.
![Image Description](https://i.postimg.cc/Xqv5QpGy/datetime.png) 

**Flag:** CTF{2024-04-09_13:52:15}

---

## Question 6: Gallery4

**Question:**  
*Can you find the registration number of the gallery from the image provided in Question 3?  

Flag Format: CTF{Registration-Number}*

**Answer:**  
As we already know that this image is come from Ilham Gallery. So, we just search registration number gallery from social media such as Instagram or Facebook.
![Image Description](https://i.postimg.cc/8cn63NMX/registration-number.jpg)

**Flag:** CTF{1300502-A}

---
