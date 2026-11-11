# Bir Valiz, Üç Şehir, Bir Ömür

**Ayhan Bozkurt’un hayatından sinematik, etkileşimli bir yol hikâyesi.**

**Zindancılar Köyü — Karadeniz Ereğli — Zonguldak | İstanbul | Ankara**

Bir köyde başlayan çocukluk, Karadeniz kıyısında geçen okul yılları, Ankara’daki üniversite hayatı, İstanbul’da geçen on iki yıl ve yeniden Ankara’ya dönüş…

*Bir Valiz, Üç Şehir, Bir Ömür*, bu yolculuğu çizgilerin canlandığı sahneler, şehirlerin kimliğine göre değişen müzikler ve edebî bir anlatımla sunan tek dosyalık bir HTML deneyimidir.

## Hikâyenin Akışı

- **1984 — Zindancılar Köyü:** Ahşap köy evleri, orman, dere, tarla, inekler, köpekler ve çocukluğun gündelik hayatı.
- **1995 — Gülüç / Karadeniz Ereğli:** Ortaokul yılları; amcaoğlu Selçuk’la Gülüç Irmağı üzerindeki köprüden ayazda okula yürüyüş.
- **1998–2002 — Karadeniz Ereğli Anadolu Lisesi:** Hazırlık sınıfıyla başlayan eğitim ve 2002 mezuniyeti.
- **2002–2006 — Ankara:** Ankara Üniversitesi Dil ve Tarih-Coğrafya Fakültesi’nde öğrencilik; sonrasında Ankara’da askerlik dönemi.
- **2007–2019 — İstanbul:** Sabancı Üniversitesi ve Özyeğin Üniversitesi’nde çalışma yılları; Beşiktaş, Üsküdar ve Harem’den veda.
- **2019’dan itibaren — Ankara:** Cumhurbaşkanlığı Millet Kütüphanesi, yazarlık, eğitim ve yapay zekâ çalışmaları.

## Deneyimin Özellikleri

- **46 sahnelik** kronolojik, bölüm bölüm ilerleyen anlatı
- Sinematik açılış jeneriği ve üç boyutlu derinlik etkili tipografi
- SVG tabanlı line-art animasyonlar, kamera hareketleri ve sahne geçişleri
- Gün doğumu, gündüz, gün batımı ve gece atmosferleri
- Zindancılar, Ereğli, İstanbul ve Ankara için ayrı müzik kimlikleri
- Şehirler arası yumuşak müzikal geçişler ve ortam sesleri
- **Hikâyeyi oku** bölümünde edebî anlatı
- Mobil ve masaüstü ekranlara uyumlu oynatma deneyimi
- Harici JavaScript kütüphanesi veya ses dosyası gerektirmeyen tek HTML dosyası

## Görsel Sanat Stili

Projenin ana görsel dili **Line Art (Çizgi Sanatı)** üzerine kuruludur. Şehirler, yapılar, insanlar ve doğa unsurları raster fotoğraflarla değil, **SVG vektör illüstrasyonları** ile sahneye taşınır.

- **Line Art / Outline Illustration:** Mimari formlar, insan figürleri ve doğal unsurların belirgin kontur çizgileriyle betimlenmesi.
- **Animated Line Drawing:** Çizgilerin ekranda adım adım çiziliyormuş gibi görünmesi.
- **Minimalist Editorial Illustration:** Açık tonlar, sınırlı renk vurguları, temiz tipografi ve hikâye odaklı kompozisyon.
- **Cinematic Motion Graphics:** Jenerik, başlık animasyonları, ışık, atmosfer ve sinematik kadrajlar.
- **2.5D / Parallax:** İki boyutlu çizim katmanlarına farklı hızlarda hareket verilerek derinlik yanılsaması oluşturulması.
- **3D-Effect Typography:** Açılış başlığında perspektif, dönüş, gölge ve katmanlama ile oluşturulan üç boyutlu görünüm. Gerçek zamanlı üç boyutlu modelleme veya WebGL sahnesi değildir.

## Animasyon ve Sahneleme Teknikleri

- **SVG Stroke Animation:** `stroke-dasharray` ve `stroke-dashoffset` ile çizgilerin aşamalı olarak görünmesi.
- **CSS Keyframe Animation:** Yürüyüş, doğal çevre hareketleri, ışık değişimleri ve jenerik animasyonları.
- **SVG Clipping / Reveal:** Maske ve kırpma alanlarıyla sahnelerin çizgisel olarak açılması.
- **Parallax Camera Motion:** Ön plan ve arka plan katmanlarının farklı hızlarda hareket etmesi.
- **Kinetic Typography:** Başlık ve metinlerin zamanlamalı olarak sahneye girmesi.
- **Day–Night Color Grading:** Gökyüzü, ışık ve atmosfer tonlarının günün saatine göre değişmesi.
- **Audio Crossfade:** Bölgeye özgü müziklerin şehir geçişlerinde birbirine yumuşak biçimde devredilmesi.

Bu teknikler bir araya gelerek **çizgi animasyonu temelli, sinematik ve etkileşimli bir dijital yaşam anlatısı** oluşturur.

Müzikler, geleneksel eser kayıtları değil; bölgelere özgü enstrümanlardan esinlenen ve **Web Audio API** ile tarayıcıda üretilen özgün dijital düzenlemelerdir.

## Çalıştırma

1. `Bir_Valiz_Uc_Sehir_Bir_Omur_Sinematik_Intro_Guncel.html` dosyasını indirin.
2. Dosyayı Chrome, Edge veya Safari gibi güncel bir tarayıcıda açın.
3. Açılış jeneriğinden sonra hikâyeyi izleyin; sesi etkinleştirmek için **Müziği aç** düğmesine basın.

Kurulum, sunucu, API anahtarı veya internet bağlantısı gerekmez. Tarayıcıların otomatik ses oynatma politikaları gereği müzik kullanıcı etkileşiminden sonra başlar.

## Kontroller

| Tuş / Hareket | İşlev |
| --- | --- |
| `→` | Sonraki sahne |
| `←` | Önceki sahne |
| `Boşluk` | Oynat / duraklat |
| `M` | Müziği aç / kapat |
| `F` | Tam ekran |
| `Esc` | Açık hikâye penceresini kapat |
| Mobilde sağa / sola kaydırma | Sahneler arasında geçiş |

## Teknoloji

**HTML5 · CSS3 · JavaScript · SVG · Web Audio API**

Sahneler vektörel çizimler ve tarayıcı tabanlı animasyonlarla oluşturulmuştur. Görseller ve müzik, harici servis çağrısı gerektirmeden yerel olarak çalışır.

## Telif Hakkı

**© 2026 Ayhan Bozkurt — AI’Han Academy. All rights reserved.**

Tüm hakları saklıdır. İzinsiz çoğaltma, yeniden dağıtım veya ticari kullanım için hak sahibinden izin alınmalıdır.
