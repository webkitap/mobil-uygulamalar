<h1 style="color:#ffc034">3.5. İSİMLENDİRME KURALLARI</h1>

Her programlama dilinde uyulması gereken isimlendirme kuralları ve standartları vardır. Kurallara mutlaka uyulması gerekirken standartlara uyulma zorunluluğu yoktur. İsimlendirme kurallarına uyulmadığında derleyici hatası meydana gelir ve uygulama çalışmaz. İsimlendirme standartlarına uyulmadığında herhangi bir hata ile karşılaşılmaz. 

İsimlendirme kuralları şunlardır:
* İsimlerde boşluk kullanılmaz.

* İsimlerde $ ve _ karakterleri dışında özel karakterler kullanılmaz.

* İsimler sayı ile başlamaz.

* İsimler büyük ve küçük harf duyarlıdır. Bir uygulama içinde yer alan "ad" değişkeni ile "Ad"değişkeni farklıdır.

* Ayrılmış anahtar kelimeler (reserved keywords) isim olarak kullanılmaz. İsimlendirmede if,else, int, char gibi programa ait ifadeler ayrılmış anahtar kelimelerdir.

Birçok isimlendirme standardı vardır. Bunlardan üç tanesi Java programlama dilinde sıklıkla kullanılır.

1. **Camel Case (Deve Gösterimi):** Devenin hörgücüne benzetilmesi dolayısıyla böyle bir isim verilmiştir. İlk harf küçük olacak şekilde diğer sözcüklerin ilk harfinin büyük yazılması ile elde edilir. 

<span style="font-weight:bold; padding-top:1px; padding-bottom:1px; padding-left:8px; padding-right:8px; background-color:#FFEEC4;">ÖRNEK</span>


kullanıcıAdıSoyadı, notOrtalaması, büyükKenar

2. **Pascal Case (Paskal Gösterimi):** Camel Case’e benzer. Tüm sözcüklerin ilk harfinin büyük yazılması ile elde edilir.

<span style="font-weight:bold; padding-top:1px; padding-bottom:1px; padding-left:8px; padding-right:8px; background-color:#FFEEC4;">ÖRNEK</span>


KullaniciAdiSoyadi, NotOrtalamasi, BuyukKenar

3. **Screaming Snake Case (Çığlık Atan Yılan Gösterimi):** Bütün harflerin büyük yazıldığı, sözcükler arası boşluk yerine _ kullanıldığı gösterim şeklidir.

<span style="font-weight:bold; padding-top:1px; padding-bottom:1px; padding-left:8px; padding-right:8px; background-color:#FFEEC4;">ÖRNEK</span>


PI_SAYISI, MAAS_KATSAYISI, SAAT_UCRETI

İsimlendirme standartları kodun okunabilirliğini artırmak için getirilmiştir. Java kodları yazılırken kullanılan isimlendirme standartları şunlardır:

- Türkçe karakter (ç, ğ, ı, ö, ş, ü, Ç, Ğ, İ, Ö, Ş, Ü) kullanmaktan kaçınılmalıdır.

- Proje isimleri Pascal Case şeklinde olmalıdır.

- Sınıf isimleri Pascal Case şeklinde olmalıdır.

- Değişken isimleri Camel Case şeklinde olmalıdır.

- Sabitler Screaming Snake Case şeklinde olmalıdır.

- Paket isimleri Pascal Case şeklinde olmalıdır.

- Metot isimleri Camel Case şeklinde olmalıdır.

>**SIRA SİZDE**: 
>
>Tabloda verilen isimlerin karşısına isimlendirme kuralları ve standartlarınagöre isimleri tekrar yazınız.
>
>| İsim                | Türü      | Doğru GösterimI |
>| ------------------- | --------- | --------------- |
>| Öğrenci Adı         | Değişken  |
>| Araba Sınıfı        | Sınıf     |
>| 1. not              | Değişken  |
>| Tahmin Oyunu        | Proje Adı |
>| Geçme Notu          | Sabit     |
>| Kullanıcı İşlemleri | Paket Adı |
>| Puan Hesapla        | Metot Adı |
>
>
>**DEĞERLENDİRME**: 
>
>Çalışmalarınız aşağıda yer alan kontrol listesi kullanılarak değerlendirilecektir.Çalışmanızı yaparken değerlendirme ölçütlerini dikkate alınız.
>
><div style="text-align:center;"><b>KONTROL LİSTESİ</b></div>
>
>| DEĞERLENDİRME ÖLÇÜTLERİ                                                                           | EVET | HAYIR |
>| :------------------------------------------------------------------------------------------------- | ---- | ----- |
>| 1. "Öğrenci Adı" değişkenine isimlendirme kurallarına ve standartlarına uygun isim verdi.         |
>| 2. "Araba Sınıfı" sınıfına isimlendirme kurallarına ve standartlarına uygun isim verdi.           |
>| 3. "1. not" değişkenine isimlendirme kurallarına ve standartlarına uygun isim verdi.              |
>| 4. "Tahmin Oyunu" projesine isimlendirme kurallarına ve standartlarına uygun isim verdi.          |
>| 5. "Geçme Notu" sabitine isimlendirme kurallarına ve standartlarına uygun isim verdi.             |
>| 6. "Kullanıcı İşlemleri" paket adına isimlendirme kurallarına ve standartlarına uygun isim verdi. |
>| 7. "Puan Hesapla" metoduna isimlendirme kurallarına ve standartlarına uygun isim verdi.           |