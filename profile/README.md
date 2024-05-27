# Proje Hakkında
Bu proje, gelecekteki ortak çalışmalarda kullanılacak bir ortam geliştirmeyi amaçlamaktadır. İki aşamalı bir yaklaşım kullanılarak gerçekleştirilecektir. İlk aşamada, Django kullanarak bir bileşen oylama sistemi geliştirilecektir. İkinci aşamada ise en yüksek oyu alan bileşenler kullanılarak Bootstrtap benzeri bir framework oluşturulacaktır.

## Toplantı Tarihleri
1. 27.05.2024 Pazartesi
2. 30.05.2024 Perşembe
3. 03.06.2024 Pazartesi

# İlk Aşama
Stajyerlerin kayıt olabileceği, yöneticiden onay alıp kaydolduktan sonra anonim olarak bileşen yükleyip, anonim olarak oy kullanabilecekleri bir platform.

## Genel Özellikler
```bash
Back-End
├── Hesap Sistemi
│   ├── Kullanıcı Yönetimi
│   ├── Kayıt ve Giriş Sistemi
│   └── Admin onayı ile kullanıcı aktivasyonu
│
├── Bileşen Sistemi
│   ├── Bileşen Yükleme
│   ├── Kullanıcıların bileşen yükleyebileceği bir form
│   └── Bileşenlerin kategoriye göre ayrılması
│
├── Oylama Sistemi
│   ├── Anonim oylama
│   └── Her kullanıcı bir bileşene en fazla bir oy verebilecek
│
└── Yönetici Paneli
    ├── Kullanıcıları onaylama/reddetme
    └── Bileşenleri yönetme ve onaylama

Front-End
├── Ana Sayfa
│   ├── Proje hakkında genel bilgi
│   └── Kayıt ve giriş bağlantıları
│
├── Kullanıcı Sayfası
│   ├── Bileşen Yükleme
│   ├── Bileşenlerin Listesi
│   └── Bileşenlerin kategoriye göre ayrılması
│
├── Oylama Sistemi
│   ├── Anonim oylama
│   └── Her kullanıcı bir bileşene en fazla bir oy verebilecek
│
└── Yönetici Paneli
    ├── Kullanıcıları onaylama/reddetme
    └── Bileşenleri yönetme ve onaylama

Sayfalar (bunları yukarıdaki gibi şekillendirmeye üşendim)

Anasayfa
Projenin tanıtımı ve genel bilgi
Kayıt ve giriş bağlantıları
Kayıt sayfası

Yeni kullanıcıların kayıt olabileceği form
Admin onayı sonrası aktivasyon
Giriş Sayfası

Mevcut kullanıcıların giriş yapabileceği form
Bileşen yükleme sayfası

Kullanıcılarınm bileşen yükleyebileceği form
Bileşen kategorilerinin seçimi
Bileşen listesi sayfası

Tüm bileşenlerin listelendiği sayfa
Kullanıcıların bileşenleri oylayabileceği arayüz
Oylama sayfası

Kullanıcıların bileşenleri anonim olarak oylayabileceği sayfa
Sonuçlar sayfası

Oylama sonuçlarının ve en çok oy alan bileşenlerin listelendiği sayfa
Kullanıcı profil sayfası

Kullanıcıların profil bilgilerini görebileceği ve düzenleyebileceği sayfa
Yönetici paneli

Kullanıcıları onaylama/reddetme
Yüklenen bileşenleri onaylama/reddetme
Oylama sonuçlarını yönetme
Hakkında Sayfası
```
