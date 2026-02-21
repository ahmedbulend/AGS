# AGS Giyim - Endüstriyel Çözümler & İş Kıyafetleri

Bu repository, AGS Giyim (Giyim Sanayi & Endüstriyel Çözümler) firması için hazırlanan modern, performanslı ve premium tasarımlı kurumsal web sitesinin kaynak kodlarını içermektedir.

Tasarımda, hiçbir ağır framework veya kütüphane kullanılmadan doğrudan **Vanilla HTML5, CSS3 ve JavaScript** teknolojilerinden yararlanılmıştır. Böylece sayfa açılış hızı maksimize edilmiş, esnek ve dinamik bir kullanıcı deneyimi oluşturulmuştur.

## Kurulum ve Çalıştırma

Bu bir statik web projesi olduğu için herhangi bir sunucu yapılandırmasına veya veritabanı kurulumuna ihtiyaç duymaz.

1. Projeyi bilgisayarınıza indirin (ZIP olarak veya `git clone` komutuyla).
2. Dosyaları çıkarttığınız klasöre gidin.
3. `index.html` dosyasına çift tıklayarak modern web tarayıcınızda (Chrome, Firefox, Safari, Edge vb.) hemen görüntüleyebilirsiniz.
4. Geliştirme sürecindeyseniz, daha iyi bir deneyim için VS Code üzerinden "Live Server" eklentisini kullanabilirsiniz.

## Proje Yapısı

```text
├── assets/                  # Logo, AI ile özel üretilen görseller vb.
│   ├── endustriyel-yaglar.png 
│   ├── is-elbiseleri.png
│   ├── logo.png
│   └── robot-elbiseleri.png
├── index.html               # Ana Sayfa (Kahraman alanı, Hakkımızda, Hizmet Kartları, İletişim)
├── is-elbiseleri.html       # İş Elbiseleri ve Kurumsal Kıyafet Detay Sayfası
├── robot-elbiseleri.html    # Endüstriyel Robot Koruyucu Kılıflar Detay Sayfası
├── endustriyel-yaglar.html  # Premium Endüstriyel Yağlar Detay Sayfası
├── style.css                # Temel tasarım sistemi, dark/light mod değişkenleri ve animasyonlar
└── script.js                # Tema değiştirme, mobil menü ve scroll (kaydırma) animasyonları
```

## Temel Özellikler

- **Açık Tema (Light Mode) / Koyu Tema (Dark Mode):** Kullanıcılar istedikleri an, sitenin gezinme çubuğunda (navbar) bulunan ikon ile temalar arası akıcı bir geçiş yapabilirler.
- **Glassmorphism (Cam Efekti):** Kartlarda ve arka planlarda kullanılan özel bulanıklaştırma (blur) efektleriyle tasarıma premium bir görünüm kazandırılmıştır.
- **Micro-Animasyonlar:** Aşağı doğru kaydırdıkça içeriklerin yumuşak bir şekilde ekranda belirmesi (scroll reveal) ve tıklama/buton efektleri ile etkileşim artırılmıştır.
- **Fully Responsive:** Akıllı telefonlardan, tabletlere ve geniş ekranlı masaüstü monitörlere kadar tüm cihazlarda kusursuz çalışacak mobil uyumlu mimari oluşturulmuştur.
- **Custom Fonts:** Temiz ve okunabilir bir tipografi için Google Fonts altyapısından `Inter` ve `Outfit` kullanılmıştır.

## GitHub Pages ile Canlıya Alma (Deployment)

1. Bu repository'i kendi GitHub hesabınızda oluşturun (örn. `kullaniciadi.github.io` veya özel bir repo adı altından Pages aktif edilerek).
2. Projedeki tüm dosyaları reponuzun `main` (veya `master`) dalına yükleyin.
3. Eğer `kullaniciadi.github.io` isimli özel bir depo açtıysanız web siteniz otomatik olarak o adreste saniyeler içinde yayına girecektir.

## Lisans ve İletişim

**AGS Giyim Sanayi & Endüstriyel Çözümler**

Bağlarbaşı Mahallesi\
2. Nilüfer Cadde - No: 25\
Osmangazi / Bursa

- Telefon: +90 (532) 765 76 77
- E-posta: agsgiyim.fatihaltun@hotmail.com
