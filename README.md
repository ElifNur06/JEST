# JEST: Kişisel Hediye Asistanı 🎁✨

JEST, sevdiklerinize en mükemmel hediyeyi bulmanıza yardımcı olan, yapay zeka destekli kapsamlı bir hediye asistanıdır. Hediye arayışını bir stresten keyifli bir deneyime dönüştürür; özel günlerinizi takip eder, bütçenizi yönetir ve hediye seçiminde kararsız kaldığınız anlarda size rehberlik eder.

## 🚀 Temel Modüller

- **Kahin (Hediye Bulucu):** `Google Gemini 2.0 Flash API` kullanarak sevdiklerinizin yaş, ilgi alanı ve ilişki durumuna göre kişiselleştirilmiş hediye önerileri üretir ve duygusal hediye notları tasarlar.
- **Ajanda (Planlayıcı):** `flutter_local_notifications` ile özel günleri hatırlatır. Tarihsel kayıt sistemi ile geçmişte ne hediye aldığınızı unutmazsınız.
- **Atölye (Araçlar):**
  - **Dedektif Modu:** Ürün barkodlarını tarayarak veya görsel analizi yaparak ürün detaylarını inceler.
  - **Hediye Çarkı:** Kararsız anlar için şans bazlı, eğlenceli hediye seçim aracı (`flutter_fortune_wheel`).
  - **Bütçe Analizi:** Hediye harcamalarınızı `fl_chart` ile görselleştirir ve bütçe takibi yapmanızı sağlar.

## 🛠 Teknik Altyapı (Tech Stack)

| Kategori | Teknoloji / Kütüphane |
| :--- | :--- |
| **Framework** | Flutter (Dart) |
| **Yapay Zeka** | Google Gemini API (gemini-2.5-flash) |
| **Barkod & Görsel** | Mobile Scanner, Image Picker |
| **Görselleştirme** | FL Chart (Grafik Analiz) |
| **İnteraktif Araçlar** | Flutter Fortune Wheel |
| **Bildirimler** | Flutter Local Notifications |
| **Veri Kalıcılığı** | SharedPreferences |

## Görseller
<img width="334" height="598" alt="image" src="https://github.com/user-attachments/assets/c2eab3a5-def0-4d33-9dcd-9301110052e0" />
<img width="333" height="598" alt="image" src="https://github.com/user-attachments/assets/2d39093e-7949-4c90-9466-92fc0720a257" />
<img width="338" height="597" alt="image" src="https://github.com/user-attachments/assets/39e101a6-aee5-4ae2-9c76-ae6de357b3c4" />
<img width="338" height="597" alt="image" src="https://github.com/user-attachments/assets/26a7be55-112b-492e-84a8-753394e1c2e0" />
<img width="336" height="593" alt="image" src="https://github.com/user-attachments/assets/3969a590-8088-4507-9d01-9adf9687a0f9" />
<img width="340" height="595" alt="image" src="https://github.com/user-attachments/assets/8eaaa481-5001-49f5-8a3c-9ac59c2d3cb5" />
<img width="330" height="591" alt="image" src="https://github.com/user-attachments/assets/018234a3-4649-4dd0-874c-44076b31d961" />
<img width="338" height="596" alt="image" src="https://github.com/user-attachments/assets/f5b89239-bd5c-4ba3-89d5-aa9614860b93" />
<img width="334" height="597" alt="image" src="https://github.com/user-attachments/assets/38c2663f-f9ce-4ccc-88d7-8ebcd5d30ff9" />
<img width="338" height="596" alt="image" src="https://github.com/user-attachments/assets/345e703a-070b-491b-9bbc-d3dcd3f8be94" />
<img width="336" height="600" alt="image" src="https://github.com/user-attachments/assets/412dd33c-6079-449d-9967-997ad518449f" />
<img width="338" height="594" alt="image" src="https://github.com/user-attachments/assets/b96efdef-0a60-4edf-8597-cf9e0a918eab" />
<img width="334" height="594" alt="image" src="https://github.com/user-attachments/assets/a5fbc33c-f02c-4371-b1d4-e7b13a033340" />
<img width="337" height="598" alt="image" src="https://github.com/user-attachments/assets/9170831d-a14f-44a2-88bb-6758d44ef130" />
<img width="340" height="593" alt="image" src="https://github.com/user-attachments/assets/bc9796e2-3d70-4d0c-a5c5-187007150eb4" />
<img width="334" height="601" alt="image" src="https://github.com/user-attachments/assets/4a636f51-60b0-4467-b918-583c317681ad" />
<img width="337" height="596" alt="image" src="https://github.com/user-attachments/assets/1a2d910c-9c7a-4eb5-b224-6a70032b0c35" />


## 🧠 Sistem Mimarisi
Veri Akışı: Kullanıcı profilleri, özel gün notları ve harcama verileri SharedPreferences ile yerel ve hızlı bir şekilde saklanır.

AI Entegrasyonu: Gemini API ile kurulan dinamik köprü sayesinde, girdiğiniz veriler (bütçe, ilgi alanı) analiz edilerek hediye önerisine dönüştürülür.

Bildirim Yönetimi: timezone kütüphanesi ile optimize edilmiş, zaman dilimine duyarlı hatırlatma motoru.

JEST - Sevdiklerinize Bir Jest Yapın.
