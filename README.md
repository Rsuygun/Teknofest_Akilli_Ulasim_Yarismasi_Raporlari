# Akıllı Ulaşım Projesi - DATABOX
Proje Hakkında
Günümüz şartlarında trafikte yaşanan olayların takip edilmesi ve geri besleme ile kontrol altına alınması için akıllı ulaşım altyapıları inşa edilmeye başlanmıştır. Fakat bu altyapıların düzgün çalışabilmesi için son kullanıcı olan sürücünün interaktif bir şekilde takip edilmesi gerekir. Araçlarda opsiyonel olarak bulunan güvenlik sistemlerinin yetersiz kalmasından dolayı ve kullanıcıların artan maliyetler sonucunda bu sistemlere erişememesi trafikte önemli eksikliklere yol açmaktadır. Bu projedeki hedefimiz uçak sistemlerinde bulunan araçlar için çoklu ölçüm yapabilen kara kutu sistemi geliştirip kara ulaşımına entegre etmektir.

Proje Detayları
Cihaz: ESP32 tabanlı geliştirilen DATABOX adındaki cihazımıza entegre ivme, yön, GPS ve çeşitli çevresel sensörler entegre edilmiştir.
Veri Aktarımı: Veriler Bluetooth aracılığıyla mobil uygulamaya aktarılır ve oradan sunucuya işlenmek üzere gönderilir.
Veri İşleme: Verilerden kaza önleme, sürücü profillendirme çıkarımları çevrimiçi ve çevrimdışı şekilde yapılır.
Geri Bildirim: Geri bildirim ve çıkarımlar sunucudan telefona, DATABOX cihazına ve sürücüye aktarılabilir.
Kaza Tutanakları: Belirli başlı kazalarda sürücüler verilerini kablosuz olarak paylaşarak kaza tutanaklarını oluşturabilirler.
Problem ve Çözüm
Problem/Sorun:
Günümüzde ulaşım sektöründe önemli derecede ilerleme ve gelişme olmasından dolayı dünya üzerinde araç sayısı ve sürücü bireyler bir hayli artmıştır. Araç sayısı ve sürücü bireylerin sayısının artışı olması istenmese de trafik kazaları, araç bakımsızlıkları ve sürücü hataları gibi birçok sebebi oluşturarak trafik ve ulaşım konusun da tehlike oluşturabiliyor.

Çözüm:
Problemimizin çözümü olarak uygun maliyetle şimdilik kara araçlarına entegre edilebilecek uçaklardaki kara kutu sisteminin benzerini geliştirmektir. Cihazımızda VANET (Vehicular Ad Hoc Network) ağına dahil olmadan araçlarda bulunacak harici bir IoT cihaz üzerinden kurgulanmıştır. Sensör verilerinden elde edilen çıkarımlar trafikte oluşabilecek kazalar için kanıt toplama amaçlı ve sürücü davranışlarını sınıflandırma için kullanılacak ve buna uygun tavsiye ve karar destek sistemi geliştirilecektir.

Hedefler
VANET olmayan ağlarda sentetik sensörlerin kullanım alanını genişletmek.
Akıllı ulaşım sistemlerinde kullanılabilir hale getirerek yerelde 3 araca entegre ederek, olası bir kaza durumunda kusurlu kişiyi %80 oranında paylaşılan verilerden tespit etmek.
Mobil veri paylaşımı ile kazaların kaldırılarak trafiğin açılması noktasında süreci %30 hızlandırmak.
Olaylar ile ilgili kanıt toplama noktasında mevcut duruma göre %80 daha etkin veri toplama ve kanıt olarak sunma imkânı hedefliyoruz.
Anormal sürüş tespiti ve çıkarım yapılması noktasında %60 hedefimiz var.

## Görseller

### DATABOX Cihazı

![Prototipe Ait Görsel-1](https://github.com/Fahrettinsolak/Teknofest-Akilli-Ulasim-Yarismasi-Raporlari/assets/79358514/73df2403-ce4f-488b-b80e-f9887db115bf)

Araç üzerinde konumlandırılmış DATABOX cihazının görünümü.

![Prototipe Ait Görsel-2](https://github.com/Fahrettinsolak/Teknofest-Akilli-Ulasim-Yarismasi-Raporlari/assets/79358514/63d9777b-3bfd-4ea6-b878-d66da075554f)

### Veri Aktarımı

![Uygulama Giriş Ekranı](https://github.com/Fahrettinsolak/Teknofest-Akilli-Ulasim-Yarismasi-Raporlari/assets/79358514/a9208eba-6f5b-486a-a405-844e076e51a4)

Mobil uygulamanın giriş ekranı.

![Veri Aktarımı Süreci](https://github.com/Fahrettinsolak/Teknofest-Akilli-Ulasim-Yarismasi-Raporlari/assets/79358514/ae4f1589-27ec-46e7-abb5-9b89e6782ec8)

Mobil uygulamadan sunucuya veri aktarımı sürecinin görseli.


## Belgeler

### Katılım Sertifikası

![Teknofest_Akilli_Ulasim_Yarismasi_Katılım](https://github.com/Fahrettinsolak/Teknofest-Akilli-Ulasim-Yarismasi-Raporlari/assets/79358514/a8c36688-af88-489b-9aa4-ad0c35a6750c)

### Finalist Sertifikası

![Teknofest_Akilli_Ulasim_Yarismasi_Finalist_Belgesi](https://github.com/Fahrettinsolak/Teknofest-Akilli-Ulasim-Yarismasi-Raporlari/assets/79358514/f5639534-2f79-489e-a2d8-1d583072a838)
