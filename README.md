
<p align="center">
  <img src="assets/logo-kopon.png" alt="KOPON Logo" width="200">
</p>

# KOPON: Hayatta Olduğumu Gösteren Cihaz

**KOPON**, afet anlarında, özellikle enkaz altında kalan bireylerin konum ve varlıklarını bildirebilmeleri için geliştirilen dijital sinyal sistemidir.

- 🧠 Geliştirici: Kaan Oral Polat
- 🤖 Destek: ChatGPT (OpenAI)
- 📟 Sistem: ESP32 + TFT + Wi-Fi + LED + Buzzer
- 🔊 Yardımcısı: **IZ** adlı tetikleyici cihaz

---

## 🔧 Sistem Bileşenleri

| Parça | Açıklama |
|-------|----------|
| **ESP32** | Ana sinyal alma, analiz ve görselleştirme |
| **TFT ILI9341** | Bilgileri ve uyarıları ekranda gösterir |
| **LED & Buzzer** | Sinyal geldiğinde sesli ve görsel uyarı |
| **IZ Cihazı (ESP8266 + Buton)** | Bireyin sinyal göndermek için kullandığı cihaz |

---

## 📸 Ekran Görselleri

<img src="assets/logo-kopon.png" width="200">
<img src="assets/logo-iz.png" width="100">

---

## 🛰️ Çalışma Prensibi

1. Birey, IZ cihazındaki butona basar.
2. Cihaz, aynı lokal ağ içinde KOPON sistemine sabit bir sinyal gönderir.
3. KOPON ekranında bireyin kimlik bilgileri (örneğin: İSİM ve TCKN) görsel olarak sunulur.
4. Sistemde **GPS veya canlı konum takibi bulunmaz**; ancak bireyin cihazı tanımlıdır.
5. Görsel blink efektleri ve 30 saniyelik geri sayım ekranı bulunur.

> 📍 Not: KOPON sistemi herhangi bir GPS modülü içermez.
> Sinyal alıcı cihaz sabittir ve lokasyon bilgisi fiziksel konuma göre tanımlanır.
> Bu sistemin amacı, bireyin **hayatta olduğunu bildirmesidir**, yer tespiti harici olarak yapılır.

---

## 💬 İletişim

📩 kopon@gmail.com

---

## 🛡️ Lisans ve Koruma

Bu proje bireysel amaçla geliştirilmiş, kamu yararına sunulmuştur.  
Tüm içerikler geliştiriciye aittir. İzinsiz kullanılamaz.

> **KOPON – Sessiz çığlığın sesi.**
