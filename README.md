Proje Amacı:
Bu proje, uçak modelleri, lokasyonlar ve rezervasyonların yönetilebildiği bir uçak rezervasyon sistemi geliştirmeyi amaçlamaktadır. Proje kapsamında üç temel form bulunmaktadır: Uçak Formu, Lokasyon Formu ve Rezervasyon Formu. Proje, nesneye dayalı programlama (OOP) prensiplerine göre modellenmiş ve SQLite veritabanı ile Entity Framework ORM kullanılarak geliştirilmiştir.

Formlar ve İşlevleri:

Uçak Formu:

Uçak Modeli
Marka
Seri Numarası
Koltuk Kapasitesi
Bu form, uçak bilgilerini listeleme ve kaydetme işlevine sahiptir.
Lokasyon Formu:

Ülke
Şehir
Havaalanı
Aktif/Pasif Durumu
Bu form, lokasyon bilgilerini yönetmek için kullanılır.
Rezervasyon Formu:

Rezervasyon ekranında koltuklar satılmadıysa yeşil, satıldıysa kırmızı renge dönecek şekilde gösterilir.
Koltuk üzerine tıklandığında, müşteri bilgileri datalistede görüntülenir.
Bu form, görsel olarak kullanıcı dostu bir rezervasyon deneyimi sağlar.
Teknik Detaylar:

Nesneye Dayalı Programlama (OOP):

Proje, sınıflar ve nesneler kullanılarak tasarlanmıştır.
Uçak, Lokasyon ve Rezervasyon gibi ana bileşenler sınıflar halinde modellenmiştir.
Veritabanı ve ORM:

SQLite veritabanı kullanılarak veri yönetimi sağlanmıştır.
Entity Framework ORM kullanılarak veritabanı işlemleri gerçekleştirilmiştir.
Kullanıcı Arayüzü:

Kullanıcı arayüzü, tab panel kullanılarak geliştirilmiştir.
Kullanıcı arayüzü, sezgisel ve kullanıcı dostu bir deneyim sunar.
Proje Geliştirme Süreci:
Rezervasyon ekranında kullanıcı deneyimini artırmak için koltukların durumu renklerle belirtilmiş ve müşteri bilgileri interaktif olarak gösterilmiştir.
