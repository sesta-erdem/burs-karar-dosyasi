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
| 05 Yıllık maliyet | İngiltere (bursuz / burslu), Hollanda ve iki Almanya senaryosu |
| 06 Son tarihler | Önündeki turlar ve referans olarak kapanmış turlar |
| 07 Karşılaştırma tablosu | Aynı veriler tek tabloda, kabul eşiği kolonuyla |
| 08 Plan | Sıralı eylem maddeleri |
| 09 Kaynaklar | Okunan 18 resmi sayfanın listesi |

## Öne çıkan bulgular

- Surrey UK 2:1 karşılığı için **GPA 2.8–3.0/4.0**, TU Delft Türk lisans diploması için **CGPA 3.0/4.0** istiyor — yani kabul eşiği aşılıyor, sorun akademik ortalama değil.
- Asıl darboğaz İngilizce: Twente **IELTS 6.5 (her bölüm 6.0)** ve dil şartı karşılanmadan **koşullu kabul vermiyor**; TU Delft **7.0 (her bölüm 6.5)** istiyor.
- Almanya artık tümüyle harçsız değil: **Baden-Württemberg** AB dışından **€1.500/yarıyıl**, **Bayern**'de FAU yüksek lisansta **€2.000–6.000/yarıyıl** alıyor.
- Tam bursların kontenjanı çok küçük: TU Delft van Effen **fakülte başına 2**, GOI-IES dünya genelinde **60**, GREAT 19 ülkeye toplam **153**.

## Teknik

Tek `index.html` dosyası — build adımı yok. Grafikler [Chart.js 4.4.1](https://www.chartjs.org/) ile CDN üzerinden çiziliyor. Dağılım grafiğindeki etiketleri bir yerleştirme algoritması koyuyor: her etiket boş bir aday konum arıyor, hepsi sığmazsa grafik numaralı gösterime geçip altındaki künyeyi açıyor. Sayfa `prefers-color-scheme` ile açık ve koyu temaya uyum sağlar, mobilde de okunur.

GitHub Pages `main` dalının kökünden yayınlanır; `index.html` güncellenip push edildiğinde canlı sayfa kendiliğinden yenilenir.

## Uyarı

Veriler **3 Eylül 2026**'da kontrol edildi. Tutarlar ve son tarihler yıldan yıla değişir — başvurudan önce sayfadaki kaynak bağlantısından tekrar teyit et. Kur çevrimi €1 ≈ £0,85 varsayımıyla yapılmıştır.
