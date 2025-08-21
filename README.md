# HH-linux-palvelimet

Paul's Haaga Helia Linux palvelimet -course work homepage

<details open>
  <summary>h1</summary>

  ## x) Raportin kirjoittaminen
  - Raportissa selostetaan mitä tehtiin, miksi, ja mitä kunkin vaiheen aikana tapahtui.
  - Helpointa, jos kirjoittaa samalla kun tekee, myös oman muistamisen tueksi.
  - Raportin kuuluu olla sen verran yksityiskohtainen, että se on toisen henkilön toistettavissa.
  - Täsmällinen: mikä komento, kellonaika jos oleellista, onnistuiko, mikä virhe jne.
  - Helppolukuinen: väliotsikoita, huolellista kieltä, vältä kirjoitusvirheitä.
  - Viittaukset käytettyhin lähteisiin, niin että viittaus myös osuu oikeaan kohtaan eikä vain listana lopussa.
  - Kuvankaappaukset osana selostusta!
  
  ## a) Linuxin asentaminen virtuaalikoneeseen

  - Kohdekone: HP ZBook 15 G3 -kannettava
  - Speksit: i7-6820HQ CPU, 16 GB RAM, 477 GB SSD, NVIDIA Quadro M2000M 4 GB
  - Host OS: Windows 10 Pro Version 22H2

  Latasin Linux distroksi juuri julkaistun Debian 13.0.0 Xfce -desktop version osoitteesta https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/debian-live-13.0.0-amd64-xfce.iso.

Tein asennuksen windowsin omaan virtuaaliympäristöön Hyper-V:hen, jonka saa päälle täppäämällä sen Windows Features valikosta:

  <img width="555" height="492" alt="image" src="https://github.com/user-attachments/assets/3f0e6a81-5887-4e7f-bd56-52a376c3d4db" />

  BIOS:ssa virtualisointi olikin jo valmiiksi päällä, koska koneella on aiemmin käytetty Dockeria virtualisointiin.
  
  Käynnistin Hyper-V Manager -ohjelman, ja valitsin Actions -välilehdeltä New -> Virtual Machine, mikä avasi asennusvelhon. 

  Valinnat:
  - Asennus D-asemalle D:\VM
  - Nimeksi Debian13
  - Generation 2
  - Startup memory 4000 MB, Use Dynamic Memory täpätty
  - Connection: Default switch
  - Create New Virtual hard disk: 30 GB, D:\VM\Debian13\Virtual Hard Disks\
  - Install operating system from a bootable image file: debian-live-13.0.0-amd64-xfce.iso

Summary:
    <img width="880" height="666" alt="image" src="https://github.com/user-attachments/assets/3c5a307c-5356-46a4-9426-eff15e3c76cc" />


</details>

<details>
  <summary>h2</summary>
</details>
