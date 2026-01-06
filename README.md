# WhatsApp Telefon Numarası Formatlayıcı

Türk telefon numaralarını formatlayan ve tarayıcınızdan doğrudan WhatsApp sohbetleri açan basit bir web uygulaması.

## 🌐 Canlı Demo

Canlı uygulamayı ziyaret edin: [https://leventkurt-stack.github.io/whatsapp-formatter/](https://leventkurt-stack.github.io/whatsapp-formatter/)

## ✨ Özellikler

- **Otomatik Formatlama**: Türk telefon numaralarını uluslararası formata (+90) dönüştürür
- **Çoklu Giriş Formatları**: Çeşitli giriş desenlerini destekler:
  - 10 haneli numaralar (5551234567) → +905551234567
  - Başında 0 olan 11 haneli (05551234567) → +905551234567
  - 90 ile başlayan 12 haneli (905551234567) → +905551234567
  - 90 ile başlayan 13 haneli (9005551234567) → +9005551234567
- **Giriş Doğrulama**: Sadece rakamlar, +, (), ve boşluklara izin verir
- **Gerçek Zamanlı Önizleme**: Yazarken formatlanmış numarayı görün
- **Doğrudan WhatsApp Entegrasyonu**: Tek tıkla WhatsApp sohbeti açar

## 🚀 Kullanım

1. Desteklenen herhangi bir formatta telefon numarası girin
2. Formatlanmış numara giriş alanının altında görünür
3. Bu numarayla WhatsApp sohbeti açmak için "Gönder"e tıklayın

## 💻 Teknoloji

- Saf HTML, CSS ve JavaScript
- Bağımlılık veya framework gerektirmez
- Masaüstü ve mobil tarayıcılarda çalışır
- Mobil öncelikli tasarım
- PWA (Progressive Web App) desteği

## 📝 Nasıl Çalışır

Uygulama, sohbet açmak için WhatsApp `wa.me` API'sini kullanır. Formatlanmış bir telefon numarası gönderdiğinizde, `https://wa.me/[numara]` adresine yönlendirir ve bu da WhatsApp Web'i (masaüstü) veya WhatsApp uygulamasını (mobil) açar.

## 🤝 Katkıda Bulunma

Bu depoyu çatallamak ve iyileştirmeler için çekme istekleri göndermek için çekinmeyin.

## 📄 Lisans

Bu proje açık kaynaklıdır ve herkesin kullanması ve değiştirmesi için mevcuttur.
