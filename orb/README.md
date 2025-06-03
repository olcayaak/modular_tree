# Orb - Kişisel AI Yönetici Asistan Uygulaması

Orb, girişimciler ve üretken bireyler için geliştirilen GPT-4.1 destekli mobil
asistan uygulamasıdır. Uygulama, sesli ve yazılı olarak etkileşime geçilebilen
bir "orb" arayüzü sunar ve kullanıcıların günlük hedeflerini takip etmelerine,
zamanlarını verimli kullanmalarına yardımcı olur.

## Özellikler
- **Kişisel bağlam**: Kullanıcı hedefleri ve motivasyonunu hafızada tutar.
- **Görev ve Takvim Senkronizasyonu**: Google Calendar API entegrasyonu ile
görev hatırlatmaları.
- **Günlük Diyalog Şablonları**: Sabah, öğlen ve akşam motivasyon soruları.
- **Bildirim Sistemi**: Push bildirimleri ve dinamik hatırlatmalar.
- **Premium Model**: 7 gün ücretsiz kullanım ardından abonelik seçeneği.

## Teknik Mimarisi
- Mobil: **React Native** (örn. Expo)
- Backend: **Supabase**
- AI: **OpenAI GPT-4.1 Assistants API**
- Kimlik Doğrulama: **Firebase Auth**
- Bildirimler: **OneSignal**

Uygulamanın temel bileşenleri `App.js` içinde örnek bir orb arayüzü ile
başlatılmıştır. Geliştirmeye buradan devam edebilirsiniz.
