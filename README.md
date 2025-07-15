# Öğrenci Yönetim Sistemi

Bu proje, HTML, CSS, JavaScript ve jQuery kullanarak geliştirilmiş basit bir öğrenci yönetim sistemidir.

## Özellikler

- ✅ Öğrenci listesi görüntüleme
- ✅ Yeni öğrenci ekleme
- ✅ Öğrenci silme
- ✅ İstatistik görüntüleme
- ✅ Responsive tasarım
- ✅ Satır tıklama efekti

## Kullanılan Teknolojiler

- HTML5
- CSS3
- JavaScript (ES5)
- jQuery 3.6.0

## Kurulum

1. Projeyi bilgisayarınıza indirin
2. `index.html` dosyasını web tarayıcınızda açın
3. Hazır!

## Dosya Yapısı

```
proje/
├── index.html          # Ana HTML dosyası
└── README.md          # Bu dosya
```

## Kullanım

### Öğrenci Ekleme
1. "Yeni Öğrenci Ekle" bölümündeki formu doldurun
2. Tüm alanları eksiksiz doldurun
3. "Öğrenci Ekle" butonuna tıklayın

### Öğrenci Silme
1. Öğrenci listesinde silmek istediğiniz öğrenciyi bulun
2. "Sil" butonuna tıklayın
3. Onay mesajında "Tamam" seçin

### Satır Tıklama
- Tablodaki herhangi bir satıra tıklayın
- Satır turuncu renge döner
- 2 saniye sonra normal rengine döner

## Veri Yapısı

Her öğrenci şu bilgileri içerir:

```javascript
{
    id: 1,
    name: "Ahmet Yılmaz",
    class: "9-A",
    age: 15,
    email: "ahmet@okul.com",
    phone: "0532-111-1111",
    city: "İstanbul"
}
```

## İstatistikler

- **Toplam Öğrenci**: Sistemdeki toplam öğrenci sayısı
- **Toplam Sınıf**: Farklı sınıfların sayısı
- **Ortalama Yaş**: Tüm öğrencilerin yaş ortalaması

## Sınıf Seçenekleri

- 9-A, 9-B
- 10-A, 10-B
- 11-A, 11-B
- 12-A, 12-B

## Şehir Seçenekleri

- İstanbul
- Ankara
- İzmir
- Antalya
- Bursa
- Adana
- Gaziantep
- Konya

## Responsive Tasarım

- Mobil cihazlarda form elemanları alt alta sıralanır
- Tablolar yatay kaydırma ile görüntülenir
- İstatistik kutuları mobilde tek sütun olur

## Tarayıcı Desteği

- Chrome (önerilen)
- Firefox
- Safari
- Edge

## Önemli Notlar

- Veriler tarayıcı hafızasında saklanır
- Sayfa yenilendiğinde eklenen veriler kaybolur
- İnternet bağlantısı jQuery CDN için gereklidir

## Geliştirici

Bu proje HTML/CSS/JavaScript öğrenmek için geliştirilmiştir.

## Lisans

Bu proje eğitim amaçlıdır, özgürce kullanılabilir.

---

**Son Güncelleme:** 2024