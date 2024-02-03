# VidInsight
VidInsight projesi, çeşitli dillerdeki videolara hızlı ve yüksek doğrulukla alt yazı ekleyip montajlama yeteneğine sahip bir teknoloji geliştirmeyi amaçlamaktadır. Projemiz, bir video dosyasının dilini otomatik olarak tespit edebilir ve orijinal dilde veya kullanıcının tercihine bağlı olarak seçilen bir alternatif dilde alt yazı sağlayabilir. Bu özellik, videoların daha geniş bir izleyici kitlesine ulaşmasını ve içerik oluşturucuların farklı dil konuşan kitlelerle etkileşim kurmasını kolaylaştırır. VidInsight, kullanıcı dostu bir arayüz sunarak video içeriklerin düzenlenmesi ve yayınlanması süreçlerini basitleştirmeyi hedefler.

## Örnek Çıktı
https://github.com/Arslanex/MedyaHackathon/assets/44752389/7f425a75-94e7-4518-9d8c-86418b73e3fb

## Deployment
Projemiz şuan erken geliştirme aşamasında oldu için tüm çalışmalar **Google Collab** sisteminde çalışmaktadır. İlerleyen aşamalarda bulut tabanlı bir yapıya geçmesi planlansada şuan için aşağıdaki bağlantılar ile ilgli dosyaları açmanız yeterli olacaktır. 

## How To Use 
VidInsight programı kapsamında aşağıdaki uygulamaları yapabilirsiniz. Yapmak istediğiniz işlemin collab dosyasını açarak işleminize başlayın. Her çalışmanın başında çalışanın ihityaç duyacağı dosyalar veya yapabileceğiniz ayarlamalar bulunmaktadır. Kısaca her dosya için yapmanız gereken yüklemeleri ve yapabilceğiniz ayarlamaları aşağıdaki tabloda paylaşıyorum. Daha detaylı rehber için [bağlantıya]() tıklayarak dökümana ulaşabilirsiniz.

İlgilendiğiniz işlemin Collab sayfasını açtıktan sonra tek yapmanız gerken aşağıda da belirtilen gerekli dosyaları yüklemek ve çalıştırmak.

### Orjinal Dilinden Alt Yazı -> Original_Sub.ipynb 
**Yüklenmesi Gereken Dosyalar:**
- kaynak video (.mp4 formatında)
  
**Yapılabilir Ayarlamalar:**
- Alt Yazı Ayarlamaları
  - Yazı Tipi
  - Font
  - Arka Plan Rengi
  - Yazı Konumu
  - ...

### Seçilen Dilden Alt Yazı -> Translated_Sub.ipynb 
**Yüklenmesi Gereken Dosyalar:**
- kaynak video (.mp4 formatında)
- Google Cloud API Key (.json formatında)
  
Bu kütüphaneyi kullanmak için bir Google Cloud API Anahtarına ihtiyacınız var. Yeni bir json anahtarı oluşturmanız gerekmektedir. Bağlantız üzerinden detaylara uaşabilrisiniz. [here](https://console.cloud.google.com/apis/credentials/serviceaccountkey). 

  
**Yapılabilir Ayarlamalar:**
- Çeviri Ayarlamaları
  - Mevcut Dil
  - Hedef Dil
    
- Alt Yazı Ayarlamaları
  - Yazı Tipi
  - Font
  - Arka Plan Rengi
  - Yazı Konumu
  - ...
