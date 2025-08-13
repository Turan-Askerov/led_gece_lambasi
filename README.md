
# Fotorezistör ile Gece Lambası Devresi

Bu projede, ortamdaki ışık seviyesini algılayan basit bir gece lambası devresi tasarlandı. Devre, karanlık ortamda LED'in otomatik olarak yanmasını sağlar. Böylece gece lambası gibi çalışır.

## 🧰 Kullanılan Malzemeler
- 1x LED (mavi)
- 1x Fotorezistör (LDR)
- 1x NPN Transistör (BC547B)
- 1x Anahtar (Rocker Switch)
- 2x 1.5V AA Pil + Pil yuvası
- 1x 1kΩ direnç
- 1x 10kΩ direnç
- Bağlantı kabloları ve zemin plakası

## 🔧 Devre Açıklaması

Fotorezistörün direnci ışığa bağlı olarak değişir. Ortam karardığında, LDR'nin direnci artar ve transistörün bazına giden voltaj seviyesi yükselir. Bu sayede transistör iletime geçer ve LED yanar. Ortam aydınlandığında LDR'nin direnci azalır ve transistör kesime girer, LED söner.

## ⚙️ Devre Şeması

Devre fiziksel olarak breadboard yerine doğrudan lehimlenerek tasarlandı. Şema henüz dijital ortamda çizilmedi. Aşağıda gerçek devre fotoğrafı yer almaktadır:

## Devre Fotoğrafı
images/IMG-20221107-WA0020.jpg


## 🧠 Tasarım ve Uygulama

Devre tamamen lehimleme yöntemiyle ve elle bağlantılar yapılarak hazırlandı. Şematik tasarım ve uygulama tarafı şahsen yapılmıştır.

---

**Not:** Proje KiCad gibi bir devre çizim aracıyla daha sonra dijitalleştirilip Gerber dosyaları üretilebilir.





