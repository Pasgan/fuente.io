# Fuente Content System V1.1

Bu sistem, Fuente'nin blog, LinkedIn, Instagram, podcast ve e-posta pazarlama içeriklerini tekrarlanabilir bir üretim standardına bağlar.

## 1. Ana üretim mantığı

Girdi esas olarak blog yazısıdır.

### 1. hafta
- Blog carousel
- LinkedIn paylaşım metni
- Instagram paylaşım metni
- E-posta pazarlama metni

### 2. hafta
- Podcast carousel
- LinkedIn paylaşım metni
- Instagram paylaşım metni
- Podcast e-posta metni

Podcast paylaşımı blog paylaşımının tekrar edilmiş veya kısaltılmış hali olmayacak. Aynı konuya farklı düşünsel giriş noktası kullanılacak.

## 2. Blog carousel standardı

Varsayılan uzunluk 6 içerik slaytı + 1 CTA veya marka slaytıdır. İçerik gerektiriyorsa 5 veya 6 slayta düşebilir.

### Slayt 1: Kapak
- kısa ve güçlü kanca
- gerekiyorsa ikinci düzey konu adı
- özgün ana görsel
- Fuente logosu
- fuente.com.tr
- ilerleme oku

### Slayt 2: Gerilim
Vaka, kısa hikâye, şaşırtıcı soru, paradoks veya gündelik iş hayatı örneği.

### Slayt 3: Kavramsal kırılma
Okuyucunun ilk varsayımını sorgulatan temel fikir.

### Slayt 4: Kurumsal karşılık
Kavram iş hayatına aktarılır.

### Slayt 5: Kullanılabilir değer
Okuyucuya gerçek bir soru, yöntem, uygulama veya çerçeve verilir.

### Son slayt: Blog CTA
Yalnızca bloga yönlendirme yapılır. Podcast bu slaytta yer almaz.

## 3. Podcast carousel standardı

Podcast carousel blog carouselden farklı yaratıcı ürün kabul edilir.

Varsayılan yapı 5 içerik slaytı + son CTA slaytıdır.

Podcast tasarımlarında mikrofon, ses dalgası, kulaklık ve Fuente altın tonları kullanılabilir.

### Kapak
Blog kapağından farklı kanca kullanılır.

### Orta slaytlar
Farklı soru, farklı örnek, yeni kavramsal ayrım veya bölümde karşılaşılacak fikirler kullanılır.

### Nihai podcast son slaytı
Onaylanmış referans yapı şudur:

**Bu bölümde neler var?**
- bölüm temalarının kısa listesi

Alt bölüm iki kolonludur:

**Sol:**
- Dinlemek için
- fuente.com.tr
- Paylaşımlar → Podcast

**Sağ:**
- Spotify ikonu
- Spotify
- Fuente Sohbetleri

Kesin kural: Son slaytta ilerleme oku kullanılmaz.

## 4. Görsel üretim standardı

Stok kurumsal fotoğraf estetiği varsayılan çözüm değildir.

Önce ana fikir belirlenir. Sonra fikir görsel metafora, gerçekçi sahneye veya güçlü objeye dönüştürülür.

Görsel açıklayıcı olmak zorunda değildir. Düşündürücü ve konuya özgü olması tercih edilir.

## 5. Formatlar

Her onaylı içerik için:
- Carousel: 1080x1350, 4:5
- Spotify: 800x800, 1:1
- Web: 1920x1080, 16:9

Formatlar yalnızca crop edilmez. Gerektiğinde kompozisyon yeniden düzenlenir.

## 6. Marka

Ana logo şeffaf arka planlı Fuente + The Source PNG'dir.

Genel renk ailesi:
- siyah
- koyu gri
- beyaz
- Fuente altın tonu
- Fuente kırmızısı

## 7. Tipografi

Ana başlık ve gövde ağırlıklı sans serif kullanır. Serif yalnızca bilinçli vurgu durumlarında kullanılır.

## 8. Metin yoğunluğu

- Kapak: yaklaşık 5-15 kelime
- Normal slayt: yaklaşık 25-45 kelime
- Hikâye/vaka slaytı: gerektiğinde yaklaşık 60 kelime

Carousel blogun küçültülmüş hali değildir.

## 9. LinkedIn PDF

Carousel görselleri onaylandıktan sonra LinkedIn'e doğrudan yüklenebilir tek PDF oluşturulur. Sayfa sırası PNG setiyle aynı olur.

Instagram için PNG seti kullanılır.

## 10. LinkedIn paylaşım metni

Carousel içeriğini tekrar etmez. Farklı bir giriş yapar, konuyu çerçeveler ve içeriğe bağlar.

## 11. Instagram paylaşım metni

LinkedIn metninin kopyası değildir. Platforma göre daha kompakt hazırlanabilir.

## 12. E-posta pazarlama

Her ana içerik için:
- 3-5 subject önerisi
- preview text
- ana e-posta gövdesi
- CTA
- gerektiğinde kısa alternatif

Blog ve podcast için ayrı paket hazırlanır.

## 13. Onay sistemi

Taslak hazırlanır. Tayfun açıkça onayladıktan sonra final dosyalar üretilir ve arşivlenir.

Onay öncesi final arşive yazılmaz.

## 14. Drive arşivi

Nihai üretimler Google Drive'da `sosyal_medya` altında tutulur.

Önerilen yapı:

```
sosyal_medya/
  YYYY/
    MM/
      Konu_Adi/
        01_Blog/
          Carousel_PNG/
          LinkedIn_PDF/
          Web_1920x1080/
        02_Podcast/
          Carousel_PNG/
          LinkedIn_PDF/
          Spotify_800x800/
          Web_1920x1080/
        03_Email/
        04_Copy/
        05_Source/
```

## 15. GitHub rolü

GitHub nihai görsel arşivi değildir. Sistem, standart, template ve versiyon geçmişini tutar.

## 16. GitHub ve Drive ayrımı

- GitHub = sistem, kurallar, template'ler, versiyon geçmişi
- Drive = nihai üretimler, PDF, PNG, web görseli, Spotify kapağı, e-posta ve paylaşım metinleri

## 17. Ana kullanım komutu

`Bu blogu Fuente Content System'e göre hazırla.`

Bu komut blog ve daha sonra podcast üretim paketini tetikleyen ana çalışma talebidir.
