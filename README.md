# 🐟 Knox Fishing System

Bu sistem **Knox Development** tarafından hazırlanmıştır.

Orta ölçekli roleplay sunucuları için geliştirilmiş, **QB-Core uyumlu balıkçılık sistemidir**.

---

## ⚙️ Sistem Özellikleri

- QB-Core framework uyumlu
- QB Inventory destekli
- Target sistemi kullanılmaz (tamamen E tuşu ile etkileşim)
- 2 adet NPC sistemi (malzeme & satış)
- Tek balık türü sistemi (`fish`)
- Yem bazlı balık tutma mekaniği
- Minigame tabanlı balık yakalama sistemi
- Server-side güvenlik kontrolleri

---

## 🎣 Oynanış Mantığı

Oyuncular balık tutabilmek için öncelikle NPC üzerinden olta ve balık yemi temin eder.

Balık tutma süreci şu şekilde ilerler:

- Oyuncu oltayı kullanır
- Yem kontrolü yapılır
- Balık oltaya takıldığında bildirim gelir
- Kısa bir bekleme süresi sonrası minigame başlar
- Doğru zamanda E tuşuna basılırsa balık yakalanır
- Başarısız olunursa yem kaybedilir

---

## 💰 Ekonomi Sistemi

Balık satış fiyatı tamamen config üzerinden ayarlanabilir.

- 1 balık = Config üzerinden belirlenen fiyat
- Tüm satış işlemleri server-side olarak gerçekleştirilir

---

## 🔐 Güvenlik

- Tüm item işlemleri server tarafında kontrol edilir
- Yem ve balık doğrulamaları exploit önleyici şekilde yapılmıştır
- Event spam koruması bulunmaktadır

---

## 📦 Kurulum

Script, resources klasörüne eklenerek kolayca aktif edilebilir ve server.cfg üzerinden başlatılır.

---

## 🧾 Notlar

- Sistem tamamen özelleştirilebilir yapıdadır
- NPC koordinatları config üzerinden ayarlanır
- Debug modu ile test komutları aktif edilebilir

---

## 🏷️ Yapım

Bu script:

**Knox Development tarafından geliştirilmiştir.**
