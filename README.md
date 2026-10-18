# 🛠️ Doguner Tweak Lab — Official iOS & CarPlay Tweaks

<p align="center">
  <img src="https://img.shields.io/badge/Platform-iOS%2014--15.8.x--16.x-blue?style=for-the-badge&logo=apple" alt="Platform" />
  <img src="https://img.shields.io/badge/Jailbreak-Dopamine%202%20Rootless-green?style=for-the-badge" alt="Dopamine" />
  <img src="https://img.shields.io/badge/License-100%25%20Free-emerald?style=for-the-badge" alt="Free" />
  <a href="https://aliciamaze.gumroad.com/l/doguner-tweak-lab">
    <img src="https://img.shields.io/badge/Support-Buy%20Me%20a%20Coffee-ff69b4?style=for-the-badge&logo=gumroad" alt="Gumroad" />
  </a>
</p>

Official APT package repository for **LongShot** (intelligent long screenshot stitcher) and **CarSplit** (CarPlay dual-app multitasking) tweaks for rootless iOS (`/var/jb`).

🌐 **Web Showcase:** [https://doguner1.github.io/repo/](https://doguner1.github.io/repo/)  
📦 **Add to Sileo / Zebra:** `https://doguner1.github.io/repo/`

---

## 📸 1. LongShot (v1.1.0)
Take seamless, high-resolution long / scrolling screenshots in any iOS application turn-by-turn with a single tap.

### 🖼️ Nasıl Çalışır? (2 Adımda Yakalama)

<p align="center">
  <img src="assets/longshot/longshot_prompt.png" alt="1. Tetikleme Kapsülü" width="34%" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/longshot/longshot_manual_hud.png" alt="2. Canlı İlerleme HUD" width="34%" />
</p>
<p align="center">
  <i>(1. Adım: Ekran Görüntüsü Alındığında Açılan Kapsül • 2. Adım: Canlı Dilim Sayacı ve Durdurma HUD'ı)</i>
</p>

### 📱 Çıktı & Özellikler

<table>
<tr>
<td width="38%" align="center" valign="top">
  <img src="assets/longshot/longshot_stitched_output.png" alt="LongShot Kesintisiz Dikey Çıktı" width="100%" />
  <br><b>✨ Birleştirilmiş Kesintisiz Çıktı (Long Shot)</b>
</td>
<td width="62%" valign="top">

### ✨ LongShot Özellikleri & Mimarisi
iOS uygulamalarında (Safari, Twitter/X, WhatsApp, Ayarlar, Reddit vb.) dikey olarak uzayan sayfaları tek dokunuşla kaydırarak tek bir kesintisiz uzun ekran görüntüsü halinde birleştiren akıllı dikişleme tweak'i.

* **🚀 Otomatik & Elle Modu:** 'Long Shot' ile tam otomatik veya 'Elle' ile adım adım kontrol.
* **🛑 Canlı Durdurma Kontrolü:** Sayfanın sonunu beklemek zorunda değilsiniz; 'Durdur' butonu ile istenilen yerde sonlandırıp tam o noktaya kadar sıfır beyaz boşlukla dikişler.
* **🖼️ iOS Küçük Ekranını Kapatma:** Sol alt köşedeki varsayılan ekran görüntüsü önizleme penceresini otomatik gizler, kapatıldığında anında eski haline döner.
* **⚡ Respring Butonu:** Ayarlar menüsünden ve gezinti çubuğundan tek dokunuşla hızlı SpringBoard yeniden başlatma.
* **💾 Galeriye Kaydet & Paylaş:** Doğrudan Fotoğraflar'a kaydeder ve yerel iOS Paylaşım sayfasını (`UIActivityViewController`) açar.
* **⚙️ Ayarlar & Teşhis Paneli:** Ayarlar uygulamasından tek tıkla Telegram üzerinden geliştiriciye log iletir.
* **🛡️ Sıfır Kilitlenme:** Güvenli çalışma zamanı kancalarıyla kilitlenme riski yoktur.

</td>
</tr>
</table>

---

## 🚗 2. CarSplit (v1.0.0-beta6)
True side-by-side multitasking on **Apple CarPlay**. Run any two bridged applications simultaneously on your vehicle's head unit display—such as **Google Maps** on one side and **YouTube / Music** on the other.

### 📸 Real In-Car Vehicle Verification

Verified and tested on actual CarPlay vehicle displays:

<p align="center">
  <img src="IMG_1188.PNG" alt="CarSplit - YouTube Music & Google Maps" width="48%" />
  &nbsp;
  <img src="IMG_1190.PNG" alt="CarSplit - Google Maps & YouTube Music" width="48%" />
</p>
<p align="center">
  <img src="IMG_1192.PNG" alt="CarSplit - DeepSeek AI & YouTube" width="48%" />
  &nbsp;
  <img src="demo1.png" alt="CarSplit - Google Maps & YouTube Premium" width="48%" />
</p>
<p align="center">
  <img src="demo2.png" alt="CarSplit - CarPlay Home Grid & Media" width="48%" />
</p>
<p align="center">
  <i>Authentic CarPlay Screenshots: YouTube Music + Google Maps, Swapped Layouts, DeepSeek AI Assistant + Media, and Home Grid Multitasking.</i>
</p>

* **🏎️ True Multitasking:** Both apps remain fully active with independent dual-touch controls.
* **⏱️ One-Tap Clock Switch:** Tap the CarPlay status bar clock to cycle split layouts instantly.
* **⚠️ Requirement:** Requires **CarBridge** ([Havoc Repo](https://havoc.app/package/carbridge) / [carbridge.app](https://carbridge.app)).
* **📱 Verified Hardware:** 100% tested and verified on iPhone 7 (`iPhone9,3` on iOS 15.8.8) in an actual vehicle.

---

## 📱 Hardware & Firmware Compatibility

| Device / Firmware | Status | Verification Details |
|---|---|---|
| **iPhone 7 (`iPhone9,3`) — iOS 15.8.8** | ✅ **VERIFIED & TESTED** | Tested and verified in real vehicle CarPlay head unit and on-device screenshot capture. |
| **Other iPhone Models (A10 - A16)** | 🧪 **Community Beta** | Universal fat binaries (`arm64` + `arm64e`) for Dopamine 2 rootless. |
| **iOS 14.0 – 15.8.x – 16.x** | 🧪 **Community Beta** | Full rootless `/var/jb` compatibility across modern iOS versions. |

---

## 📦 How to Add to Sileo / Zebra

1. Open **Sileo** or **Zebra**.
2. Go to **Sources** → **Add** (`+`).
3. Enter: `https://doguner1.github.io/repo/`
4. Search for `LongShot` or `CarSplit` and install!

---

## ☕ Support the Developer

All tweaks from Doguner Tweak Lab are **100% free** with zero paywalls, ads, or tracking. If you enjoy these tweaks and want to support ongoing research and test hardware:

👉 [**Buy Me a Coffee on Gumroad**](https://aliciamaze.gumroad.com/l/doguner-tweak-lab)

---

## 📄 License & Community Notice

Strictly **FREE Community Edition**. If you purchased this anywhere, you were scammed!
Report pirated distributions and download official `.deb` releases only from this repo.
