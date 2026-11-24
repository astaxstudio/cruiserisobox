<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=CruiserIsoBox&fontSize=60&fontColor=ffffff&animation=fadeIn&desc=ISO%27lar%C4%B1n%C4%B1%20yan%C4%B1nda%20gezdir&descSize=20&descAlignY=72" alt="CruiserIsoBox" />

### 🚢 Tek USB. Sınırsız ISO. Tek menü.

[![Lisans: GPLv3](https://img.shields.io/badge/Lisans-GPLv3-blue?style=for-the-badge&logo=gnu&logoColor=white)](LICENSE)
[![Sürüm](https://img.shields.io/github/v/release/KULLANICIADI/cruiser-isobox?style=for-the-badge&color=ff6b35&label=S%C3%BCr%C3%BCm)](https://github.com/KULLANICIADI/cruiser-isobox/releases)
[![İndirme](https://img.shields.io/github/downloads/KULLANICIADI/cruiser-isobox/total?style=for-the-badge&color=2ecc71&label=%C4%B0ndirme)](https://github.com/KULLANICIADI/cruiser-isobox/releases)
[![Yıldız](https://img.shields.io/github/stars/KULLANICIADI/cruiser-isobox?style=for-the-badge&color=f1c40f)](https://github.com/KULLANICIADI/cruiser-isobox/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PR-Kabul%20Edilir-ff69b4?style=for-the-badge)](CONTRIBUTING.md)

**[⬇️ İndir](https://github.com/KULLANICIADI/cruiser-isobox/releases)** •
**[📖 Kullanım](#-nasıl-kullanılır)** •
**[🐛 Hata Bildir](https://github.com/KULLANICIADI/cruiser-isobox/issues)** •
**[💬 Fikir Öner](https://github.com/KULLANICIADI/cruiser-isobox/discussions)**

</div>

---

## 🎯 Nedir?

**CruiserIsoBox**, USB belleğini çoklu boot aracına çeviren açık kaynaklı bir projedir.
ISO dosyalarını belleğe kopyalarsın, bilgisayarı o bellekten açarsın, menüden istediğini seçersin.
**Her ISO için belleği yeniden formatlamak yok.** 🎉

> 💡 Rufus'un kolaylığı + Ventoy'un çoklu boot gücü, tek araçta.

## 🌈 Neden CruiserIsoBox?

| | 🔴 Klasik yöntem | 🟢 CruiserIsoBox |
|---|---|---|
| **Birden fazla ISO** | Her seferinde yeniden yaz | Hepsini yan yana koy |
| **Ayarlar** | Elle uğraş | ISO başına hazır profil |
| **Bellek verisi** | Format = hepsi silinir | Normal depolama olarak da kullan |
| **Arayüz** | Karmaşık ya da komut satırı | Sade ve renkli |

## ✨ Özellikler

- 📦 **Çoklu boot:** Tek USB'de birden fazla ISO
- 🎛️ **ISO başına profil:** Örneğin Windows 11 için TPM atlama, Linux için kalıcı depolama
- 🔥 **Tek ISO yazma modu:** Klasik Rufus tarzı yazma
- 🌐 **Dahili ISO indirici:** Dağıtımı seç, doğrudan belleğe indir
- 🩺 **USB sağlık raporu:** Hız testi, bad block, gerçek kapasite
- 🔄 **Güvenli güncelleme:** Verilerine dokunmadan

> ⚠️ **Durum:** Proje erken aşamada. Yukarıdaki özelliklerin hepsi hazır değil.
> Güncel durum için [Yol Haritası](#️-yol-haritası) bölümüne bak.

## 🧭 Nasıl çalışır?

```mermaid
flowchart LR
    A[💾 USB'yi tak] --> B[🛠️ CruiserIsoBox'ı kur]
    B --> C[📂 ISO'ları kopyala]
    C --> D[🔌 Bilgisayarı USB'den aç]
    D --> E[🎯 Menüden ISO seç]
    E --> F[🚀 Çalıştır!]
```

## 🚀 Nasıl kullanılır?

1. **[Releases](https://github.com/KULLANICIADI/cruiser-isobox/releases)** sayfasından son sürümü indir
2. Uygulamayı aç, USB belleğini seç
3. **Kur**'a bas (bellek bir kez hazırlanır)
4. ISO dosyalarını belleğe kopyala
5. Bilgisayarı yeniden başlat, USB'den aç, ISO'nu seç 🎉

<details>
<summary>🐧 Linux için</summary>

Kurulum adımları buraya gelecek.

</details>

<details>
<summary>🪟 Windows için</summary>

Kurulum adımları buraya gelecek.

</details>

## 🗺️ Yol Haritası

- [ ] 🔧 Temel USB hazırlama
- [ ] 📦 Çoklu ISO boot menüsü
- [ ] 🎛️ ISO başına profil sistemi
- [ ] 🌐 ISO indirici
- [ ] 🩺 USB sağlık raporu
- [ ] 🎨 Özelleştirilebilir boot menüsü teması
- [ ] 🌍 Çoklu dil desteği (Türkçe, İngilizce)

## 🤝 Katkıda bulun

Her türlü katkı değerli! Kod, hata raporu, çeviri, logo ya da fikir, hepsi hoş geldi.
Başlamak için **[CONTRIBUTING.md](CONTRIBUTING.md)** dosyasına bak.

⭐ Projeyi beğendiysen **yıldız vermeyi** unutma, başkalarının da bulmasına yardım eder!

## 📣 Duyur

Arkadaşlarına, forumlara, topluluklara anlat. Küçük bir paylaşım bile projeyi büyütür:

> 🚢 **CruiserIsoBox**: Tek USB'ye bir sürü ISO koy, açılışta menüden seç.
> Açık kaynak, ücretsiz, renkli! 👉 github.com/KULLANICIADI/cruiser-isobox

## 📜 Lisans

Bu proje **GNU GPLv3** lisansı altındadır. Ayrıntılar için [LICENSE](LICENSE) dosyasına bak.

## ℹ️ Not

CruiserIsoBox, Rufus ve Ventoy'dan esinlenmiş bağımsız bir projedir. Bu projelerle, ayrıca SanDisk ya da başka bir markayla resmi bir bağlantısı yoktur.

---

<div align="center">

**Sevgiyle yapıldı 💙 | ISO'larını yanında gezdir 🚢**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" alt="" />

</div>
