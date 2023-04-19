# 3.6. OPERATÖRLER
Java dilinde kullanılan operatörlerin bazıları şunlardır:

- Aritmetik operatörler
- Atama operatörleri
- Karşılaştırma operatörleri
- Mantıksal operatörler

## 3.6.1. Aritmetik Operatörler
Aritmetik operatörler, matematiksel işlemleri gerçekleştirmek için kullanılır (Tablo 3.3).

**Tablo 3.3: Aritmetik Operatörler**

| Operatör | İsim     | Açıklama                                            | Örnek |
| -------- | -------- | --------------------------------------------------- | ----- |
| +        | Toplama  | İki değeri toplar.                                  | x + y |
| -        | Çıkarma  | Bir değeri diğerinden çıkarır.                      | x - y |
| *        | Çarpma   | İki değeri çarpar.                                  | x * y |
| /        | Bölme    | Bir değeri diğer değer böler.                       | x / y |
| %        | Mod alma | Soldaki değeri sağdaki değere bölerek kalanı bulur. | x % y |
| ++       | Artırma  | İşlenen değeri 1 artırır.                           | x++   |
| - -      | Eksiltme | İşlenen değeri 1 azaltır.                           | x--   |

**7. UYGULAMA**: İşlem adımlarına göre aritmetiksel operatörlerin kullanıldığı bir uygulamayı tasarlayınız.

**1. Adım**: "AritmetikselOperatorler" adında yeni bir Java sınıfı tanımlayınız.

**2. Adım**: AritmetikselOperatorler sınıfı içine şu kodu yazınız:

```java
public class AritmetikselOperatorler {
    public static void main(String[] args) {
        int x = 10;
        int y = 3;
        int toplam = x + y;
        int fark = x - y;
        int carpim = x * y;
        int bolme = x / y;
        int mod = x % y;
        x++;
        y--;
        System.out.println("Toplam: " + toplam);
        System.out.println("Fark: " + fark);
        System.out.println("Çarpım: " + carpim);
        System.out.println("Bölme: " + bolme);
        System.out.println("Mod Alma: " + mod);
        System.out.println("Artırma: " + x);
        System.out.println("Azaltma: " + y);
    }
}
```

**3. Adım**: Yazdığınız kodu Run menüsünden Run ‘AritmetikselOperatorler.main()’ with Coverage
komutuyla çalıştırınız.

**Ekran Çıktısı**

>Toplam: 13\
Fark: 7\
Çarpım: 30\
Bölme: 3\
Mod Alma: 1\
Artırma: 11\
Azaltma: 2

>**SIRA SİZDE**
>
>Yedinci uygulamadaki **x değeri 13,** **y değeri 5** olacak şekilde değiştirildiğinde oluşacak sonuçları kâğıt üzerinde hesaplayıp aşağıdaki tabloya yazınız. Gerekli kodlamayı yaptıktan sonra çalıştırıp sonuçları karşılaştırınız.
>
>| İşlem    | Tahmininiz | Sonuç |
>| -------- | ---------- | ----- |
>| Toplam   |
>| Fark     |
>| Çarpım   |
>| Bölme    |
>| Mod Alma |
>| Artırma  |
>| Azaltma  |
>
>**DEĞERLENDİRME**: 
>
>Çalışmanız aşağıda yer alan kontrol listesi kullanılarak değerlendirilecektir. Çalışmanızı yaparken değerlendirme ölçütlerini dikkate alınız.
>
>**KONTROL LİSTESİ**
>
>| DEĞERLENDİRME ÖLÇÜTLERİ                                         | EVET | HAYIR |
>| --------------------------------------------------------------- | ---- | ----- |
>| 1. Toplam tahminini ve uygulama çıktısını doğru olarak buldu.   |
>| 2. Fark tahminini ve uygulama çıktısını doğru olarak buldu.     |
>| 3. Çarpım tahminini ve uygulama çıktısını doğru olarak buldu.   |
>| 4. Bölme tahminini ve uygulama çıktısını doğru olarak buldu.    |
>| 5. Mod alma tahminini ve uygulama çıktısını doğru olarak buldu. |
>| 6. Artırma tahminini ve uygulama çıktısını doğru olarak buldu.  |
>| 7. Azaltma tahminini ve uygulama çıktısını doğru olarak buldu.  |

## 3.6.2. Atama Operatörleri
Değişkenlere değer atama için atama operatörleri kullanılır (Tablo 3.4.).

**Tablo 3.4: Atama Operatörleri**

| Operatör | Örnek  | Benzeri   | Açıklama                                                                                                          |
| -------- | ------ | --------- | ----------------------------------------------------------------------------------------------------------------- |
| =        | x = 5  | x = 5     | Basit atama operatörüdür. Eşitliğin sağındaki değeri soldaki değişkenin içine aktarır.                            |
| +=       | x += 5 | x = x + 5 | Topla ve ata operatörüdür. Değişkeni eşitliğin sağındaki değer kadar artırır.                                     |
| -=       | x -= 5 | x = x -5  | Çıkart ve ata operatörüdür. Değişkeni eşitliğin sağındaki değer kadar azaltır.                                    |
| *=       | x *= 5 | x = x * 5 | Çarp ve ata operatörüdür. Değişkeni eşitliğin sağındaki değer ile çarpıp atama işlemini gerçekleştirir.           |
| /=       | x /= 5 | x = x / 5 | Böl ve ata operatörüdür. Değişkeni eşitliğin sağındaki değere bölüp atama işlemini gerçekleştirir.                |
| %=       | x %= 5 | x = x % 5 | Mod al ve ata operatörüdür. Eşitliğin sağındaki değere göre değişkenin modunu alıp atama işlemini gerçekleştirir. |

**8. UYGULAMA**: İşlem adımlarına göre atama operatörlerinin kullanıldığı bir uygulamayı tasarlayınız.

**1. Adım**: "AtamaOperatorleri" adında yeni bir Java sınıfı tanımlayınız.

**2. Adım**: AtamaOperatorleri sınıfı içine şu kodu yazınız:

```java
public class AtamaOperatorleri {
    public static void main(String[] args) {
        int x = 15;
        System.out.println("x = " + x);
        x += 3;
        System.out.println("x += 3 : " + x);
        x -= 2;
        System.out.println("x -= 2 : " + x);
        x *= 2;
        System.out.println("x *= 2 : " + x);
        x /= 4;
        System.out.println("x /= 4 : " + x);
        x %= 2;
        System.out.println("x %= 2 : " + x);
    }
}
```

**3. Adım**: Yazdığınız kodu Run menüsünden Run ‘AtamaOperatorleri.main()’ with Coverage komutuyla çalıştırınız.

**Ekran Çıktısı**

>x = 15\
x += 3 : 18\
x -= 2 : 16\
x *= 2 : 32\
x /= 4 : 8\
x %= 2 : 0

>**SIRA SİZDE**
>
>Sekizinci uygulamadaki **x değeri 13** olacak şekilde değiştirildiğinde oluşacak sonuçları kâğıt üzerinde hesaplayıp aşağıdaki tabloya yazınız. Gerekli kodlamayı yaptıktan sonra çalıştırıp sonuçları karşılaştırınız.
>
>| İşlem         | Tahmininiz | Sonuç |
>| ------------- | ---------- | ----- |
>| Atama         |
>| Topla ve ata  |
>| Çıkart ve ata |
>| Çarp ve ata   |
>| Böl ve ata    |
>| Mod al ve ata |
>
>**DEĞERLENDİRME**: 
>
>Çalışmanız aşağıda yer alan kontrol listesi kullanılarak değerlendirilecektir. Çalışmanızı yaparken değerlendirme ölçütlerini dikkate alınız.
>
>**KONTROL LİSTESİ**
>
>| DEĞERLENDİRME ÖLÇÜTLERİ                                                | EVET | HAYIR |
>| ---------------------------------------------------------------------- | ---- | ----- |
>| 1. "Atama" tahminini ve uygulama çıktısını doğru olarak buldu.         |
>| 2. "Topla ve ata" tahminini ve uygulama çıktısını doğru olarak buldu.  |
>| 3. "Çıkart ve ata" tahminini ve uygulama çıktısını doğru olarak buldu. |
>| 4. "Çarp ve ata" tahminini ve uygulama çıktısını doğru olarak buldu.   |
>| 5. "Böl ve ata" tahminini ve uygulama çıktısını doğru olarak buldu.    |
>| 6. "Mod al ve ata" tahminini ve uygulama çıktısını doğru olarak buldu. |

## 3.6.3. Karşılaştırma Operatörleri
Karşılaştırma operatörleri iki değeri karşılaştırmak için kullanılır (Tablo 3.5). Sonuç olarak boolean bir değer meydana gelir. Karşılaştırma işlemi doğru ise true, değil ise false değeri oluşur.

**Tablo 3.5: Karşılaştırma Operatörleri**

| Operatör | Adı                         | Örnek  |
| -------- | --------------------------- | ------ |
| ==       | Eşit mi?                    | x == y |
| !=       | Farklı mı? (Eşit değil mi?) | x != y |
| >        | Büyük mü?                   | x > y  |
| <        | Küçük mü?                   | x < y  |
| >=       | Büyük veya eşit mi?         | x >= y |
| <=       | Küçük veya eşit mi?         | x <= y |

**9. UYGULAMA**: İşlem adımlarına göre karşılaştırma operatörlerinin kullanıldığı bir uygulamayı tasarlayınız.

**1. Adım**: "KarsilastirmaOperatorleri" adında yeni bir Java sınıfı tanımlayınız.

**2. Adım**: KarsilastirmaOperatorleri sınıfı içine şu kodu yazınız:

```java
public class KarsilastirmaOperatorleri {
    public static void main(String[] args) {
        int x = 15;
        int y = 8;
        System.out.println("x ile y eşit mi : " + (x == y));
        System.out.println("x ile y farklı mı : " + (x != y));
        System.out.println("x, y’den büyük mü : " + (x > y));
        System.out.println("x, y’den küçük mü : " + (x < y));
        System.out.println("x, y’den büyük veya eşit mi : " + (x >= y));
        System.out.println("x, y’den küçük veya eşit mi : " + (x <= y));
    }
}
```

**3. Adım**: Yazdığınız kodu Run menüsünden Run ‘KarsilastirmaOperatorleri.main()’ with Coverage
komutuyla çalıştırınız.

**Ekran Çıktısı**

>x ile y eşit mi : false\
x ile y farklı mı : true\
x, y’den büyük mü : true\
x, y’den küçük mü : false\
x, y’den büyük veya eşit mi : true\
x, y’den küçük veya eşit mi : false

>**SIRA SİZDE**
>
>Dokuzuncu uygulamadaki x değeri 8 olacak şekilde değiştirildiğinde oluşacak sonuçları kâğıt üzerinde hesaplayıp aşağıdaki tabloya yazınız. Gerekli kodlamayı yaptıktan sonra çalıştırıp sonuçları karşılaştırınız.
>
>| İşlem | Tahmininiz | Sonuç |
>| ----- | ---------- | ----- |
>| ==    |
>| !=    |
>| >     |
>| <     |
>| >=    |
>| <=    |
>
>**DEĞERLENDİRME**:
>
>Çalışmanız aşağıda yer alan kontrol listesi kullanılarak değerlendirilecektir. Çalışmanızı yaparken değerlendirme ölçütlerini dikkate alınız.
>
>**KONTROL LİSTESİ**
>
>| DEĞERLENDİRME ÖLÇÜTLERİ                                      | EVET | HAYIR |
>| ------------------------------------------------------------ | ---- | ----- |
>| 1. "= =" tahminini ve uygulama çıktısını doğru olarak buldu. |
>| 2. "!=" tahminini ve uygulama çıktısını doğru olarak buldu.  |
>| 3. ">" tahminini ve uygulama çıktısını doğru olarak buldu.   |
>| 4. "<" tahminini ve uygulama çıktısını doğru olarak buldu.   |
>| 5. ">=" tahminini ve uygulama çıktısını doğru olarak buldu.  |
>| 6. "<=" tahminini ve uygulama çıktısını doğru olarak buldu.  |

## 3.6.4. Mantıksal Operatörler
Mantıksal operatörler iki veya daha fazla karşılaştırma işlemini değerlendirmek için kullanılır (Tablo 3.6). Sonuç olarak boolean bir değer meydana gelir. 

**Tablo 3.6: Mantıksal Operatörler**

| Operatör | Adı             | Örnek               | Açıklama                                                                                                                                                                                                                                                 |
| -------- | --------------- | ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| &&       | Ve              | (x == 5 && y ==6)   | x, 5’e eşit ve y, 6’ya eşit midir? <br><br> True değeri alması için her iki koşulun da doğru olması gerekir                                                                                                                                              |
| \|\|     | Veya            | (x == 5 \|\| y ==6) | x, 5’e eşit veya y, 6’ya eşit midir? <br><br> True değeri alması için her iki koşuldan sadece birinin doğru olması yeterlidir.                                                                                                                           |
| !        | Mantıksal değil | !(x == 5)           | x, 5’e eşit midir ifadesinin mantıksal tersini alır. <br><br> Parantez içindeki ifade **true** ise mantıksal tersini alarak **false** sonucunu üretir. <br><br> Parantez içindeki ifade **false** ise mantıksal tersini alarak **true** sonucunu üretir. |

**10. UYGULAMA**: İşlem adımlarına göre mantıksal operatörlerin kullanıldığı bir uygulamayı tasarlayınız.

**1. Adım**: "MantiksalOperatorler" adında yeni bir Java sınıfı tanımlayınız.

**2. Adım**: MantiksalOperatorler sınıfı içine şu kodu yazınız:

```java
public class MantiksalOperatorler {
    public static void main(String[] args) {
        int x = 5;
        int y= 8;
        System.out.println("x 10’dan büyük ve y 10’dan küçük mü : " + (x > 20 && y < 20));
        System.out.println("x 10’dan büyük ve y 10’dan küçük mü tersi : " + !(x > 20 && y < 20));
        System.out.println("x 10’dan büyük veya y 10’dan küçük mü : " + (x > 20 || y <20));
        System.out.println("x 10’dan büyük veya y 10’dan küçük mü tersi: " + !(x > 20 || y <20));
    }
}
```

**3. Adım**: Yazdığınız kodu Run menüsünden Run ‘MantiksalOperatorler.main()’ with Coverage komutuyla çalıştırınız.

**Ekran Çıktısı**

>x 10’dan büyük ve y 10’dan küçük mü : false\
x 10’dan büyük ve y 10’dan küçük mü tersi : true\
x 10’dan büyük veya y 10’dan küçük mü : true\
x 10’dan büyük veya y 10’dan küçük mü tersi: false

>**SIRA SİZDE:**
>
>Onuncu uygulamadaki **x değeri 15** olacak şekilde değiştirildiğinde oluşacak sonuçları kâğıt üzerinde hesaplayıp aşağıdaki tabloya yazınız. Gerekli kodlamayı yaptıktan sonra çalıştırıp sonuçları karşılaştırınız.
>
>**DEĞERLENDİRME**: 
>
>Çalışmanız aşağıda yer alan kontrol listesi kullanılarak değerlendirilecektir. Çalışmanızı yaparken değerlendirme ölçütlerini dikkate alınız.
>
>**KONTROL LİSTESİ**
>
>| DEĞERLENDİRME ÖLÇÜTLERİ                                                                | EVET | HAYIR |
>| -------------------------------------------------------------------------------------- | ---- | ----- |
>| 1. (x > 10 && y < 10) işleminin tahminini ve uygulama çıktısını doğru olarak buldu.    |
>| 2. !(x > 10 && y < 10) işleminin tahminini ve uygulama çıktısını doğru olarak buldu.   |
>| 3. (x > 10 \|\| y < 10) işleminin tahminini ve uygulama çıktısını doğru olarak buldu.  |
>| 4. !(x > 10 \|\| y < 10) işleminin tahminini ve uygulama çıktısını doğru olarak buldu. |