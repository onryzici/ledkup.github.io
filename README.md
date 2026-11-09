# LED Küp Simülatörü

İç yüzeyleri HUB75 LED panel olan, önü açık bir küpün tarayıcıda çalışan 3B simülasyonu.

**Canlı:** https://onryzici.github.io/ledkup.github.io/

- Video / GIF oynatma: tek kaynak (kesintisiz açılım, her yüzde aynı, panorama) ya da her panele ayrı dosya
- Elektronik görünüm: paneller, Raspberry Pi Zero 2 W, HUB75 sürücü kartı, 5 V 20 A güç kaynağı, kablolar
- Canlı akım/güç tahmini, PWM bit ve parlaklık ayarı
- Malzeme listesi, bağlantı şeması, ffmpeg ve `rpi-rgb-led-matrix` komutları

Donanım (Türkiye): 10× P5 iç mekan 320×160 modül (64×32, HUB75), iki modül bir yüz, U-mapper ile tek zincir (320×64), Pi Zero 2 W + 74HCT245 adaptör, 5 V 40 A. Yaklaşık 14.400 TL.

Tek dosya: `index.html` (three.js 0.160, CDN'den). Yerelde açmak için bir statik sunucu yeterli, örn. `npx serve .`
