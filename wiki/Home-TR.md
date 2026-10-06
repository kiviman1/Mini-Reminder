# Forever Mini Reminder

[EN · English](Home) | **TR · Türkçe**

> **World of Warcraft: Forever için akıllı hatırlatmalar, savaş bilgileri ve hafif dünya yardımcıları.**  
> Gerektiği anda faydalı bilgiyi gösterir; oyunu bir rotasyon yardımcısına dönüştürmez.

**Sürüm 1.19.4** · **Forever 1.60.1** · **Interface 16001** · **English + Türkçe**

---

## Buradan başla

| Addonu yeni mi kuruyorsun? | Ayarları mı düzenleyeceksin? | Bir şey çalışmıyor mu? |
|---|---|---|
| [**Kurulum ve İlk Ayarlar →**](Installation-and-Setup-TR) | [**Ayarlar Rehberi →**](Settings-Reference-TR) | [**Sorun Giderme →**](Troubleshooting-TR) |
| Doğru kurulumu yap ve ilk hatırlatmaları ekrana getir. | Önemli seçeneklerin ne yaptığını tek tek gör. | Yaygın sorunları çöz ve hata raporuna ne eklemen gerektiğini öğren. |

[**Komutlar ve Kontroller**](Commands-and-Controls-TR) · [**SSS**](FAQ-TR) · [**Değişiklik Geçmişi**](Changelog-TR)

---

## Forever Mini Reminder neler yapıyor?

| | Özellik | Ne sunuyor? |
|---|---|---|
| 🔔 | [**Akıllı Hatırlatmalar**](Smart-Reminders-TR) | Eksik sınıf etkileri, kaynaklar, süreler, yükler ve hazırlık durumları için bağlama göre uyarılar. |
| ☠️ | [**Aktif DoT Takibi**](Active-DoTs-TR) | Desteklenen DoT etkilerini düşmana göre gruplar; isteğe bağlı kalan hasar tahmini gösterir. |
| 🎯 | [**Savaş Göstergeleri**](Combo-Points-TR) | Combo puanları ile desteklenen Charge, Intercept ve Feral Charge isim plakası göstergeleri. |
| 🧪 | [**Tüketilebilirler**](Professions-and-Consumables-TR) | Çantaya göre silah güçlendirmeleri, elixir, flask, Well Fed yiyecekleri ve kamp etkisi hatırlatmaları. |
| 🗺️ | [**Dünya Haritası Rehberi**](World-Map-Guide-TR) | Arazi gösterimi, seviye aralıkları, geçişler, ulaşım rotaları, uçuş noktaları ve instance giriş/haritaları. |
| 🌦️ | [**Çevre Göstergeleri**](Environment-HUD-TR) | Sunucu saati, hava durumu bilgisi, modellenen sıcaklıklar ve ayrı su/nefes göstergesi. |
| 🎒 | [**Çanta Çubuğu**](Bag-Bar-TR) | Oyunun çanta düğmelerinde boş/toplam yuva ve Hunter cephane sayaçları. |
| 🎮 | [**Mini Oyunlar ve AFK**](Mini-Games-and-AFK-TR) | Uçuş noktaları arasında iki mini oyun ve ırk temalı dekoratif AFK sahneleri. |

Addon arayüzünde hem **İngilizce hem Türkçe metinler** bulunur. Gerekli yerlerde büyü ve eşya adları oyun istemcisini izler.

---

## Sınıf rehberleri

Karakterinde nelerin desteklendiğini net görebilmen için sınıfa özel ayarlar ve hatırlatmalar ayrı ayrı belgelenmiştir.

| [**Shaman**](Shaman-TR) | [**Mage**](Mage-TR) | [**Warrior**](Warrior-TR) |
|---|---|---|
| [**Hunter**](Hunter-TR) | [**Paladin**](Paladin-TR) | [**Priest**](Priest-TR) |
| [**Rogue**](Rogue-TR) | [**Druid**](Druid-TR) | [**Warlock**](Warlock-TR) |

[**Tüm Sınıf Rehberlerini aç →**](Class-Guides-TR)

---

## Hızlı kurulum

1. **`ForeverShamanReminder`** klasörünü adını değiştirmeden kur.
2. Oyunda minimap düğmesine sol tıkla veya **`/fsrsettings`** yaz.
3. O karakter için istediğin hatırlatma ve yardımcı özellikleri etkinleştir.
4. **Large / Compact** düzenini seç; ardından göstergeleri yerleştirmek için **Move / Lock** kullan.

Sınıf ve tüketilebilir tercihleri karaktere özeldir. Genel görünüm ve yardımcı özellik ayarları belgelerde belirtildiği şekilde ortaktır.

---

## Ne kadar bilgi görmek istediğini sen seç

Forever Mini Reminder'ın amacı sürekli ekranda gürültü oluşturmak değil, **duruma göre** bilgi göstermektir. Hazırlık uyarılarını binekteyken, dinlenme alanlarında veya ölü/hayalet durumunda gizleyebilirsin. Aktif süreler, DoT'lar, çanta bilgileri ve dünya yardımcıları ilgili oldukları sürece görünür kalabilir.

Addon **rotasyon yönlendirmesi yapmaz**, büyüleri otomatik kullanmaz ve eşyaları otomatik tüketmez.

[**Görünüm ve Düzenler →**](Appearance-and-Themes-TR) · [**Uyumluluk ve Sınırlamalar →**](Compatibility-and-Limitations-TR)

---

## Yardım veya katkı

- 🛠️ [**Sorun Giderme**](Troubleshooting-TR)
- 🐞 [**Hata Bildirimi**](Reporting-Bugs-TR)
- 💡 [**Özellik Önerileri**](Feature-Requests-TR)
- 📝 [**Değişiklik Geçmişi**](Changelog-TR)
- 📚 [**Katkılar ve Belge Kaynakları**](Credits-and-Sources-TR)

---

<details>
<summary><strong>Belge kapsamı ve teknik notlar</strong></summary>

Bu Wiki, sağlanan **1.19.4 sürüm paketini** belgeler. Planlanan veya yalnızca geliştirme sürümünde bulunan özellikler yayımlanmış işlev gibi anlatılmaz.

Bu sürüm **Large** ve **Compact** hatırlatma düzenleri, gruplu veya bağımsız yerleşim ve ortak hatırlatma ölçeği sunar. Seçilebilir bir **Modern / WoW Native** tema sistemi içermez.

Wiki dili, addonun oyun içi dilinden ayrıdır. Belge dili için her sayfanın üstündeki **EN / TR** bağlantılarını kullan. `/fsrlang en` ve `/fsrlang tr` ise addon arayüzünün dilini değiştirir.

**1.19.4 kaynak referansları:** `ForeverShamanReminder.toc:1–9`; `README.txt:12–57`; `README.txt:69–160`; `Settings.lua:15–148`.

</details>
