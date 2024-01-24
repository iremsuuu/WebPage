## Asp.net core Tabanlı Login-Register-Calculator Uygulaması
Bu README dosyası, WebVize uygulamasını tanıtmak, kurulum yapmak ve temel kullanım adımlarını açıklamak için tasarlanmıştır.

### Proje Tanımı
WebVize uygulaması, öğrencilerin vize ve final sınavlarından aldıkları notları kullanarak ortalama hesaplamalarını sağlayan bir web uygulamasıdır. Ayrıca, kullanıcıların kayıt olmaları ve giriş yapmaları da mümkündür.

### Proje Yapısı
Proje, aşağıdaki temel sayfalar ve modeller üzerine inşa edilmiştir:

#### Index Sayfası (Pages/Index.cshtml):
Giriş yapmak veya kayıt olmak için kullanıcıyı yönlendirir.
Sayfa Modeli: IndexModel

#### Login Sayfası (Pages/LoginPageModel.cshtml):
Kullanıcı girişi yapmak için kullanılır.
Sayfa Modeli: LoginPageModel
#### Register Sayfası (Pages/Register.cshtml):

Yeni kullanıcı kaydı yapmak için kullanılır.
Sayfa Modeli: RegisterModel

#### Calculator Sayfası (Pages/Calculator.cshtml):
Vize ve final notlarına göre ortalama hesaplamak için kullanılır.
Çıkış yapmak için çıkış yap butonuna basılır.
Sayfa Modeli: CalculatorModel

### Kullanılan Teknolojiler
ASP.NET Core Razor Pages
Microsoft Access Veritabanı
