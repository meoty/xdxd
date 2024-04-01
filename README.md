# MVVM Android Ayakkabı Mağazası Uygulaması

Bu proje, kullanıcıların ayakkabı verilerini yönetmelerine olanak tanıyan bir Android uygulamasıdır. Kullanıcılar ayakkabı ekleyebilir, güncelleyebilir, silebilir ve mevcut ayakkabıları görüntüleyebilir. Proje, MVVM mimarisi kullanılarak geliştirilmiş olup, Retrofit ile bir RESTful API'ye bağlanır.

## Kullanılan Kütüphaneler ve Teknolojiler

- **OkHttp ve Retrofit:** HTTP istekleri göndermek ve API'ye bağlanmak için kullanıldı.
- **Gson:** JSON verilerini işlemek için kullanıldı.
- **Coroutines:** Asenkron programlama için kullanıldı.
- **AndroidX Bileşenleri:** RecyclerView, AppCompat, Material Design bileşenleri ve diğer AndroidX kütüphaneleri kullanıldı.

## Özellikler

- **Ayakkabı Ekleme:** Kullanıcılar yeni ayakkabı bilgilerini ekleyebilir.
- **Ayakkabı Güncelleme:** Kullanıcılar mevcut ayakkabı bilgilerini güncelleyebilir.
- **Ayakkabı Silme:** Kullanıcılar mevcut ayakkabıları silebilir.
- **Ayakkabı Görüntüleme:** Kullanıcılar mevcut ayakkabıları görüntüleyebilir.

## MVVM Mimarisi

![mvvm-diagram](https://github.com/meoty/xdxd/assets/141409558/7bf4c1d8-ba8a-4f69-8833-f3650c67404d)

Bu proje, MVVM (Model-View-ViewModel) mimarisi kullanılarak geliştirilmiştir. Her bileşenin rolü şu şekildedir:

- **Model:** Ayakkabı veri modeli sınıfları, API çağrılarından dönen verilerin temsili için kullanıldı.
- **View:** Kullanıcı arayüzü bileşenleri, Jetpack Compose kullanılarak oluşturuldu.
- **ViewModel:** UI ile bağlantıyı yöneten ve iş mantığını yürüten ara katman sınıflarıdır.

## Nasıl Başlatılır

1. Bu depoyu klonlayın: `git clone https://github.com/kullanici_adi/AyakkabiMagazasi.git`
2. Android Studio'da proje klasörünü açın.
3. Bir Android cihazı veya emülatör kullanarak uygulamayı çalıştırın.

## Katkılar


Bu projeye katkıda bulunmak isterseniz, lütfen bir çekme isteği gönderin. Katkılarınızı memnuniyetle karşılarız!

## Lisans

Bu proje, MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasını inceleyin.
