# 3.4. SABİTLER
Sabit, değeri atandıktan sonra değeri değiştirilemeyen bir değişken türüdür. Sabit tanımlandığında atanan değer programın herhangi bir yerinde değiştirilemez, değiştirilmeye çalışıldığında program hata verir. Bir değişken türü olması nedeniyle aynı değişken gibi tanımlanır fakat başına **final** ayrılmış kelimesi (keyword) getirilir (Görsel 3.20).

![Sabit tanımlama söz dizimi](./temel-komutlar/gorsel-3.20-sabit-tanimlama-soz-dizimi.png)

**NOT**

>Sabitlere isim verilirken büyük harfleri kullanmak, Java programcıları arasında bir gelenek hâline gelmiştir. Bu şekilde kullanım zorunlu değildir fakat kodu okuyan herkesin bu değişkenin bir sabit olduğunu anlamasını kolaylaştırır. 

**6. UYGULAMA**: İşlem adımlarına göre sabitin kullanıldığı bir uygulamayı tasarlayınız.

**1. Adım**: “DenemeSabitler” adında yeni bir Java sınıfı tanımlayınız.

**2. Adım**: DenemeSabitler sınıfı içine şu kodu yazınız:

```java
public class DenemeSabitler {
    public static void main(String[] args) {
        final int PI = 3;
        int yariCap = 5;
        System.out.println("Çevre = " + (2*PI*yariCap));
    }
}
```

**3. Adım:** Yazdığınız kodu Run menüsünden Run ‘DenemeSabitler.main()’ with Coverage komutuyla çalıştırınız.

**Ekran Çıktısı**

>Çevre = 30

>**SIRA SİZDE**:
>
>Altıncı uygulamadaki PI sabitini 3.14 olacak şekilde gerekli değişiklikleri yapıp çalıştırınız.
>
>**DEĞERLENDİRME**:
>
>Çalışmanız aşağıda yer alan kontrol listesi kullanılarak değerlendirilecektir. Çalışmanızı yaparken değerlendirme ölçütlerini dikkate alınız.
>
>**KONTROL LİSTESİ**
>
>| DEĞERLENDİRME ÖLÇÜTLERİ                                | EVET | HAYIR |
>| ------------------------------------------------------ | ---- | ----- |
>| 1. New Project komutunu tıkladı.                       |
>| 2. Empty Activity proje türünü seçti.                  |
>| 3. Uygulama adını belirledi.                           |
>| 4. Project penceresinde New Java Class komutunu seçti. |
>| 5. Java sınıfı için hedef klasör seçti.                |
>| 6. Java sınıfına “DenemeSabitler” adını belirledi.     |
>| 7. PI sabitine uygun değişken türünü belirledi.        |
>| 8. PI sabitine 3.14 sayısını atadı.                    |
>| 9. Run with Coverage komutuyla uygulamayı çalıştırdı.  |
>| 10. Cover penceresinde uygulama çıktısını gözlemledi.  |