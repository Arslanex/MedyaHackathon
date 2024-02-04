# VidInsight
VidInsight projesi, çeşitli dillerdeki videolara hızlı ve yüksek doğrulukla alt yazı ekleyip montajlama yeteneğine sahip bir teknoloji geliştirmeyi amaçlamaktadır. Projemiz, bir video dosyasının dilini otomatik olarak tespit edebilir ve orijinal dilde veya kullanıcının tercihine bağlı olarak seçilen bir alternatif dilde alt yazı sağlayabilir. Bu özellik, videoların daha geniş bir izleyici kitlesine ulaşmasını ve içerik oluşturucuların farklı dil konuşan kitlelerle etkileşim kurmasını kolaylaştırır. VidInsight, kullanıcı dostu bir arayüz sunarak video içeriklerin düzenlenmesi ve yayınlanması süreçlerini basitleştirmeyi hedefler.

## Örnek Çıktı
https://github.com/Arslanex/MedyaHackathon/assets/44752389/2754c457-9de4-44ff-9159-a9d1598df8c5

## Deployment
Projemiz şuan erken geliştirme aşamasında oldu için tüm çalışmalar **Google Collab** sisteminde çalışmaktadır. İlerleyen aşamalarda bulut tabanlı bir yapıya geçmesi planlansada şuan için aşağıdaki video örneğinde olduğu gibi dosyaları collab üzerinden açabilir ve çalıştırabilirsiniz. Aşağıda örnek bir video bulunmaktadır.

https://github.com/Arslanex/MedyaHackathon/assets/44752389/af882d64-c880-4d8c-adf3-ec48b863c845

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
 
  ### Bir Videoda Aranan Kelime(leri) Bulma -> Find_It.ipynb
  **Yüklenmesi Gereken Dosyalar:**
- kaynak video (.mp4 formatında)
- Deepgram API Key [here](https://console.deepgram.com/project/17fc1ef6-8a79-4d16-85e6-37ab5edb1404/keys)

**Yapılabilir Ayarlamalar:**
- Aranan kelime

### Video Özetleme -> Summurize_Vide_Desc.ipynb
**Yüklenmesi Gereken Dosyalar:**
- kaynak video (.mp4 formatında)
- openai api code
  
**Yapılabilir Ayarlamalar:**
- Aranacak kelime

