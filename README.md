# 🌳 Tarih Ağacı - İnteraktif Tarih Platformu

Tarih Ağacı, Türk tarihini dijital bir platforma taşıyan, kullanıcıların tarihi olayları interaktif bir ağaç yapısı üzerinden keşfedebileceği Full-Stack bir web uygulamasıdır. İçeriklerin dinamik olarak yönetilebildiği bir yönetici (Admin) paneline sahiptir.

## 🚀 Projenin Amacı
Tarihsel verileri statik metinler yerine algoritmik ve görsel bir hiyerarşi ile sunmak. Projemiz, veri yönetimi, MVC mimarisi ve responsif ön yüz tasarımını bir araya getiren kapsamlı bir ürün geliştirme çalışmasıdır.

## 🛠️ Kullanılan Teknolojiler

**Backend (Sunucu ve Veri Yönetimi):**
* **Node.js:** Sunucu ortamı
* **Express.js:** Web uygulama çatısı
* **MySQL:** İlişkisel veritabanı (Veri modelleme ve saklama)
* **EJS:** Dinamik HTML sayfaları için şablon motoru

**Frontend (Kullanıcı Arayüzü):**
* **HTML5 & CSS3:** Sayfa iskeleti ve stillendirme
* **JavaScript:** Kullanıcı etkileşimi ve DOM manipülasyonu
* **Bootstrap:** Responsif (mobil uyumlu) tasarım bileşenleri

## ⚙️ Temel Özellikler
* **MVC Mimarisi:** Model, View ve Controller yapılarının izole edildiği temiz kod tasarımı.
* **Yönetici Paneli (Admin CMS):** Tarihi bilgilerin, soruların ve olayların sisteme eklenebildiği dinamik veri giriş arayüzü (`admin.ejs`).
* **Veritabanı Entegrasyonu:** SQL sorguları ile veri ekleme, okuma, güncelleme ve silme (CRUD) işlemleri.
* **Dinamik Yönlendirme:** Node.js arka ucu ile kesintisiz veri akışı.

## 📁 Proje Yapısı
* `server.js` : Ana sunucu dosyası ve API yönlendirmeleri.
* `models.js` / `db.js` : Veritabanı bağlantısı ve tablo modelleri.
* `/views` : Kullanıcı ve yönetici paneline ait EJS şablonları.
* `/public` : Statik dosyalar (CSS, Client-Side JS, Görseller).
* `tarih_agaci.sql` : Veritabanı şema ve örnek verileri.

## 💻 Kurulum ve Local'de Çalıştırma

Bu proje geliştirme aşamasında olduğu için şu an uzak bir sunucuda (hosting) canlıda değildir. Projeyi kendi bilgisayarınızda (localhost) tam kapasiteyle ve veritabanı bağlantısıyla çalıştırmak için aşağıdaki adımları izleyebilirsiniz:
1. Projeyi bilgisayarınıza klonlayın: `git clone https://github.com/feiwche/Tarih-Agaci.git`
2. Proje dizinine girip gerekli Node.js paketlerini (bağımlılıkları) yükleyin: `npm install`
3. Veritabanını kurun: `tarih_agaci.sql` dosyasını yerel MySQL sunucunuza (örneğin XAMPP, WAMP veya MySQL Workbench üzerinden) içe aktarın (import).
4. Sunucuyu başlatın: `node server.js`
5. Tarayıcınızda `http://localhost:3000` adresine giderek projeyi tam donanımlı haliyle deneyimleyin.

---

*Geliştiriciler:*

İrem Kervan - Bilgisayar Mühendisliği Öğrencisi
Coşkun Efe Kapancı - Bilgisayar Mühendisliği Öğrencisi
Yusuf Altıparmak - Bilgisayar Mühendisliği Öğrencisi
İbrahim Ethem Sevimoğlu - Bilgisayar Mühendisliği Öğrencisi
