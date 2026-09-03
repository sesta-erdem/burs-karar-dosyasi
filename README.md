# Burs Karar Dosyası

Yurt dışı yüksek lisans için tek sayfalık karar dosyası: **kabul şartları**, hangi rotanın ne kadar gerçekçi olduğu, kapsam/şans dengesi, yıllık toplam maliyet ve son tarihler. Bütün tutar, tarih ve eşikler kurumların kendi sayfalarından okundu ve sayfada kaynak bağlantısıyla veriliyor.

## 🔗 Canlı sayfa

**https://sesta-erdem.github.io/burs-karar-dosyasi/**

## İçerik

| Bölüm | Ne var |
|---|---|
| 01 Karar özeti | Neyin gerçekçi olduğu, asıl engelin ne olduğu, asıl kararın ne olduğu |
| 02 Şans haritası | 9 rota, en yüksek şanstan en düşüğe; her biri için kazandırdığı / kabul şartı / başvuru / ana engel + kaynak linki |
| 03 Şans × Kapsam | Kazanma ihtimali ile yıllık değeri karşılaştıran dağılım grafiği |
| 04 Kabul şartları | İngiltere, Almanya, Hollanda ve İrlanda için GPA, IELTS, harç ve vize eşikleri |
| 05 Kırk üniversite | Her ülkeden 10 üniversite: kabul eşiği, İngilizce şartı, AB dışı harç ve okulun kendi bursu |
| 06 Yıllık maliyet | İngiltere (bursuz / burslu), Hollanda ve iki Almanya senaryosu |
| 07 Son tarihler | Önündeki turlar ve referans olarak kapanmış turlar |
| 08 Karşılaştırma tablosu | Aynı veriler tek tabloda, kabul eşiği kolonuyla |
| 09 Plan | Sıralı eylem maddeleri |
| 10 Kaynaklar | Okunan 18 resmi sayfanın listesi |

## Öne çıkan bulgular

**40 üniversite taramasından:**

- **Otomatik burslar rekabetçi olanlardan daha gerçekçi.** Sussex, sırf Türkiye vatandaşı olana **£5.000** düşüyor (panel yok, sıralama yok); Swansea Thrive **£4.000**; DCU mühendislik/bilgisayar **€5.000**; MTU **€3.000**; UCC not karşılığı **%10–20**.
- **İngilizce eşiği 6.0 ile 7.0 arasında değişiyor.** En düşükler MTU (6.0/5.5, mühendislik ve bilgisayar), Leeds (6.0/5.5), RWTH Aachen (6.0), Hannover (6.0), Sheffield (6.0). En yüksek TU Delft (7.0/6.5).
- **RWTH Aachen** harç almıyor ve IELTS 6.0 kabul ediyor; buna karşılık **TUM** yüksek lisansta yarıyıl başına €4.000–6.000 alıyor. Aynı ülke, tamamen farklı iki maliyet.
- **MTU'da veri bilimi / yapay zekâ / siber güvenlik yüksek lisansı** otomatik indirimle **€12.000/yıl** — bu listenin en ucuz İngilizce yüksek lisansı.
- **Utrecht Excellence Scholarship 2026-27'den itibaren kaldırıldı** (bütçe kesintisi). Eski listelerde hâlâ görünüyor.
- **Trinity'nin Global Excellence bursu** mühendislik, bilgisayar, işletme ve doğa bilimlerini kapsam dışı bırakıyor.
- **Sheffield** Türkiye için açık eşik veriyor: 2:1 = GPA 2.8 (ODTÜ, Boğaziçi, Bilkent, Sabancı, Koç, İTÜ düzeyi) veya 3.0 (diğer üniversiteler).

**İlk turdan:**

- Surrey UK 2:1 karşılığı için **GPA 2.8–3.0/4.0**, TU Delft Türk lisans diploması için **CGPA 3.0/4.0** istiyor — yani kabul eşiği aşılıyor, sorun akademik ortalama değil.
- Asıl darboğaz İngilizce: Twente **IELTS 6.5 (her bölüm 6.0)** ve dil şartı karşılanmadan **koşullu kabul vermiyor**; TU Delft **7.0 (her bölüm 6.5)** istiyor.
- Almanya artık tümüyle harçsız değil: **Baden-Württemberg** AB dışından **€1.500/yarıyıl**, **Bayern**'de FAU yüksek lisansta **€2.000–6.000/yarıyıl** alıyor.
- Tam bursların kontenjanı çok küçük: TU Delft van Effen **fakülte başına 2**, GOI-IES dünya genelinde **60**, GREAT 19 ülkeye toplam **153**.

## Teknik

Tek `index.html` dosyası — build adımı yok. Grafikler [Chart.js 4.4.1](https://www.chartjs.org/) ile CDN üzerinden çiziliyor. Dağılım grafiğindeki etiketleri bir yerleştirme algoritması koyuyor: her etiket boş bir aday konum arıyor, hepsi sığmazsa grafik numaralı gösterime geçip altındaki künyeyi açıyor. Sayfa `prefers-color-scheme` ile açık ve koyu temaya uyum sağlar, mobilde de okunur.

GitHub Pages `main` dalının kökünden yayınlanır; `index.html` güncellenip push edildiğinde canlı sayfa kendiliğinden yenilenir.

## Uyarı

Veriler **3 Eylül 2026**'da kontrol edildi. Tutarlar ve son tarihler yıldan yıla değişir — başvurudan önce sayfadaki kaynak bağlantısından tekrar teyit et. Kur çevrimi €1 ≈ £0,85 varsayımıyla yapılmıştır.
