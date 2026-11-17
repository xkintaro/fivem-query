<a href="README.md">
  <img src="https://img.shields.io/badge/Language-English-blue?style=flat-square&logo=google-translate&logoColor=white" alt="English">
</a>
<a href="README-TR.md">
  <img src="https://img.shields.io/badge/Language-Türkçe-red?style=flat-square&logo=google-translate&logoColor=white" alt="Türkçe">
</a>

  <br />
  <br />

<div align="center">
  <img src="frontend/public/mascot.png" width="120" height="120" />
  <br />
  <br />

  <p>
     FiveM sunucularındaki oyuncuları sorgulayıp filtrelemenizi sağlayan bir web aracı.
  </p>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

  <p>
    <a href="#warning">Uyarı</a> •
    <a href="#about">Hakkında</a> •
    <a href="#features">Özellikler</a> •
    <a href="#tech">Teknolojiler</a> •
    <a href="#setup">Kurulum</a> •
    <a href="#gallery">Galeri</a> •
    <a href="#license">Lisans</a>
  </p>

  <br />
  <br />
</div>

## <a id="warning"></a> ⚠️ Uyarı

Bu proje daha önce **Aether FiveM** adıyla yayınlanıyordu. Ne işe yaradığını daha iyi anlatması için adı **FiveM Query** olarak değiştirildi. Bu değişiklikle birlikte Aether logosu kaldırıldı, yeni logo giriş ekranında ve favicon olarak kullanılmaya başlandı, gezinme çubuğundaki logo da kaldırıldı. Galerideki ekran görüntüleri hâlâ eski adı ve logoyu gösteriyor.

## <a id="about"></a> 📋 Hakkında

**FiveM Query**, bir FiveM sunucusuna bağlı tüm oyuncuları listeleyen bir web aracıdır. Sunucunun `players.json` adresini girin, araç kendi backend'i üzerinden anlık oyuncu listesini çeksin. Her oyuncu adı, sunucu ID'si ve ping değeriyle gösterilir.

Bir oyuncuya tıklayarak Steam, Discord, Rockstar lisansı, Xbox Live ve FiveM gibi tüm kimliklerini görebilirsiniz. Kalabalık sunucularda aradığınız oyuncuyu hızlıca bulmak için listeyi ada, ID'ye, Steam'e veya Discord'a göre filtreleyin.

## <a id="features"></a> ✨ Özellikler

- **Sunucu sorgulama**: Sunucunun `players.json` adresini girerek anlık oyuncu listesini çekin.
- **Oyuncu listesi**: Her oyuncunun adını, sunucu ID'sini ve ping değerini görün. Ping, gecikmeye göre yeşil, sarı veya kırmızı renkte gösterilir.
- **Oyuncu detayları**: Bir oyuncuya tıklayarak bağlantı adresini, ping değerini ve türüne göre renklendirilmiş tüm kimliklerini görün.
- **Birlikte çalışan filtreler**: Oyuncu adı, ID, Steam ID ve Discord ID ile aynı anda arama yapın, tüm filtreleri tek tıkla temizleyin.
- **İstatistikler**: Toplam oyuncu sayısını, filtrelere uyan oyuncu sayısını ve ortalama ping değerini tek bakışta görün.
- **Yeni sorgu**: Sayfayı yenilemeden sonuçları temizleyin ve başka bir sunucuyu sorgulayın.

## <a id="tech"></a> 🛠️ Teknolojiler

`React` · `Vite` · `Tailwind CSS` · `Node.js` · `Express`

## <a id="setup"></a> 🚀 Kurulum

### Gereksinimler

- **Node.js**

### Adım Adım Kurulum

1. **Depoyu klonlayın**

   ```bash
   git clone https://github.com/xkintaro/fivem-query.git
   cd fivem-query
   ```

2. **Bağımlılıkları yükleyin**

   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. **Backend sunucusunu başlatın**

   ```bash
   cd backend
   node index.js
   ```

   Backend `http://localhost:5000` adresinde çalışır.

4. **Geliştirme sunucusunu başlatın**

   Yeni bir terminalde:

   ```bash
   cd frontend
   npm run dev
   ```

Uygulamayı şu adreste açın: [http://localhost:5173](http://localhost:5173). Ardından bir FiveM sunucusunun adresini `http://ip:port/players.json` biçiminde girin.

## <a id="gallery"></a> 🖼️ Galeri

<img src="frontend/public/md/20260227203204299.jpg" width="100%" />

<img src="frontend/public/md/20260227203204081.jpg" width="100%" />

<img src="frontend/public/md/20260227203204191.jpg" width="100%" />

## <a id="license"></a> 📄 Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakabilirsiniz.

#

<p align="center">
  <sub>❤️ Developed by "Mustafa TAŞAL" (kintaro)</sub>
</p>
