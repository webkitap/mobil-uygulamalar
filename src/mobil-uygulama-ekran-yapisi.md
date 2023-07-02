<h1 style="color:#00b9f2;">2.2. MOBİL UYGULAMA EKRAN YAPISI</h1>

Mobil uygulama geliştirilirken uygulama çalıştığında ekran yapısında bazı bileşenler yer alır. En üstte **status bar (durum çubuğu)**, onun hemen altında **action bar (i̇şlem çubuğu)** ve ekranın en altında ise **navigation bar (gezinti çubuğu)** bulunur. Uygulama çalıştığında ekranda görünmeyen activity (MainActivity) ve activity içinde kullanıcı ile etkileşime girecek bileşenlerin bulunduğu ViewGroup (Görünüm grubu) Görsel 2.2’de farklı renklerle gösterilmiştir. 
<div style="display:block;text-align:center">

![Mobil uygulama ekran yapısı](./ekran-tasarimi/gorsel-2.2-mobil-uygulama-ekran-yapisi.png)
</div>

- **Status Bar**: Mobil cihaz ekranının en üstünde yer alan bu çubukta pil durumu, saat, ağ bağlantı simgesi gibi bildirimler bulunur.

- **Action Bar**: Bu çubuk activitynin üst tarafında yer alır. Uygulama ismi, activity ismi veya simgeleri, ek görünümler ve etkileşimli nesneler bu çubukta bulunabilir. Ayrıca gezinti yapmak için işlem çubuğuna simgeler yerleştirilebilir.

- **Navigation Bar**: Alt gezinti çubuğu olarak da isimlendirilen, uygulama ekranının altında görünen çubuktur. Ekranlar ve uygulamalar arasında temel gezinme işlemleri buradaki simgelerden yapılır. 