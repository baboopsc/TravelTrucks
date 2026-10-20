# TravelTrucks 

## Kısa Açıklama
TravelTrucks, karavan kiralama alanında faaliyet gösteren bir şirket için geliştirilmiş modern bir frontend web uygulamasıdır. Kullanıcılar ana sayfadan karavan kataloğuna erişebilir, çeşitli kriterlere göre (lokasyon, araç tipi, donanım vb.) karavanları filtreleyebilir, beğendikleri araçları favorilere ekleyebilir ve seçtikleri karavan için rezervasyon talebinde bulunabilirler.

## Temel Özellikler
* **Geniş Kapsamlı Katalog:** Backend API'sinden (MockAPI) çekilen karavan ilanlarının listelenmesi.
* **Gelişmiş Filtreleme:** Konum, araç tipi ve ek donanımlara (klima, mutfak, TV vb.) göre anlık filtreleme yapabilme.
* **Favori Sistemi:** Beğenilen karavanları favorilere ekleme özelliği (veriler sayfa yenilendiğinde kaybolmaması için Local Storage'da tutulur).
* **Sayfalandırma (Load More):** Katalog sayfasında "Load More" butonu ile ek ilanların yüklenmesi.
* **Detaylı İlan Görünümü:** Her karavan için özel fotoğraf galerisi, teknik detaylar (uzunluk, yakıt tüketimi vb.) ve 5 yıldızlı kullanıcı yorumları sistemi.
* **Rezervasyon Formu:** Kullanıcıların karavan detay sayfasından hızlıca rezervasyon yapabilmesi ve başarılı işlem bildirimi.
* **Merkezi Durum Yönetimi:** Araç listesi, filtreler ve favorilerin Redux kullanılarak global state üzerinde yönetilmesi.

## Kullanılan Teknolojiler
* **React.js & Vite** (Geliştirme ve Derleme)
* **Redux** (State Management)
* **React Router** (Sayfa Yönlendirmeleri)
* **Axios** (API İstekleri)
* **CSS Modules** (Bileşen Bazlı Stillendirme)

## Kurulum ve Kullanım Talimatları

Projeyi yerel bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. **Repoyu Klonlayın:**
```bash
git clone https://github.com/baboopsc/travel-trucks.git
```

2. **Proje Dizinine Girin:**
```bash
cd travel-trucks
```

3. **Gerekli Bağımlılıkları Yükleyin:**
```bash
npm install
```

4. **Geliştirme Sunucusunu Başlatın:**
```bash
npm run dev
```

5. **Canlı Sürüme Hazırlama (Build):**
```bash
npm run build
```

## Yazar Bilgisi
* **Geliştirici:** Ali Muhsin Mışraklı
* **GitHub:** [baboopsc](https://github.com/baboopsc)
