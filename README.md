# catrhat
Example repository for testing

## Hei Maailma

Linux kurssi

# h1 Virtuaali-Linux
Kone jota käytän sisältää:
gpu -> AMD Radeon rx6900 XT,
cpu -> Intel Core i7 8700K,
ram -> 32gb,
host OS -> windows10


### Lataa Debian ISO image

Lataa se osoitteesta: https://cdimage.debian.org/images/unofficial/non-free/images-including-firmware/current-live/amd64/iso-hybrid/

### Luo uusi virtuaalikone

Nimeä virtuaalikoneesi ja valitse lataamasi iso tiedosto sille varattuun kohtaan.

![1](https://user-images.githubusercontent.com/112497215/212956133-2f978cf4-0ddf-481d-9244-3b476185ce49.PNG)

Täytä käyttäjätunnuksesi ja salasanasi, sekä poista välilyönti Hostname:sta että voit jatkaa seuraavaan kohtaan.

![2](https://user-images.githubusercontent.com/112497215/212956163-53d03580-083f-4be3-8e41-eea87efa0b0d.PNG)

Valitse oman koneen mukaan, suositus 4000mb ja 1CPU

![3](https://user-images.githubusercontent.com/112497215/212956190-386e4d33-362f-4bc4-a00a-82547f45265f.PNG)

Varaa 60GB Virtuaaliseen kovalevyyn.

![4](https://user-images.githubusercontent.com/112497215/212956217-a097e387-d67b-44a0-b731-43ac7840c2f5.PNG)

### Käynnistä luotu virtualikone

![image](https://user-images.githubusercontent.com/112497215/212956816-74192ad1-4aea-4168-b310-cdd948d7ddaa.png)


### Valitse Debian Installer

![image](https://user-images.githubusercontent.com/112497215/212957007-f7d8ad0e-d289-48ed-be68-343d678101a3.png)

Valitse kieli jota haluat käyttää.

![image](https://user-images.githubusercontent.com/112497215/212957235-69c28206-1b69-4c59-a6fa-9dda30a30ddf.png)

Valitse maa.

![image](https://user-images.githubusercontent.com/112497215/212957331-d3dad346-e1ea-4158-84f1-1eab932941cd.png)

Valitse näppäimistön kieli.

![image](https://user-images.githubusercontent.com/112497215/212957466-2a2e319a-a116-4f5b-aad5-436dd2a94567.png)

Valitse Erase disk.

![image](https://user-images.githubusercontent.com/112497215/212957580-535bd1a1-728c-4fb3-9f23-e60f389d83e8.png)

Luo käyttäjätunnus.

![image](https://user-images.githubusercontent.com/112497215/212957671-f9979921-8ec3-406f-a8da-454b842301d3.png)

summa summarum

![image](https://user-images.githubusercontent.com/112497215/212957902-eb3dbb65-7ea7-4559-b27d-5972fa2e6152.png)

### Latauksen jälkeen

suorita seuraavat komennot terminaalissa: sudo apt-get update, sudo apt-get -y dist-upgrade, sudo apt-get -y install ufw, sudo ufw enable

## VALMISTA

