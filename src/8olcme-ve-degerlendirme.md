<h1 style="text-align:center;">ÖLÇME VE DEĞERLENDİRME</h1>

**A) Aşağıdaki cümlelerde parantez içine yargılar doğru ise “D”, yanlış ise “Y” yazınız.**

**1.** ( ) Tehlikeli izne bağlı olan servisler dinlenebilir.

**2.** ( ) Yayın alıcılar manifest dosyasında tanımlanmalıdır.

**3.** ( ) SMS alma işlemleri bir yayın alıcı ile yapılır.

**4.** ( ) E-posta işlemleri IntentFilter nesnesi kullanılarak yapılır.

**5.** ( ) Kapatılmayan servisler sonsuza kadar çalışabilir.

**6.** ( ) IntentServisler aktivite ile doğrudan iletişim kurabilir.

**7.** ( ) API 23 öncesi sistemlerde kanal nesnesi olmadan bildirim verilir.

**8.** ( ) Zincir görevlerde her türlü WorkerRequest nesnesi kullanılır.

**9.** ( ) Tek seferlik çalışan görevlerde kısıtlama kullanmak zorunlu değildir.

**10.** ( ) Yazılım türü sensörler daha yavaş çalışır.

**B) Aşağıdaki cümlelerde boş bırakılan yerlere doğru sözcüğü yazınız.**

|                   |                   |                          |
| :---------------: | :---------------: | :----------------------: |
| Arka plan servisi |   PendingIntent   |        SmsManager        |
|     Manifest      |       Bound       | setRequiresBatteryNotLow |
|      Donanım      | BroadcastReceiver |       Notification       |
|                   |   setSmallIcon    |                          |


**11.** İşletim sisteminden gelen mesajları alabilmek için ................................................ kullanılır.

**12.** Yayın alıcılar mutlaka ................................................ dosyasına kaydedilmelidir.

**13.** SMS göndermek ve almak için ................................................ nesnesi kullanılır.

**14.** En temel Android servisi ................................................ servisidir.

**15.** Activity ile bağlantı kurularak çalışan servis türü ................................................ servistir.

**16.** Bildirim yapabilmek için NotificationManager nesnesine ................................................ verilmelidir.

**17.** Bildirimlerde ................................................ özelliği mutlaka olmalıdır.

**18.** Bildirimlerde kullanıcının bildirime dokunduğu ................................................ ile algılanır.

**19.** Görevler tanımlanırken düşük batarya kısıtı ................................................ ile ayarlanır.

**20.** En hızlı sensörler ................................................ sensörlerdir.


**C) Aşağıdaki soruları dikkatlice okuyarak doğru seçeneği işaretleyiniz.**


**21. Aşağıdakilerden hangisi bir yayın alıcı sınıfın metotlarından biridir?**

A) onResume \
B) onReceive\
C) onKill \
D) onPush\
E) onDestroy\

**22. Aşağıdakilerden hangisi temel Android uygulamalarından biri değildir?**

A) Activity \
B) BroadcstReceiver\
C) Service \
D) Worker\
E) Content Provider\

**23. Sürekli olarak çalışan ve stopService ile duruncaya kadar çalışan servis türü aşağıdakilerden hangisidir?**

A) Broadcast \
B) Arka plan servisi\
C) Bound \
D) Ön plan servisi\
E) Sticky\

**24. Activityler arasında veri alışverişlerinde aşağıdaki nesnelerden hangisi kullanılır?**

A) Data \
B) Worker\
C) Intent \
D) Service\
E) Bundle\

**25. Bildirim kanallarını ayarlayan nesne aşağıdakilerden hangisidir?**

A) NotificationChannel \
B) PendinIntent\
C) Notification \
D) WorkManager\
E) Service\

**26. Aşağıdakilerden hangisi bir WorkManager kısıtı <u>değildir?</u>**

A) setRequiresCharging \
B) setRequiresBatteryNotLow\
C) setRequiresDeviceIdle \
D) setDeviceNotConnected\
E) setManageCommand\

**27. Işık şiddetini ölçen sensörün anahtar adı aşağıdakilerden hangisidir?**

A) TYPE_ORIENTATION \
B) TYPE_GRAVITY\
C) TYPE_GYROSCOPE \
D) TYPE_ACCELEROMETER\
E) TYPE_LIGHT\

**28. Uygulamaya vektör grafikleri eklemeyi sağlayan aracın adı aşağıdakilerden hangisidir?**

A) Asset Studio \
B) App Inspection\
C) LogCat \
D) Manifest\
E) Image Studio

**29. Sensör verilerini almak için SensorEventListener aşağıdaki metotlardan hangisi ile kaydedilir?**

A) register \
B) receiver\
C) regListener \
D) registerListener\
E) registerSensor\

**30. WorkManager nesnesi, oluşturulan görevleri aşağıdaki metotlardan hangisi ile işleme alır?**


A) add \
B) enqueue\
C) insert \
D) append\
E) kill

**Ç) Aşağıdaki cümlelerde verilen işlemleri yapınız.**

**31. BroadcastReceiver oluşturmak için bir sınıf türetiniz.**

**32. E-posta göndermek için bir Intent oluşturup gerekli veri yazıp gönderiniz.**

**33. Servis.java servisini çalıştırınız.**

**34. Düşük pil seviyesinde çalışmayı engelleyen ve cihaz şarjdayken çalışmasını sağlayan Constraints nesnesini yazınız.**