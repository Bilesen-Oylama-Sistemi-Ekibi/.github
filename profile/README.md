# Proje Hakkında
Bu proje, gelecekteki ortak çalışmalarda kullanılacak bir ortam geliştirmeyi amaçlamaktadır. İki aşamalı bir yaklaşım kullanılarak gerçekleştirilecektir. İlk aşamada, Django kullanarak bir bileşen oylama sistemi geliştirilecektir. İkinci aşamada ise en yüksek oyu alan bileşenler kullanılarak Bootstrtap benzeri bir framework oluşturulacaktır.

## Toplantı Tarihleri
1. 27.05.2024 Pazartesi
2. 30.05.2024 Perşembe
3. 03.06.2024 Pazartesi

# İlk Aşama
Stajyerlerin kayıt olabileceği, yöneticiden onay alıp kaydolduktan sonra anonim olarak bileşen yükleyip, anonim olarak oy kullanabilecekleri bir platform.

## Genel Özellikler
### Backend için yapılması gerekenler:
1. Hesap sistemi olacak.
   - Kullanıcı hesabı olacak ve hesabın iki türü olacak (üye, yönetici).
   - Hesap bir yönetici tarafından onaylanana kadar herhangi bir işlem yapamayacak. (oylama, bileşen yükleme, bileşen görüntüleme gibi)

2. Bileşen sistemi olacak.
   - Onaylı kullanıcıların yükledikleri bileşenler anonim olarak görünecek.
   - Bileşenler kategoriye göre ayrılabilecek.

3. Oylama sistemi olacak.
   - Kullanıcıların verdiği oylar anonim olarak gözükecek.
   - Kullanıcılar bir bileşene sadece bir defa oy verebilecek.

4. Eğer kullanıcı bir yöneticiyse,
   - Kullanıcıları onaylayıp/reddetme yetkisine sahip olacak.
   - Bileşenleri yönetip, onaylayabilecek.

> [!IMPORTANT]
> Backendde Django, Frontendde React kullanacağımız için
> Django ile React arasındaki iletişimi REST API sayesinde
> yapacağız. Eğer ki bu terimlere yabancıysanız
> "django rest api", "django crud api" diye aratabilirsiniz.

### Frontend için yapılması gereken sayfalar:
1. Anasayfa (Projenin tanıtımı, genel bilgi, kayıt ve giriş bağlantıları)
2. Kayıt ve Giriş sayfaları (ayrı bir sayfa yapmak yerine anasayfada modal olarak çıkarılabilir.)
3. Kullanıcının kendi profilini görüntüleyip, bilgilerini düzenleyebileceği sayfa
4. Bileşenlerin listelendiği sayfa (kategori, oy sayısı gibi özelliklere göre sıralanıp filtrelenebilecek. bileşenlere de buradan oy verilecek.)
5. Bileşen yükleme sayfası (ayrı bir sayfa yapmak yerine listeleme sayfasında modal olarak çıkarılabilir.)
Eğer yönetici hesabıysa bileşen listeleme menüsünde ek bir seçenekle bileşeni onaylayıp silebilecek. Navigasyon çubuğunda ek bir seçenek olacak ve yönetici o seçeneğe bastığında onaylama bekleyen kullanıcıları görüntüleyebilecek.
