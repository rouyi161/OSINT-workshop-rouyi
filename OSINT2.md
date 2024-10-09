
 # Project Write-Up: Questions and Answers

This document contains answers to five key questions from the https://tryhackme.com/jr/workshoposint2.

## Question 1: Jalan Jalan Desa

**Question:**  
*Syah yang minat akan menggembara telah sampai ke negeri Indera Kayangan. Syah telah meninggalkan satu gambar kepada anda. Gambar tersebut merupakan tempat yang telah Syah lawati sejurus anda membaca ini. Syah juga selalu meninggalkan review sejurus melawat mana2 tempat. Jejak dimana beliau berada !

Gambar: https://postimg.cc/4714PvtM

Format Flag: 3108{}*

**Answer:**  
In this challenge, we got an image of location.
![Image Description](https://i.postimg.cc/76FCxmLx/jejak.png)

After figure out this is Kota Kayang Museum. In the question mention that Syah have give the review so we search certain word "Kota Kayang Museum" and "3108". After that, we get the flag.

![Image Description](https://i.postimg.cc/rpcr9bCv/muzium.jpg)

**Flag:** 3108{Muzium_Bersejarah_Perlis}


---

## Question 2: Tinggi Lagi

**Question:**  
*Bangunan Tertinggi Di Malaysia yang tidak terbina. Tau tak kat mana?

Gambar: https://postimg.cc/8jR4Hjnv

Format Flag: 3108{latitude, longtitude}

Jawapan dalam dua titik perpuluhan*

**Answer:**  
On this question it gives this picture.
![Image Description ](https://i.postimg.cc/65SPBZrM/tinggi.png)

I use Google Image and found out this picture is Tradewind Square Tower. After that, I google latitude and longtitude of Tradewind and get the flag.
![Image Description](https://i.postimg.cc/m2YX2xDn/latitude.png)

**Flag:**3108{3.15, 101.71}

---

## Question 3: LostArt

**Question:**  
*There're a lot of masterpiece lost during war times, find the ID of the art for example: IBOH24{Art-ID}

Image: https://postimg.cc/Lqx2Z4pK

Flag Format: IBOH24{}*

**Answer:**  
On this question I get this picture.
![Image Description](https://i.postimg.cc/qRTRSgDR/Whats-App-Image-2024-09-28-at-22-39-34-2af2fd14.jpg)

After Google Image, I gained the artist and the name of this art.
![Image Description](https://i.postimg.cc/65fcxdbJ/art.jpg)

After that, I go to LostArt Database and try searching the name and artist of this art. Then, I get the flag. 
![Image Description](https://i.postimg.cc/QCR8xbLJ/art-id.png)

**Flag:**IBOH24{583920}

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
