#  Hazırlayan: Hüseyin UZUNYAYLA / OgnitorenKs
###  İletişim;
-   Discord: https://discord.gg/7hbzSGTYeZ
-   Mail: ognitorenks@gmail.com
-   Site: [https://ognitorenks.blospot.com](https://ognitorenks.blospot.com)


<details><summary><B> Versiyon 4.5 ► 19.06.2025 </B></summary>

    • Menüdeki 7,8,9,10 numaralı işlemler 6 ve 14 numaralı işlemler ile alakalı olduğundan gizli hale getirildi. İşlem yapmak için öncelikle mount tanımlaması yapmak gerekiyor. Bunun için Menü üst bölümüne bilgi notları eklendi.
    • EasyDism açılışındaki sistemdeki mount dizinlerinin hepsini remount etme işlemi iptal edildi. Seçilen mount dizinine özel remout işlemi eklendi.
    • "Mount yol tanımla" bölümündeki imaj bilgi bölümü düzenlendi.
    • Dil dosyasına eklenenler; "Y0031", "Y0032", "Y0033"
    • Dil dosyasında değiştirilenler; "Y0016"
    • "Format sonrası ilk açılışa script ekle" bölümünde düzenlemeler yapıldı. 
        • Renklendirme komutlarındaki hatalar giderildi.
        • Katılımsız programlar için ayrı bir klasör dizini oluşturuldu. [Setup\Unattended]
        • Sessiz kurulum parametreleriyle kurulumu sağlanan programlar için ayrı bir klasör oluşturuldu. [Setup\Normal]
        • Masaüstüne çıkartılan dosya ve klasör isimlerinde Türkçe harflerin bozulmaması için çalışmaya 7-Zip eklendi.
    
    
</details><details><summary><B> Versiyon 4.4 ► 08.05.2025 </B></summary>

    • Menü teması düzenlendi.

</details><details><summary><B> Versiyon 4.3 ► 02.05.2025 </B></summary>

    • NSudo hatası giderildi.

</details><details><summary><B> Versiyon 4.2 ► 19.06.2024 </B></summary>

    • İmaj mount işlemi sonrası test için ekleyip unuttuğum 'pause' komutu kaldırıldı.
    • "Format sonrası ilk açılışa batch script ekle" bölümündeki tüm hatalar giderildi. Sorunsuz bir şekilde çalışması sağlandı.

</details><details><summary><B> Versiyon 4.1 ► 25.05.2024</B></summary>

    • "OgnitorenKs_Reader" başlığında nizami görüntü için kodlar düzenlendi.
    • "Hepsi bir arada Windows Hazırla [AIO]" bölümüne farklı mimari sürümlerin x86 üzerinde birleştirilmesiyle ilgili uyarı mesajı eklendi.
        • Ayrıca tüm sürümlerin görüntülenmesi için Ana sürüm imajında "Sources" klasöründe "ei.cfg" dosyası eklemesi için yeni kodlar eklendi.
    • Komut ekranı başlığına programın sürüm bilgisi eklendi.
    • Dil dosyasında bazı düzenlemeler yapıldı.
    • "Format sonrası batch script ekle" bölümünde mount kontrol komutu eklendi.

</details><details><summary><B> Versiyon 4.0 ► 23.05.2024</B></summary>

    • Genel olarak bazı kodlar revize edildi.
    • Dosya konumunu belirten 'L' değişkeni 'Konum' olarak düzenlendi.
    • Regedit dönüştürme kodlarında yer alan hatalar giderildi.
    • "Modelong2" başlığı tek bir bölümde kullandıldığı için ilgili bölüme alınıp başlık iptal edildi.
    • install.wim/esd dosya yolu kontrol bölümünde ESD için yapılan kontrollerde komutlara ekleme yapıldı.
    • Hata mesajlarını göstermesi için oluşturduğum 'LE' başlığı 'Error_Window' olarak değiştirildi.
    • 'Mount_Check' ve 'Mount_Check2' başlıkları birleştirildi. Bağlı kodlar revize edildi.
    • Dil kodları revize edildi. Eski sisteme ait dil kodları kaldırıldı.
    • Regedit entegrasyonu bölümünde bazı dönüştürme eksiklikleri giderildi.
    • 'Windows Setup düzenle' bölümü eklendi.
        • Lerup lauch bar ve programların hızlıca eklenmesi. İlk kurulumda dosyayı internetten indirir.
        • Windows 11 eski donanım engellemesini kaldırmak için bypass kayıtlarını entegre eder.
        • VMD sürücüleri ekler. İlk kurulumda dosyayı internetten indirir.
        • Setup özelleştirmesiyle alakalı dosyaları değiştirir. 3 adet dosya ile sınırlandırılmıştır.
    • Regedit ekleme bölümü için özel başlıklar oluşturuldu.
    
</details>