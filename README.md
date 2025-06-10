## 🌌 About the Project

At its core, the app offers users the opportunity to choose from three iconic Mars Rovers – Curiosity, Opportunity and Spirit – each with their own unique mission history and explorations. Once a rover is selected, users can delve into a large collection of views captured on the Martian surface, including landscapes, geological formations, and snapshots of the rover's journey across the Martian landscape

## 🎯 Purpose & Problem Solved

- Space data is often technical and difficult for the average user to access and understand.  
- This project simplifies and visualizes NASA’s data to provide an intuitive way to explore space information.  
- It aims to inspire users with up-to-date, meaningful space content presented in an educational and enjoyable manner.  
- Utilizes APIs to provide real-time and dynamic data updates.



Used technologies :

In this project, Spring Boot acts as the backbone that performs important functions such as HTTP requests, data processing, and response processing. Spring's powerful Inversion of Control (IoC) container and application architecture using dependency injection enable seamless integration with external APIs such as NASA's Rover API. NASA's Mars Rover API: The project's primary data source, the API provides access to images and information captured by NASA's Mars rovers.

Thymeleaf : Thymeleaf acts as a templating engine that allows HTML pages to be dynamically rendered with data from the API.

Bootstrap: Bootstrap enhances the user interface by providing responsive design elements and components for a polished user experience.

Main Features:

Selection of Mars Rovers: Users can choose from NASA's three active Mars rovers (Curiosity, Opportunity, and Spirit), each offering a unique perspective on the Martian landscape.

Viewing Mars Images: The app allows users to explore the Martian terrain and geological features by displaying a gallery of stunning images captured by the selected rover.

Filtering Images: By filtering images by various criteria, such as sol (Mars day) and camera type, users can narrow their search and focus on specific areas of interest.

Interactive User Interface: The user interface is designed to be intuitive and user-friendly, providing seamless navigation and an immersive experience.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
## 🌌 Proje Hakkında
Uygulama özünde kullanıcılara, her birinin kendine özgü görev geçmişi ve keşifleri olan üç ikonik Mars Rover'ı (Curiosity, Opportunity ve Spirit) arasından seçim yapma fırsatı sunuyor. Bir gezici seçildikten sonra kullanıcılar,
Mars yüzeyinde çekilen geniş manzara koleksiyonunu, manzaraları, jeolojik oluşumları ve gezicinin Mars arazisindeki yolculuğuna dair anlık görüntüleri derinlemesine inceleyebiliyor

## 🎯 Amaç & Çözüm

- Uzay verileri genellikle teknik ve karmaşık kaynaklarda bulunur.  
- Kullanıcıların bu verilere kolayca erişmesini sağlamak, görsel ve anlaşılır biçimde sunmak.  
- Uzayla ilgili bilgileri hem eğlenceli hem de öğretici bir şekilde paylaşmak.  
- API kullanımıyla gerçek zamanlı ve dinamik veri sunmak.

---

## ⚙️ Özellikler

- NASA’nın Astronomy Picture of the Day (APOD) verilerini gösterir.  
- Mars Rover fotoğraflarını listeler ve detaylı inceleme imkanı sağlar.  
- React.js ve Next.js kullanılarak oluşturulmuş hızlı ve modern bir frontend.  
- Tailwind CSS ile responsive ve şık tasarım.  
- Axios & SWR ile API çağrıları ve önbellekleme yönetimi.  
- Mobil ve masaüstü uyumlu arayüz.
-Mars Görüntülerini Görüntüleme : Uygulama, seçilen gezici tarafından çekilen çarpıcı görüntülerden oluşan bir galeri görüntüleyerek kullanıcıların Mars arazisini ve jeolojik özelliklerini keşfetmesine olanak tanır.
-Görüntüleri Filtreleme : Kullanıcılar, görüntüleri sol (Mars günü) ve kamera türü gibi çeşitli kriterlere göre filtreleyerek aramalarını daraltabilir ve belirli ilgi alanlarına odaklanabilirler.

## 🛠 Teknoloji Yığını (Tech Stack)

| Katman          | Teknoloji/ Araçlar              |
|-----------------|-------------------------------|
| Frontend        | React.js, Next.js             |
| Stil & Tasarım  | Tailwind CSS                  |
| Veri Yönetimi   | Axios, SWR                   |
| API             | NASA Open APIs                |
| Dağıtım (Opsiyonel) | Vercel / Netlify            |

---
## 🚀 Kurulum & Çalıştırma

1. Depoyu klonla:

```bash
git clone https://github.com/devsukransinci/nasa_project.git
2 Bağımlılıkları yükle:
cd nasa_project
3 Projeyi geliştirme modunda başlat:
npm run dev
4 Tarayıcını aç ve http://localhost:3000 adresine git.
 Proje Yapısı
nasa_project/
 ├── components/       # React bileşenleri
 ├── pages/            # Next.js sayfaları
 ├── public/           # Statik dosyalar, resimler
 ├── styles/           # Tailwind CSS ve global stiller
 ├── utils/            # API çağrıları ve yardımcı fonksiyonlar
 └── README.md
🎓 Öğrendiklerim & Geliştirme Süreci
NASA Open API’lerini etkin kullanma ve veri yönetimi.

React ve Next.js ile performans odaklı SPA geliştirme.

Tailwind CSS ile hızlı ve modern tasarım uygulaması.

SWR kütüphanesi ile veri önbellekleme ve otomatik yenileme.

Responsive tasarım ile tüm cihazlarda uyumlu kullanıcı deneyimi.

API sınırlandırmaları ve hata yönetimi üzerine pratik çözümler.
