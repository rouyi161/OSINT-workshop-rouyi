
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

## Question 4: RyoikiTenkai

**Question:**  
*Which train lines am I part of? Example: "Hakozaki Line, Meijō Line, and Sennichimae Line" will be IBOH24{HakozakiLine_MeijōLine_SennichimaeLine}

Image: https://postimg.cc/sBWSmLT2

Flag Format: IBOH24{}*

**Answer:**  
I get this image on this question 
![Image Description](https://i.postimg.cc/fb2KznXY/Whats-App-Image-2024-09-28-at-22-39-35-88945beb.jpg) 

After figure out, this is about Kitakami Station
![Image Description](https://i.postimg.cc/cHxMXRbh/station.jpg)

After that, I navigate to wikipedia page and it show the line of statiion and I combine these three lines become flag.
![Image Description](https://i.postimg.cc/hPW8YR6h/line.png)

**Flag:**  IBOH24{TōhokuShinkansen_TōhokuMainLine_KitakamiLine}

---

## Question 5: Airport

**Question:**  
*I am an airport, can you find my name?

Example: "Kuala Lumpur International Airport" will be IBOH24{Kuala_Lumpur_International_Airport}

Image: https://postimg.cc/ppKwNVyQ

Flag Format: IBOH24{}*

**Answer:**  
On this question, I get this image
![Image Description](https://i.postimg.cc/QxzhTH3z/Whats-App-Image-2024-10-05-at-15-12-14-86750d8a.jpg)

I use Google Image and figure out it is Haneda Airport from Reddit and I get the flag.
![Image Description](https://i.postimg.cc/jjKFYJ1w/airport.jpg)

**Flag:** IBOH24{Haneda_Airport} 

---
