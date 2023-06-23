<h1 style="color:#cd2d98;">1.2. EMÜLATÖR KURULUMU</h1>

Farklı işletim sistemine ait programları yerel işletim sisteminde çalıştırmak için aracı yazılımlara ihtiyaç duyulur. Bu aracı yazılımlara emülatör ismi verilir. Android Studio içinde mobil işletim sistemine uygun emülatör programı kurulabilir. Geliştirilen uygulamalar bu emülatörde test edilebilir.

Kurulumdan sonra Android Studio çalıştırıldığında karşılama ekranında **More Actions (Ek Eylemler)** listesindeki **Virtual Device Manager (Sanal Cihaz Yöneticisi)** seçeneği tıklanır (Görsel 1.13).

<div style="display:block;text-align:center">

![Virtual Device Manager seçimi](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.13-virtual-device-manager-secimi.png)
</div>


Açılan **Device Manager (Cihaz Yöneticisi)** penceresindeki **Create device (Cihaz oluştur)** düğmesine tıklanır (Görsel 1.14). 
<div style="display:block;text-align:center">

![Create device düğmesi](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.14-create-device-dugmesi.png)
</div>


**Select Hardware (Donanım Seç)** penceresi açılır. Bu pencerede **Category (Kategori)** kısmında TV, Phone (Cep telefonu), Wear OS (Giyilebilir cihazlar), Tablet ve Automotive (Otomotiv tabletleri) yer alır. Uygulamanın çalıştırılacağı cihaz hangi kategorideyse o kategori seçilerek uygun ekran büyüklüğü ve çözünürlük belirlenir. Görsel 1.15’te 480 piksel genişliğinde, 854 piksel uzunluğunda ve 5.4 inch ekran büyüklüğüne sahip bir cep telefonu cihazı seçilmiştir. İhtiyaç duyulması hâlinde **New Hardware Profile (Yeni Donanım Profili)** düğmesiyle boyut ve çözünürlüğünü kullanıcının ayarlayabileceği bir cihaz oluşturulabilir. **Import Hardware Profiles (Donanım Profili İçe Aktar)** düğmesiyle daha önceden dosyaya kaydedilmiş bir donanım profili yüklenebilir. **Clone Device (Cihazı Kopyala)** düğmesi kullanılarak da belirli bir cihazın özellikleri kopyalanır. Kopyalanan cihazın birkaç özelliğinde değişiklik yapılabilir. Next düğmesi tıklanarak bir sonraki pencereye geçilir.
<div style="display:block;text-align:center">

![Emülatör cihazının seçimi](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.15-emulator-cihazinin-secimi.png)
</div>


**Select a system image (Sistem imajı seçimi)** penceresinde emülatör cihazına bir işletim sistemi seçilir. Pencerenin üstünde **Recommended (Tavsiye edilen)**, **x86 Images (x86 İşlemciler için imajlar)** ve **Other Images (Diğer imajlar)** olmak üzere üç adet sekme yer alır.

- **Recommended**: Bu sekme seçiliyken en hızlı çalışacak işletim sistemi imajı kullanıcıya görüntülenir.
- **x86 Images**: x86 işlemcilerde çalışacak işletim sistemi imajları görüntülenir. 32 bitlik işlemciler için listede x86 olarak belirtilmişken 64 bitlik işlemciler için x86_64 olarak işletim sistemleri belirtilmiştir.
- **Other Images**: Diğer işlemcilerde çalışacak işletim sistemi imajları görüntülenir

<span style="color:#f00;font-weight:bold">UYARI:</span> Her Android işletim sistemi sürümü için tek bir API düzeyi belirlenmiştir. Application Programming Interface (Uygulama Programlama Arayüzü) kelimelerinin baş harfleriyle API isimlendirilmesi yapılır. API, yazılımların kendi aralarında iletişim kurmasını sağlayan bir yapıdır. API düzeyi düştükçe yazılan uygulamanın çalışacağı cihaz sayısı artar ancak uygulamada kullanılacak özellikler azalır. API düzeyi yükseldikçe uygulamada kullanılacak özellikler artar ancak kapsadığı cihaz sayısı azalır.

Recommended sekmesindeki Android işletim sistemlerinin isimlerinin hemen yanında Download düğmesi yer alır. Bu düğmeyle o işletim sisteminin imajı indirilir ve işletim sistemi seçime hazır hâle getirilir. Görsel 1.16 penceresinde Marshmallow (Android 6.0) işletim sistemi indirilmiş ve seçime hazır hâle getirilmiştir. Bu sürüm seçilir ve Next düğmesine tıklanır.

<div style="display:block;text-align:center">

![Sanal cihaza işletim sistemi seçimi](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.16-sanal-cihaza-isletim-sistemi-secimi.png)
</div>


Kurulumun son penceresinde oluşturulan ayarların doğruluğu kontrol edilebilir ve bu pencereden ayarlar değiştirilebilir (Görsel 1.17).

- **AVD Name (AVD İsmi)**: Ayarlanan cihazın ismi bu kutuya yeni değer girilerek değiştirilebilir.
- **5.4” FWVGA 5.4 480x854 mdpi**: Bu yazının sağ tarafında yer alan **Change… (Değiştir)** düğmesi ile ekran boyutları farklı bir cihaz seçilebilir.
- **Marshmallow Android 6.0 x86**: Bu yazının sağ tarafında yer alan **Change…** düğmesi ile seçilen işletim sistemi değiştirilebilir.

- **Startup Orientation (Başlangıç Yönlendirmesi)**: Bu bölümde yar alan iki farklı **Portrait (Portre) ve Landscape (Manzara)** simgelerinden biri seçilerek cihazın dikey ve yatay kullanılacağı belirlenebilir. Dikey kullanım için Portrait simgesi seçilir, yatay kullanım içinse Landscape simgesi seçilir.
- **Emulated Performance (Emülasyon Performansı)**: Bu yazının sağ tarafındaki **Graphics: (Grafikler)** açılır kutusunda üç seçenek yer alır. **Automatic (Otomatik), Hardware (Donanım)** ve **Software (Yazılım)** isimli seçeneklerden bilgisayarın grafik kartı kullanılacaksa emülasyon için Hardware seçilir. Grafik kartıyla problemler yaşanırsa ve grafik kartı yerine yazılım kullanılacaksa emülasyon için Software seçilir. Emülasyonun duruma göre otomatik olması istenirse Automatic seçilebilir.
- **Device Frame (Cihaz Çerçevesi)**: Bu onay kutusu işaretlenerek sanal cihazın kenarında çeşitli işlev düğmeleri kullanılabilir hâle getirilir. Bu düğmeler istenmezse bu onay kutusu
işaretlenmez.
- **Show Advanced Settings (Gelişmiş Ayarları Göster)**: Sanal cihazla ilgili ayrıntılı ayarlar yapılması gerektiğinde bu düğme tıklanır. Bu düğme tıklandıktan sonra cihaz ön ve arka kamera ayarları, ana bellek miktarı, yardımcı depolama bellek miktarı, SD kart bellek miktarı, cihazın işlemci sayısı gibi ayrıntılı ayarların belirlenebileceği kutular pencerede belirir. 
<div style="display:block;text-align:center">

![Ayarları doğrulama penceresi](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.17-ayarlari-dogrulama-penceresi.png)
</div>


Finish düğmesine tıklandıktan sonra pencerenin ortasında **Creating Android Virtual Device (Android Sanal Cihaz Oluşturuluyor)** ifadesi görüntülenir (Görsel 1.18).
<div style="display:block;text-align:center">

![Sanal cihaz oluşturuluyor bilgisi](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.18-sanal-cihaz-olusturuluyor-bilgisi.png)
</div>

Sanal cihaz oluşturulduktan sonra pencerenin en üstünde Görsel 1.19’daki bilgiler ve simgeler görünür.
<div style="display:block;text-align:center">

![Sanal cihaz bilgileri](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.19-sanal-cihaz-bilgileri.png)
</div>


Bu bilgilerde sanal cihazın ismi, sanal cihazda yüklü olan işletim sistemi, API düzeyi, yardımcı depolama biriminde kapladığı alan ve Actions (Eylemler) simgeleri yer alır. Bu simgeler şunlardır:


<table>
<thead>
  <tr>
    <th></th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="margin:0px;padding:0px;"><img src="./mobil-uygulama-gelistirmeye-hazirlik/launch-this-avd-in-the-emulator.png" alt="Launch this AVD in the emulator"></td>
    <td><span style="font-weight:bold">Launch this AVD in the emulator (Bu Android Sanal Cihazı emülatörde çalıştır)</span>: Bu simge tıklanarak sanal cihaz çalıştırılır.</td>
  </tr>
</tbody>
</table>

<table>
<thead>
  <tr>
    <th></th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="margin:0px;padding:0px;"><img src="./mobil-uygulama-gelistirmeye-hazirlik/edit-this-avd.png" alt="Edit this AVD"></td>
    <td><span style="font-weight:bold">Edit this AVD (Bu Android Sanal Cihazı düzenle)</span>: Sanal cihazla ilgili değişiklik yapılması gerekirse bu simge tıklanır.</td>
  </tr>
</tbody>
</table>

<table>
<thead>
  <tr>
    <th></th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="margin:0px;padding:0px;"><img src="./mobil-uygulama-gelistirmeye-hazirlik/acilir-menu.png" alt="Açılır menu"></td>
    <td><span style="font-weight:bold">Edit this AVD (Bu Android Sanal Cihazı düzenle)</span>Bu simge tıklandığında açılır bir menü ile karşılaşılır (Görsel 1.20). Bu menüdeki seçenekler şunlardır: </td>
  </tr>
</tbody>
</table>

<div style="display:block;text-align:center">

![Açılır menü seçenekleri](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.20-acilir-menu-secenekleri.png)
</div>

- **Duplicate (Çoğaltma)**: Sanal cihazın özelliklerine sahip ikinci bir kopya oluşturmak için kullanılır.
  
- **Wipe Data (Verileri Sil)**: Sanal cihazı fabrika ayarlarına döndürmek için kullanılır. Sonradan düzenlenen verileri siler ve cihazı ilk açılış durumuna getirir.

- **Cold Boot Now (Soğuk Önyükleme Şimdi)**: Sanal cihazın herhangi bir kaydedilmiş durumdan değil, en baştan açılmasını sağlar.

- **Show on Disk (Disk Üzerinde Göster)**: Sanal cihazın dosyalarını bulunduğu klasörde gösterir.

- **Delete (Sil)**: Sanal cihazın silinmesini sağlar.



Emülatörde sanal cihazı başlatmak için <img src="./mobil-uygulama-gelistirmeye-hazirlik/launch-this-avd-in-the-emulator.png" width="30px" height="30px" alt="Launch this AVD in the emulator"> simgesine tıklanır. Her şey doğru ayarlandıysa Android işletim sistemi yüklü bir cep telefonu cihaz penceresi ekranda belirir (Görsel 1.21).

<div style="display:block;text-align:center">

![Sanal cihaz ve cihazın sağ yanında çerçeve işlev düğmeleri](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.21-sanal-cihaz-ve-cihazin-sag-yaninda-cerceve-islev-dugmeleri.png)
</div>


**1. UYGULAMA**: İşlem adımlarına göre mobil uygulama geliştirme ortamında 5.1 inch büyüklüğünde Android 6.0 işletim sistemi kullanan bir emülatör kurulumunu yapınız.

**1. Adım**: Mobil uygulama geliştirme programını çalıştırınız.\
**2. Adım**: Karşılama ekranında More Actions seçeneğine tıklayınız.\
**3. Adım**: Açılan listeden Virtual Device Manager seçeneğine tıklayınız.\
**4. Adım**: Yeni gelen pencerede Create device düğmesine tıklayınız.\
**5. Adım**: Select Hardware penceresinde Category kısmından Phone ve 5.1”WVGA seçiniz (Görsel 1.22).
<div style="display:block;text-align:center">

![Emülatör seçimi](./mobil-uygulama-gelistirmeye-hazirlik/gorsel-1.22-emulator-secimi.png)
</div>


**6. Adım**: Next düğmesini tıklayınız.\
**7. Adım**: Select a system image penceresinde Marshmallow seçiniz.\
**8. Adım**: Next düğmesini tıklayınız.\
**9. Adım**: Verify Configuration penceresinde Finish düğmesine tıklayınız.\

>**SIRA SİZDE**: 
>
>Mobil uygulama geliştirme ortamında 6.7 inch büyüklüğünde Android 6.0 işletim sistemi kullanan bir emülatör kurulumunu yapınız.
>
>**DEĞERLENDİRME**: 
>
>Çalışmanız aşağıda yer alan kontrol listesi kullanılarak değerlendirilecektir. Çalışmanızı yaparken değerlendirme ölçütlerini dikkate alınız.
>
><div style="text-align:center;"><b>KONTROL LİSTESİ</b></div>
>
>| DEĞERLENDİRME ÖLÇÜLERİ                                                             | EVET | HAYIR |
>| :--------------------------------------------------------------------------------- | ---- | ----- |
>| 1. Mobil uygulama geliştirme ortamını çalıştırdı.                                  |
>| 2. Karşılama ekranında More Actions seçeneğine tıkladı.                            |
>| 3. Açılan listeden Virtual Device Manager seçeneğine tıkladı.                      |
>| 4. Yeni gelen pencerede Create device düğmesine tıkladı.                           |
>| 5. Select Hardware penceresinde Category kısmından Phone ve 6.7” Horizantal seçti. |
>| 6. Next düğmesine tıkladı.                                                         |
>| 7. Select a system image penceresinde Marshmallow seçti.                           |
>| 8. Next düğmesine tıkladı.                                                         |
>| 9. Verify Configuration penceresinde Finish düğmesine tıkladı.                     |