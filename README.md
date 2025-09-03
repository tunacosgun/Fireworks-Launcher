<h1 align="center">🎆 Fireworks Launcher</h1>

<p align="center">
  <em>Canvas üzerinde dinamik havai fişek simülasyonu — mouse/touch ile top at, parçacıklar patlasın!</em>
</p>

<p align="center">
  <img src="screenshot.png" width="600" alt="Fireworks Launcher Preview">
</p>

---

## ✨ Özellikler

- 🧨 **Gerçek zamanlı parçacık patlamaları** (Canvas 2D)
- 🖱️ **Mouse & Touch kontrolü** — hedefe nişan al, basılı tut, seri atış yap
- 🎞️ **İz ve parıltı efektleri** — yarı saydam kaplama ile motion‑trail
- ⚙️ **Hafif ve bağımsız** — saf HTML + CSS + JS (framework yok)
- 📱 **Responsive** — tam ekran, mobil/masaüstü uyumlu

---

## 🚀 Hızlı Başlangıç

```bash
# Klonla
git clone https://github.com/tunacosgun/fireworks-launcher.git
cd fireworks-launcher

# Çalıştır
# Sadece index.html dosyasını tarayıcıda açman yeterli
```

> Not: Dosyayı doğrudan çift tıklayarak açabilir veya basit bir statik sunucu ile servis edebilirsin.

---

## 📁 Dosya Yapısı

```
fireworks-launcher/
├── index.html        # Canvas, animasyon, etkileşim
├── screenshot.png    # README için önizleme görseli (opsiyonel)
└── README.md
```

---

## 🧩 Nasıl Çalışır?

- `Cannon` (top) mouse imlecine göre açı hesaplar (`atan2`)
- `Cannonball` mermileri hız vektörü ile hareket eder, yaşam süresi sonunda **Explosion** tetikler
- `Explosion` birden çok `Particle` üretir; geri sekme ve ekran sınırı çarpışmaları basit kurallarla simüle edilir
- Arka plan iz efekti için her karede yarı saydam bir dikdörtgen çizilir

---

## 🎨 Özelleştirme İpuçları

- `colors` dizisini düzenleyerek mermi/parçacık renk paletlerini değiştir
- `gravity`, hız ve `timeToLive` değerleri ile fizik hissini ayarla
- Mobil için `touchmove` dinleyicisinde hassasiyeti artır
- Arkaplan ve tipografi için `<style>` bölümünü dilediğin gibi güncelle

---

## 🖼️ Demo GIF (Opsiyonel)

Ekran kaydı alıp GIF’e çevirerek projeye ekleyebilirsin:

```markdown
![Fireworks Demo](demo.gif)
```

---

## 🧑‍💻 Geliştirici

**Tunahan Coşgun**  
🌐 <a href="https://github.com/tunacosgun">github.com/tunacosgun</a>

---

<div align="center">
  <sub>© Fireworks Launcher — HTML/CSS/JS • Canvas 2D</sub>
</div>
