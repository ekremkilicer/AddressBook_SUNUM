# AddressBook_SUNUM

Merhaba, Address Book projesi İstanbul - Beşiktaş Wissen Akademi'de Kursiyerlik yaptığım süreçte yazdık.Bu projede Trendyol,Getir gibi uygulamalardaki adres ekleme bölümünden esinlendik. Amacımız adres kaydı yapmaktır. Ayrıca gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Bu projenin tüm hakları ben Betül Akşan'a, 302 sabah grubu sınıfımın öğrencilerine aittir. Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık. -AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor)
Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor.
Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34
Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .


![1](https://user-images.githubusercontent.com/120444709/219598336-56c840a1-005e-4ee9-bcaf-f9d9ce04f9d9.png)
![2](https://user-images.githubusercontent.com/120444709/219598385-13eadfd2-06d4-4cbb-be2a-23d6cc7cedff.png)
![3](https://user-images.githubusercontent.com/120444709/219598399-c69d9895-3337-42cb-8efc-6b8bed6eb453.png)
![5](https://user-images.githubusercontent.com/120444709/219598418-2f5b06fe-c4fd-4541-9600-7c859a6a1eee.png)
![6](https://user-images.githubusercontent.com/120444709/219598433-ad43bb43-6a4a-4999-937d-844bfa2e9078.png)
![7](https://user-images.githubusercontent.com/120444709/219598450-94cab1d6-5ff4-4623-8f8f-27cb0e1aed8f.png)
![9](https://user-images.githubusercontent.com/120444709/219598457-8ecbbd81-3b1a-4e2d-93a0-15cb5acb3208.png)

