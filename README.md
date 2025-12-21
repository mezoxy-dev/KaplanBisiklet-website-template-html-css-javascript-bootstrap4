# KaplanBisiklet - Web Tabanlı Bisiklet Satış ve Yönetim Sistemi Proje Raporu

## 1. Proje Özeti
**Proje Adı:** KaplanBisiklet
**Tarih:** 7 Aralık 2025
**Geliştirici:** MUSTAFA MEHMET ASLANDAĞ

Bu proje, modern ve profesyonel bir bisiklet satış platformu ile bu platformu yönetecek kapsamlı bir yönetim panelinin geliştirilmesini kapsamaktadır. Proje, son kullanıcılar için şık, duyarlı (responsive) ve etkileşimli bir e-ticaret arayüzü sunarken, yöneticiler için ürün, duyuru ve birim yönetimini kolaylaştıran işlevsel bir admin paneli içermektedir.

## 2. Kullanılan Teknolojiler ve Araçlar
Proje geliştirme sürecinde, performans, esneklik ve modern web standartları gözetilerek aşağıdaki teknolojiler kullanılmıştır:

### 2.1. Temel Teknolojiler
*   **HTML5:** Sayfa yapısı ve semantik içerik oluşturulması için kullanıldı. SEO uyumlu etiketler (semantic tags) tercih edilerek erişilebilirlik artırıldı.
*   **CSS3:** Tüm görsel tasarım ve stil işlemleri için "Vanilla CSS" kullanıldı.
    *   **CSS Değişkenleri (Custom Properties):** Renk paleti ve tema yönetimi (Teal/Yeşil tonları) için merkezi bir stil yapısı kuruldu.
    *   **Flexbox ve Grid:** Duyarlı (responsive) yerleşimler için modern layout teknikleri kullanıldı.
    *   **Animasyonlar:** Kullanıcı deneyimini (UX) zenginleştirmek için hover efektleri ve geçişler eklendi.
*   **JavaScript (ES6+):** Sayfa içi etkileşimler, dinamik içerik yönetimi ve form kontrolleri için kullanıldı.

### 2.2. Kütüphaneler ve Framework'ler
*   **Bootstrap:** Hızlı ve duyarlı grid yapısı ile hazır bileşenlerin (modal, navbar vb.) kullanımı için projeye dahil edilmiştir.
*   **jQuery:** DOM manipülasyonu ve bazı eski eklentilerin (slider vb.) uyumluluğu için kullanılmıştır.
*   **Chart.js:** İstatistik sayfasında (`statistics.html`) verilerin görselleştirilmesi ve grafik çizimi için kullanıldı.
*   **FontAwesome:** Kullanıcı arayüzünde modern ve ölçeklenebilir ikonlar sağlamak için entegre edildi.
*   **Google Fonts:** Tipografi standartlarını yükseltmek ve "Premium" bir hissiyat vermek amacıyla modern font aileleri (Inter, Roboto vb.) kullanıldı.

## 3. Proje İsterleri ve Kapsam

### 3.1. Ön Yüz (Frontend) İsterleri
*   **Modern Tasarım:** Kullanıcıyı etkileyen, canlı renklere ve cam morfizm (glassmorphism) gibi modern tasarım trendlerine sahip bir arayüz.
*   **Responsive Yapı:** Mobil, tablet ve masaüstü cihazlarda kusursuz çalışan esnek tasarım.
*   **Dinamik İçerik:**
    *   Ana sayfada otomatik kayan **Duyuru Slider'ı**.
    *   Ürünlerin listelendiği ve filtrelendiği **Mağaza (Shop)** sayfası.
    *   Kurumsal kimliği yansıtan **Misyon, Vizyon ve Birimler** sayfaları.
*   **İletişim ve Etkileşim:**
    *   Çalışan bir **İletişim Formu** (Validasyonlu).
    *   **Bülten Aboneliği (Newsletter)** alanı.
*   **İstatistik Paneli:** Kullanıcı ve satış verilerini gösteren, animasyonlu sayaçlar ve grafikler içeren bilgilendirme sayfası.

### 3.2. Yönetim Paneli (Admin Dashboard) İsterleri
*   **Dashboard Dizaynı:** Site genelindeki renk paletiyle uyumlu, profesyonel bir yönetim arayüzü.
*   **Yönetim Fonksiyonları:**
    *   **Ürün Yönetimi:** Yeni ürün ekleme, düzenleme ve listeleme.
    *   **Duyuru Yönetimi:** Ana sayfadaki duyuruların yönetimi.
    *   **Birim/Personel Yönetimi:** Organizasyon şemasının güncellenmesi.
    *   **Mesajlar:** İletişim formundan gelen mesajların görüntülenmesi.

## 4. Proje Modülleri ve Dosya Yapısı

### 4.1. Genel Sayfalar
*   `index.html`: Ana sayfa, öne çıkan ürünler ve duyuru slider'ı.
*   `shop.html`: Tüm ürünlerin listelendiği katalog sayfası.
*   `about.html` / `mission-vision.html`: Kurumsal bilgiler.
*   `units.html`: Organizasyon birimleri ve yönetim kadrosu.
*   `contact.html`: İletişim bilgileri ve formu.
*   `statistics.html`: İstatistiksel veriler ve grafikler.
*   `product-*.html`: Ürün detay sayfaları.

### 4.2. Admin Paneli
*   `admin/index.html`: Yönetim paneli ana gösterge tablosu.
*   `admin/products.html`: Ürün envanter yönetimi.
*   `admin/announcements.html`: Duyuru yönetimi.
*   `admin/units.html`: Birim yönetim sayfası.
*   `admin/messages.html`: Kullanıcı mesajları kutusu.

## 5. Tasarım ve Geliştirme Süreci
*   **Renk Paleti:** Marka kimliğini yansıtan koyu/premium temalar ve yeşil/teal aksan renkleri tercih edildi.
*   **Kullanıcı Deneyimi (UX):** Menülerde kolay erişim sağlandı (Header düzeltmeleri), formlarda kullanıcıya geri bildirim veren mekanizmalar kuruldu.
*   **Kod Kalitesi:** Modüler ve tekrar kullanılabilir CSS sınıfları oluşturuldu. JavaScript kodları, sayfa performansını düşürmeyecek şekilde optimize edildi.

## 6. Sonuç
Cycle projesi, belirlenen isterler doğrultusunda, modern web teknolojileri kullanılarak başarıyla geliştirilmiştir. Hem son kullanıcı hem de yönetici tarafında ihtiyaç duyulan tüm temel fonksiyonlar, estetik ve performanslı bir yapıda sunulmuştur. Proje, gelecekteki geliştirmelere açık, genişletilebilir bir mimariye sahiptir.
