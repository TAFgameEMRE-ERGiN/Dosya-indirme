================================================================================
                            TAF OPTIMIZER v2.0
================================================================================

Windows sisteminizi maksimum performansa ulastiran, modern ve guclu 
optimizasyon araci

Gelistirici: Swex/Cinar
GitHub: https://github.com/TAFgameEMRE-ERGiN
Discord: https://discord.gg/tafgame

================================================================================
                              NEDIR?
================================================================================

TAF Optimizer, Windows isletim sistemlerinizi optimize etmek, gereksiz 
servisleri kapatmak ve sistem performansini artirmak icin gelistirilmis 
profesyonel bir aractir. Modern arayuzu, guclu ozellikleri ve kullanim 
kolayligi ile sisteminizdeki gizli performansi ortaya cikarir.


NEDEN TAF OPTIMIZER?

  * Modern Arayuz - Goz alici mavi-gri tema ve akici animasyonlar
  * Tek Tikla Optimizasyon - Karmasik ayarlari basit toggle butonlariyla yonetin
  * Coklu Dil - Turkce ve Ingilizce tam destek
  * Gercek Zamanli Izleme - CPU, RAM kullanimini anlik takip edin
  * Guvenli - Tum degisiklikler geri alinabilir
  * Oyuncu Dostu - Oyun performansini artiran ozel modlar


================================================================================
                            OZELLIKLER
================================================================================

SISTEM OPTIMIZASYONU
--------------------
  - Menu gecikmelerini kaldirma
  - Fare hover efektlerini kapatma
  - Aero Shake devre disi
  - Baslangic optimizasyonu
  - Onbellek temizleme
  - Cortana kapatma

SERVIS YONETIMI
---------------
  - Windows Update kontrolu
  - Windows Search yonetimi
  - Superfetch optimizasyonu
  - Print Spooler yonetimi
  - Windows Defender ayarlari
  - Telemetri servisleri

GIZLILIK KORUMASI
-----------------
  - Telemetri kapatma
  - Konum takibi engelleme
  - Reklam ID'si kapatma
  - Etkinlik gecmisi silme
  - Geri bildirim kapatma
  - Tanilama verilerini durdurma

SISTEM TEMIZLIGI
----------------
  - Gecici dosyalar
  - Geri donusum kutusu
  - Prefetch temizleme
  - DNS onbellegi
  - Olay gunlukleri
  - Kucuk resim onbellegi

AG OPTIMIZASYONU
----------------
  - TCP optimizasyonu
  - Nagle algoritmasi kapatma
  - MTU boyutu ayarlama
  - QoS yonetimi
  - DNS optimizasyonu
  - Winsock sifirlama

OYUN MODU
---------
  - Gorsel efektleri kapatma
  - Yuksek performans modu
  - Hazirda bekletme kapatma
  - Hizli baslatma devre disi
  - SSD optimizasyonu
  - Windows Oyun Modu

EK OZELLIKLER
-------------
  - Sistem Bilgisi: Islemci, RAM, GPU, disk detaylari
  - Onarim Araclari: SFC, DISM, disk kontrolu, ag sifirlama
  - Guvenlik Ayarlari: Firewall, SmartScreen, gercek zamanli koruma
  - Bildirim Yonetimi: Tum Windows bildirimlerini kontrol edin


================================================================================
                              KURULUM
================================================================================

YONTEM 1: HAZIR EXE (ONERILEN)
-------------------------------
1. Releases sayfasindan son surumu indirin
2. TAFOptimizer.exe dosyasini calistirin
3. Kurulum gerektirmez! Tasinabilir ve kullanima hazir


YONTEM 2: KAYNAK KODDAN
------------------------
1. Repository'yi klonlayin:
   git clone https://github.com/TAFgameEMRE-ERGiN/TAF-Optimizer.git

2. Gerekli paketleri yukleyin:
   pip install -r requirements.txt

3. Programi calistirin:
   python swextools.py


YONTEM 3: KENDINIZ DERLEYIN
----------------------------
PyInstaller ile EXE olusturun:
   python -m PyInstaller SwexTools.spec

Olusan dosya: dist/TAFOptimizer.exe


================================================================================
                              KULLANIM
================================================================================

BASLANGIC
---------
1. TAFOptimizer.exe dosyasini calistirin
2. Modern arayuz karsinizda belirecek
3. Sol menuден kategori secin
4. Toggle butonlariyla ozellikleri aktif/pasif yapin


IPUCLARI
--------
  * Kirmizi Toggle: Ozellik kapali
  * Yesil Toggle: Ozellik acik
  * Gercek Zamanli: CPU/RAM kullanimi surekli guncellenir
  * Dil Degistirme: Sag ustteki TR/EN butonuna tiklayin
  * Sistem Bilgisi: Donanim detaylarini goruntuyleyin


ONEMLI UYARILAR
---------------
  ! Yonetici Yetkisi: Bazi islemler icin gereklidir
    (sag tik -> Yonetici olarak calistir)

  ! Yedekleme: Sistem degisiklikleri yapmadan once geri yukleme 
    noktasi olusturun

  ! Yeniden Baslatma: Bazi degisiklikler icin sistem yeniden 
    baslatilmalidir


================================================================================
                        SISTEM GEREKSINIMLERI
================================================================================

MINIMUM
-------
  - Isletim Sistemi: Windows 10
  - RAM: 2 GB
  - Disk Alani: 50 MB
  - Islemci: Dual Core
  - Ekran Cozunurlugu: 1280x720

ONERILEN
--------
  - Isletim Sistemi: Windows 11
  - RAM: 4 GB+
  - Disk Alani: 100 MB
  - Islemci: Quad Core+
  - Ekran Cozunurlugu: 1920x1080+


PYTHON GEREKSINIMLERI (Kaynak Kod)
-----------------------------------
  - Python 3.8+
  - tkinter (genellikle Python ile gelir)
  - psutil >= 5.9.0
  - GPUtil >= 1.4.0 (opsiyonel, GPU bilgisi icin)


================================================================================
                          TEKNIK DETAYLAR
================================================================================

MIMARI
------
TAF Optimizer
  |
  +-- GUI Layer (Tkinter)
  |     +-- Modern UI Components
  |     +-- Animation Engine
  |     +-- Real-time Monitoring
  |
  +-- System Layer (psutil)
  |     +-- CPU/RAM Monitoring
  |     +-- Process Management
  |     +-- System Information
  |
  +-- Registry Layer (Windows API)
  |     +-- Registry Modifications
  |     +-- Service Management
  |     +-- System Configuration
  |
  +-- Optimization Layer
        +-- Performance Tweaks
        +-- Privacy Settings
        +-- Network Optimization


DOSYA YAPISI
------------
TAF-Optimizer/
  |
  +-- swextools.py          # Ana program
  +-- SwexTools.spec        # PyInstaller config
  +-- taf.ico              # Program ikonu
  +-- requirements.txt      # Python bagimliliklari
  +-- guard.py             # Koruma modulu
  +-- README.txt           # Bu dosya
  +-- dist/
        +-- TAFOptimizer.exe # Derlenmis program


================================================================================
                        KATKIDA BULUNMA
================================================================================

Katkilarinizi bekliyoruz!

1. Fork edin
2. Branch olusturun (git checkout -b feature/harika-ozellik)
3. Commit yapin (git commit -m 'Harika ozellik eklendi')
4. Push edin (git push origin feature/harika-ozellik)
5. Pull Request acin


KATKI ALANLARI
--------------
  - Hata duzeltmeleri
  - Yeni ozellikler
  - Dokumantasyon iyilestirmeleri
  - Yeni dil cevirileri
  - Arayuz gelistirmeleri


================================================================================
                              LISANS
================================================================================

Bu proje MIT Lisansi altinda lisanslanmistir.

MIT License

Copyright (c) 2026 Swex/Cinar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.


================================================================================
                            GELISTIRICI
================================================================================

                              Swex/Cinar

              Windows optimizasyonu ve sistem araclari konusunda uzman

  GitHub: https://github.com/TAFgameEMRE-ERGiN
  Discord: https://discord.gg/tafgame


================================================================================
                            TESEKKURLER
================================================================================

  * TAF Game Toplulugu - Surekli destek ve geri bildirimler icin
  * Katkida Bulunanlar - Projeyi gelistiren herkese
  * Acik Kaynak Toplulugu - Ilham veren projeler icin


================================================================================
                        DESTEK & ILETISIM
================================================================================

Sorulariniz mi var? Yardima mi ihtiyaciniz var?

  Discord: https://discord.gg/tafgame
  Bug Report: https://github.com/TAFgameEMRE-ERGiN/issues
  Email: Destek icin Discord'dan ulasin


================================================================================
                          SURUM GECMISI
================================================================================

v2.0 - MAVI FIRTINA (2026)
---------------------------
  * Tamamen yenilenen mavi-gri tema
  * Gelismis animasyonlar ve efektler
  * Turkce/Ingilizce dil destegi
  * Gercek zamanli CPU/RAM izleme
  * Oyun modu ve performans optimizasyonlari
  * 50+ yeni optimizasyon secenegi
  * %40 daha hizli baslangic
  * Daha dusuk bellek kullanimi

v1.0 - ILK SURUM
----------------
  * Ilk kararli surum
  * Temel optimizasyon ozellikleri
  * Gizlilik ayarlari
  * Sistem temizleme araclari


================================================================================
                            YOL HARITASI
================================================================================

YAKINDA GELECEK OZELLIKLER
---------------------------
  [ ] Karanlik/Aydinlik tema secenegi
  [ ] Otomatik guncelleme sistemi
  [ ] Profil sistemi (farkli optimizasyon profilleri)
  [ ] Detayli performans grafikleri
  [ ] Ozellestirilebilir renkler
  [ ] Daha fazla dil destegi
  [ ] Yedekleme/Geri yukleme sistemi
  [ ] Yapay zeka destekli optimizasyon onerileri


================================================================================

              TAF OPTIMIZER ILE SISTEMINIZI GUCLENDIRIN!

                    Made with <3 by Swex/Cinar

================================================================================
