<h1 style="text-align:center;">ÖLÇME VE DEĞERLENDİRME</h1>

**A) Aşağıdaki cümlelerde parantez içine yargılar doğru ise "D", yanlış ise "Y" yazınız.**

**1.** ( ) Şart ifadesi "true" olarak sağlandığı zaman if içindeki kodlar çalıştırılır.\
**2.** ( ) <,>,==,<=,>=,!= karakterleri aritmetiksel operatörlerdir.\
**3.** ( ) Maksimum dört adet for döngüsü iç içe yazılır.\
**4.** ( ) while döngüsünde yazılan şart ifadesi şartı sağlamasa da döngü en az bir defa çalıştırılır.\
**5.** ( ) Karar ifadelerinde şart yazılırken "||" operatörü kullanılırsa şartlardan birinin "true" olması yeterlidir.\
**6.** ( ) Java dilindeki String veri tipinde karşılaştırma yapılırken "==" ifadesi ile karşılaştırmak yeterlidir.

**B) Aşağıdaki kodlar çalıştırıldığında elde edilecek textView değerlerini ilgili başlıkta verilen kutucuğa yazınız.**


**7.** Aşağıdaki kodlar çalıştırıldığında textView ögesine eklenecek değerler nelerdir?

<table>
<thead>
    <tr>
        <td></td>
        <td>textView Değerleri</td>
    </tr>
</thead>
<tbody>
  <tr>
    <td><pre><code class="language-java">textView.setText("");
    for(int i=0;i < 50;i++){
        if(i==18 || i==27){
            continue;
        }
        if(i%3==0){
            textView.setText(textView.getText()+" "+ i);
        }
    }
    </code></pre>
    </td>
  </tr>
</tbody>
</table>

**8.** Aşağıdaki kodlar çalıştırıldığında textView ögesine eklenecek değerler nelerdir?

<table>
<thead>
    <tr>
        <td></td>
        <td>textView Değerleri</td>
    </tr>
</thead>
<tbody>
  <tr>
    <td><pre><code class="language-java">int sayac = 0,sonuc=1;
    while (sayac < 7)
    {
        sayac = sayac+1;
        sonuc = sonuc * sayac;
        textView.setText(textView.getText() + " " +sonuc);
    }</code></pre>
    </td>
  </tr>
</tbody>
</table>

**C) Aşağıdaki cümlelerde oluşturulması istenen kodları boş bırakılan yerlere yazınız.**

**9.** Eğer **sayi1** değişkeni **sayi2** değişkeninden büyük eşit ve **sayi3** değişkeninden de küçükse karar ifadesini Java diline uygun kod olarak oluşturunuz.

**10.** Daha öncesinde tanımlanan ve içinde String veri tutan editText_Adi ögesindeki değer, adiSoyadi içindeki değere eşit ise karar ifadesini Java diline uygun kod olarak oluşturunuz.

**11.** Daha öncesinde tanımlanan ve içinde 10 değeri tutan sayac değişkeni vardır. 0’dan sayac değişkeninin içindeki değere kadar olan tam sayıları Logcat ekranına yazdıran programın kodlarını Java diline uygun bir biçimde oluşturunuz.

**D) Aşağıdaki cümlelerde tasarlanması istenen kodları boş bırakılan yerlere yazınız.**

**12.** Üç farklı EditTextten üç not girişi yapıldığında en yüksek notu textView ögesinde gösteren uygulamanın karar kodlarını tasarlayınız.

**13.** EditText ögesine gün bilgisi yazı ile girildiğinde her gün için farklı bir günaydın mesajı tanımlayan programın kodlarını switch-case kullanarak tasarlayınız.