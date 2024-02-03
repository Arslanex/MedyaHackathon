# VidInsight
VidInsight projesi, çeşitli dillerdeki videolara hızlı ve yüksek doğrulukla alt yazı ekleyip montajlama yeteneğine sahip bir teknoloji geliştirmeyi amaçlamaktadır. Projemiz, bir video dosyasının dilini otomatik olarak tespit edebilir ve orijinal dilde veya kullanıcının tercihine bağlı olarak seçilen bir alternatif dilde alt yazı sağlayabilir. Bu özellik, videoların daha geniş bir izleyici kitlesine ulaşmasını ve içerik oluşturucuların farklı dil konuşan kitlelerle etkileşim kurmasını kolaylaştırır. VidInsight, kullanıcı dostu bir arayüz sunarak video içeriklerin düzenlenmesi ve yayınlanması süreçlerini basitleştirmeyi hedefler.

## Kullanılan Teknolojii ve Kütüphaneler
### Deepgram API / Whisper Model
Kullanıcıdan alına .mp4 dosyasını ffmpeg kütüphanesi yardımı ile hızlıca .mp3 formatına çevirmemnin ardından fast_whisper modeli işeleme sokuyoruz.
### Google Traslate API
.srt dosyasını orjinal dilden kullanıcının istediği dile çevirmek için kullanıyoruz.
### Movipy
finalize edilmiş altyazıyı videoya gömmek için kullanıyoruz.

## Güncel Scriptler / Collab Klasörü
### Original Sub Dosyası
In: 
- .mp4 file
  
Out:
- .json file
- .srt file
- .docs file
- .sub added video

Dosyanın sonunda video içinde arana bir kelime olması durumunda bulunup bulunmadığını, .str dosyasında hangi aralıkta olduğunu ve video hangi saniyelerde olduğunu gösteren methodlar bulunmaktadır.

### Original Sub Dosyası
In: 
- .mp4 file
- goole api key
  
Out:
- .json file
- .srt file
- .docs file
- .sub added video

Dosyanın sonunda video içinde arana bir kelime olması durumunda bulunup bulunmadığını ve .str dosyasında hangi aralıkta olduğunu.

## Results



https://github.com/Arslanex/MedyaHackathon/assets/44752389/7f425a75-94e7-4518-9d8c-86418b73e3fb



