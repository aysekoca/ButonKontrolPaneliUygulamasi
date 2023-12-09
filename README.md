# ButonKontrolPaneliUygulamasi
## BUTON KONTROL PANELİ UYGULAMASI

#### NEDİR VE NE İŞE YARAR

Buton kontrol paneli uygulaması özelleştirilmiş bir buton sınıfı oluşturur. Her buton farklı durumları temsil etmek için renk ve simgeler ile  tasarlanmıştır. Tıklanabilirlik özelliği eklenmiş olup butonlara tıklandığında durumları değişir.<br>
Daha basit olarak anlatırsak bu uygulama özel tuşlar yapmak için kullanılır. Tuşlara tıklandığında farklı renkler ve simgeler gösterirler. Örnek vericek olursak aktifken bir rengi ve simgeyi, pasifken farklı bir rengi ve simgeyi gösterebilirler. Bu uygulama basit bir arayüz içinde bu özel butonlardan oluşan bir panel oluşturur ve bu panelden farklı durumları temsil eden butonlarla birlikte bir örnek yaratır.

#### KODU NASIL KULLANABİLİRİZ VE NASIL TEST EDEBİLİRİZ

1)CustomButton sınıfı özelleştirilmiş butonları temsil eder. Butonların özelliklerini dinamik olarak değiştirmek ve butonlara tıklama olaylarını yönetmek için kullanılır
Kodu çalıştırmak için, main metodu olan CustomButton sınıfını çalıştırabiliriz. <br>

2)Butonların Özellikleri <br>
Bu kod, özel butonlar oluşturur. Her bir butonun üzerinde belirli bir metin bulunur ve bu butonlara tıklandığında renkleri ve simgeleri değişir.<br>
Butonları oluştururken kullanabileceğiniz bazı özellikler vardır:<br>
         **a)Metin:** Butonun üzerinde göstermek istediğiniz yazı. <br>
         **b)Pasif Rengi:** Butonun pasif durumda olduğunda göstereceği renk.<br>
         **c)Aktif Rengi:** Butonun aktif durumda olduğunda göstereceği renk.<br>
         **d)Pasif Simgesi:** Buton pasif durumdayken göstereceği simge.<br>
         **e)Aktif Simgesi:** Buton aktif durumdayken göstereceği simge.<br>
         **f)GraphQL Schema:** Butona tıklandığında çalıştırılacak olan hayali GraphQL şeması.<br>


Butonların Özelliklerini Değiştirme:<br>
Butonların metin değerlerini, renklerini ve simgelerini değiştirmek için setButtonText, setButtonColors ve setButtonIcons gibi metodları kullanabiliriz. Bu metodlar, butonların görünümünü ayarlamanıza sağlar.<br>

3)Kodu Test Etme <br>
Kodu çalıştırdıktan sonra, oluşturulan butonların görünüşünü ve davranışını gözlemleriz.
Butonlara tıklayarak durumlarının nasıl değiştiğini görebilir ve renk/simge değişimini test edebiliriz.
Butonları farklı şekillerde oluşturarak nasıl çalıştığını gözlemleyebiliriz. Örneğin, farklı renkler veya farklı simgelerle deneyebiliriz.<br>
#### UYGULAMAYA AİT KODUN ÇALIŞTIRILMA VİDEOSU:

[Uploading Ekran Kaydı 2023-12-09 15.54.00.zip…]()






#### UYGULAMAYA AİT EKRAN GÖRÜNTÜLERİ:

<img width="402" alt="Resim1" src="https://github.com/aysekoca/ButonKontrolPaneliUygulamasi/assets/115224843/6c51614b-443f-44a4-8e56-968e8116c6a6"> <br>


<img width="397" alt="Resim2" src="https://github.com/aysekoca/ButonKontrolPaneliUygulamasi/assets/115224843/60babcff-aa16-4524-9a70-1214bd5a4fb0"> <br>

<img width="415" alt="Resim3" src="https://github.com/aysekoca/ButonKontrolPaneliUygulamasi/assets/115224843/cff9590b-d4d6-424f-b9b4-54985c1b42e8"> <br>

 


 


### GRAPQL ŞEMASI

Buton kontrol paneli uygulamasında kullandığımız GraphQL şeması, bir tür veri organize etme ve erişme yapısıdır.<br>
Örnek vericek olursak, bir uygulama kullanıcılar gönderiler veya ürünler gibi farklı veri türlerine sahip olabilir. GraphQL şeması, bu veri türlerini ve bunlarla yapılabilecek işlemleri(örneğin, yeni bir kullanıcı oluşturma veya bir gönderiyi güncelleme gibi) tanımlar. Uygulamamızdaki hayali  graphqlSchema ise her bir butonun ilişkilendirildiği bu yapısal şemayı temsil eder. Bu şema o butonun hangi veriyi veya işlemi temsil ettiğini belirtir. Bu şekilde, butonlara tıklama işlemi, belirtilen GraphQL şemasında tanımlanan bir işlemi gerçekleştirir.

 



#### GrapQl Şemasının Kullanım Örnekleri:

1)Sosyal Medya Uygulamaları: Kullanıcı profilleri, paylaşılan gönderiler veya yorumlar gibi içerikler, kullanıcılar arasındaki etkileşimleri temsil eden GraphQL şemaları üzerinden yönetilebilir. Örneğin, bir "beğeni" butonu veya "yorum yap" butonu, ilgili gönderiye yapılan bir GraphQL mutasyonuyla ilişkilendirilmiş olabilirler.<br>

2)E-Ticaret Siteleri: Ürünler, kategoriler, sepet işlemleri gibi e-ticaret işlevleri GraphQL şemaları aracılığıyla temsil edilebilir. Bir "sepete ekle" butonu, ilgili ürünün eklenmesini temsil eden bir GraphQL mutasyonuyla ilişkilendirilebilir.<br>

3)Hava Durumu Uygulamaları: Hava durumu verileri, şehirler veya koordinatlar aracılığıyla alınabilir. Kullanıcılar, belirli bir şehir için hava durumu verilerini almak için bir butona tıkladıklarında, bu buton ilgili GraphQL sorgusunu tetikleyebilir.<br>

4)Oyunlar: Oyunlarda, kullanıcıların puanlarını saklama, başarıları veya seviye geçişlerini yönetme gibi işlemler için GraphQL şemaları kullanılabilir. Örneğin, bir "skor gönder" butonu, kullanıcının oyun skorunu sunucuya göndermek için bir GraphQL mutasyonu tetikleyebilir.<br>

5)Mobil Uygulamalar: Kullanıcı oturum açma, profil güncelleme, fotoğraf yükleme gibi temel işlemler GraphQL şemaları üzerinden yönetilebilir. Bir "profil fotoğrafı değiştir" butonu, ilgili işlemi gerçekleştiren bir GraphQL mutasyonunu tetikleyebilir.<br>


Yukarıdakı örnekler günlük hayatta GraphQL şemalarının çeşitli kullanım alanlarını bizlere gösterir.Her biri, kullanıcıların etkileşimde bulunduğu farklı işlevleri temsil eden butonlar veya işlevlerle ilişkilendirilebilir. Bu butonlar, kullanıcı etkileşimleriyle belirli bir işlemi gerçekleştirmek için GraphQL şemasını kullanabilir.<br>

Özetle graphqlSchema alanı, her bir butonun tıklama işlemiyle bağlantılı olduğu GraphQL yapısını temsil eder. Bu yapı, butonun hangi veriyi işlediğini veya hangi işlemi gerçekleştirdiğini belirtir.












