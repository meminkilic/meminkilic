# Merhaba, ben Mehmet Emin Kılıç 👋

Harita mühendisiyim. Sincan Belediyesi Plan ve Proje Müdürlüğü'nde kadastro, imar ve
CBS (GIS) alanında çalışıyorum. Mesleğimde karşılaştığım problemleri yazılımla çözüyorum:
kurum içi süreçleri hızlandıran masaüstü ve web uygulamaları, QGIS eklentileri ve
uçtan uca geliştirdiğim mobil ürünler.

- 📍 Ankara, Türkiye
- 🗺️ Uzmanlık: kadastro, parselasyon (18. madde), imar uygulamaları, mekânsal analiz,
  drone verisi (ortofoto / DSM / DTM)
- 💻 Kendi kendine öğrenmiş, tek kişilik geliştirici: tasarımdan yayına kadar tüm aşamalar
- 📫 İletişim: [e-posta](mailto:ADRESINIZ@ornek.com) · [LinkedIn](https://linkedin.com/in/LINKEDIN-ADINIZ)

---

## 🍽️ Rotaste — canlı ürün

**Şehir şehir, lokma lokma.** Türkiye için konum tabanlı restoran keşif uygulaması.
Fikirden App Store ve Google Play yayınına kadar tek başıma geliştirdim.

🔗 **[rotaste.com](https://www.rotaste.com)** · [Kaynak kod](https://github.com/meminkilic/lezzet-rotasi)

| | |
|---|---|
| **Platformlar** | Web, iOS (App Store), Android (Google Play) |
| **Backend** | Python, Flask, Railway |
| **Veri & kimlik** | Supabase (Google / Apple / e-posta girişi), Google Places API |
| **Mobil** | Capacitor ile native sarmalama, Codemagic CI/CD |
| **Öne çıkanlar** | Rota üzerinde arama (geometrik koridor filtresi + grid tabanlı önbellek), PKCE akışıyla native OAuth, deep link, çok aşamalı App Store onay sürecinin yönetimi |

---

## 🛠️ Diğer projeler

> Aşağıdaki projeler kurumsal veri ve iş süreçleri içerdiği için depoları özel (private)
> tutulmaktadır. Talep hâlinde demo ve teknik detay paylaşabilirim.

### İfraz & Tevhit Yönetim Sistemi

Tapu ve imar işlemlerinde ifraz (ayırma) ve tevhit (birleştirme) dosyalarını uçtan uca
yöneten tek dosyalık web uygulaması. PDF'ten otomatik veri çıkarımı, malik ve vekâlet
yönetimi, vekâlet metninin otomatik üretimi, GeoJSON yükleme ile parsel alanı hesabı,
çekme mesafesine göre yapılaşma alanı görselleştirmesi ve harita üzerinde kontrol.
`HTML · CSS · JavaScript · PDF analizi · GeoJSON`

### QGIS Parselasyon Eklentisi

3194 sayılı İmar Kanunu'nun 18. maddesi kapsamındaki arazi ve arsa düzenlemeleri için
QGIS eklentisi. DOP/KOP hesapları, kök parselden imar parseline dağıtım cetveli,
irtifak ve yapı bilgilerinin işlenmesi.
`Python · PyQGIS · Qt`

### Yol Kotu ve Çap Havale Programı

Müdürlüğe gelen yol kotu ve çap taleplerinin teknikerler arasında adil dağıtımını sağlayan
karar destek aracı. İşin türüne (uçuşlu / uçuşsuz ölçüm), bölge uzaklığına ve parsel
büyüklüğüne göre ağırlıklandırma; izin ve telafi takibi; mira metaforuyla görselleştirilmiş
denge paneli ve Excel'e aktarım.
`HTML · CSS · JavaScript · ExcelJS`

### Tapu Veri Arama Uygulaması

Kadastro MDB veri tabanları üzerinde ada/parsel ve mahalle bazlı hızlı arama yapan
masaüstü uygulaması. SQLite ön belleği ile büyük veri setlerinde anlık sonuç,
Excel'e aktarım.
`Python · PyQt5 · SQLite`

### MEK Systematic

Yapı aplikasyon harcı hesaplama aracı. Projeden yüklenen PDF üzerinde görsel alan seçimi,
sunucu tarafında metin çıkarımı ve otomatik harç hesabı. Hem bağımsız HTML hem de
Flask tabanlı web sürümü.
`Python · Flask · pdfplumber · pdf.js`

---

## 🧰 Kullandığım teknolojiler

- **Diller** — Python · JavaScript · SQL · HTML/CSS
- **Web** — Flask · Supabase · REST API · Railway
- **Mobil** — Capacitor · Codemagic (CI/CD) · App Store Connect · Google Play Console
- **Masaüstü** — PyQt5 · SQLite
- **CBS** — QGIS · PyQGIS · GDAL/OGR · GeoJSON · ITRF96 / TUREF TM33 · NetCAD · AutoCAD
- **Veri** — pandas · openpyxl · pdfplumber

---

<sub>Kurum bünyesinde geliştirilen uygulamaların kaynak kodları paylaşıma kapalıdır.
Ekran görüntülerindeki tüm veriler örnek verilerle üretilmiştir.</sub>
