İklim Değişikliğini Engellemek

Bir eko hesaplayıcı türü projedir.
Yani bilgi veren bir site.
İklim Değişikliği hakkında bilgiler vardır.

Projenin amacı:
Size bilgiler verir.

-------------------------------------------------------------------------------------------------------------------------------

Nasıl Yapacağım?

Proje VS CODE üzerinden yapılacak. Orada Mezuniyet projesi için bir klasör oluşturuldu. Read.me sadece nasıl yapılacağını görmek için.

*Küresel ısınma hakkında bilgi veren bir web sitesi (blog veya bilgilendirme sitesi) için Python (Flask) ve Jinja ikilisi mükemmel bir tercihtir. Flask projenin arkasındaki mantığı ve sayfaların yönlendirmesini yönetirken, Jinja da küresel ısınma verilerini, makaleleri ve görselleri HTML şablonlarınıza dinamik olarak yerleştirmenizi sağlar.

Flask nedir, ne işe yarar:

*Flask, web siteleri ve web uygulamaları oluşturmamıza yardımcı olan bir Python kütüphanesidir. Sıradan Python kodunu gerçek bir web sunucusuna dönüştürür – tıpkı gerçek web sitelerini çalıştıranlar gibi!

Neden Flask kullanmalı? Flask ile şunları yapabilirsiniz:

Kendi web sayfanızı oluşturabilirsiniz;
İstekleri işleyebilirsiniz (örneğin, /, /about, /game gibi adreslere);
Python'da kullanılan kodları doğrudan HTML'de de kullanabilirsiniz;
Basit bir yönetici paneli, sohbet, oyun, blog – gerçekten istediğiniz her şeyi oluşturabilirsiniz!

HTML'den farkı nedir?
Flask arka uçtur – sitenin mantığıdır ve Python ile yazılmıştır!
HTML, web sitesinin görünümünden sorumludur.
Flask ise kararları verir: neyin, ne zaman ve kime gösterileceğini.

Nasıl çalışır?
Bir Flask uygulamasını çalıştırdığınızda, bu uygulama bilgisayarınızda bir "mini sunucu" açar. Tarayıcınız üzerinden belirli bir adrese (http://localhost:5000 gibi) girerek erişebilirsiniz.

-----------------------------------------

HTML

Bir web sitesi oluşturmak için öncelikle sayfa düzenini tasarlamamız gerekiyor! Bu iş için HTML (bir programlama dili değildir!) mükemmel bir araçtır!
1. İlk olarak index.html adında bir dosya oluşturuyoruz.
2. Ardından sayfa için bir kod yazmalıyız!
3. Başarılı!

Bir HTML sayfası etiketlerden oluşur. İşte en önemli olanlardan bazıları:

- <html></html> - ana etiket - onsuz yapamazsınız! Diğer tüm etiketler bunun içinde yer alır!
- <head></head> - sayfa hakkındaki tüm önemli bilgileri içeren etiket!
- <body></body> - bu etiket genellikle sayfanın tüm içeriğini içerir.
- <h1></h1> - bu büyük bir başlık!
- <p></p>  - bu etiket basit bir metin içerir!
- <img> - ve bu ilk eşleşmeyen etiketimiz! Bir resim yerleştirmemize izin verir!

Örneği inceleyin (Projenin HTML kodu için bu örnek çok önemli!):

<!DOCTYPE html>
<html>
<head>
    <title>Tarayıcıda görünecek sekmenin adı</title>
</head>
<body>
    <h1>Bu büyük bir başlık!</h1>
    <p>Bu sadece bir paragraf metni</p>
    <h2>Bu daha az büyük bir başlık</h2>
             <ul>
                   <li>Bu bir madde işaretli liste öğesidir (ilk öğe)</li>
                   <li>bu da ikinci öğe</li>
             </ul>
     <img src="BURAYA RESMİN BAĞLANTISINI YAPIŞTIRIN" alt="Image1">
</body>
</html>

HTML kodunun temeli bu olmalıdır!












