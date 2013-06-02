GeziProject
===========

NOT: Tartismak istediginiz konulari issue acabilirsiniz. Tamamen topluluk tarafindan yonetilen ve gelistirilen bir proje olmasi onemli 

Gezi parkı ile başlayan protestolara bizzat katıldım. Protestolar sırasında yaşadığım sorunların bazılarına çözüm üretebileceğimizi duşunuyorum. Sadece protesto ederek katılmak yeterli olmamalı, bu nedenle aklıma gelen fikirleri tartışmaya açmak istiyorum. Bu tartışmalardan çözüm üreten projeler çıkmasını umuyorum. Protestolar dünyanın her yerinde var olmaya devam edecek, bence bu tarz yardımcı projeler ile etkileri güçlenecek ve olumsuzluklar önlenebilecek. Gezi parkı protestolarında onaylamadığım ve oradaki halkın da onaylamadığını bildiğim bir çok olay oldu. Bu olayların bazılarına mudehale ederek önlemeyi basardık(Kamu malına zarar vermek, taskınlık ve provokasyon yapmak gibi). Bu önerim ile protesyoların kucuk grupların yaptıgı taskınlıkları azaltmasını ve amacından taşmadan yürümesine yardımcı olmasını umuyorum.

Beklentim bu projeyi yaparken benimle birlikte çalışacak, aynı düşünceleri paylaşan insanlar bulmak ve hızla hayata geçirmek. Projenin GNU lisansına sahip olması gerektığini duşunuyorum. Buradaki butün konular sadece projenin başlaması için önerilerim ve hepsinn tartışarak değişmesi/gelişmesini bekliyorum.


#Bence en temel sorunlar
Buraya sadece teknik anlamda çözüm bulabilecegimizi düşündüğüm sorunları yazdım, elbette çok madde var. Problemlerin boyutlarını bir çok blog yazısı kapsadıgı için sadece temel başlıklarla yetiniyorum. Çözümlerin ayrıntılı yazılması bence projelerin gerçekleşme olasılığını arttıracaktır.

* Sosyal medya bilgi kirliliği
* Erişim ihtiyacı (Internet, GSM, ...)
* Ortamda yayılan dedidokuların önlenmesi
* Bölgesel olarak güncel durumun bilinmemesi
* Pil ömrü, sarj ihtiyacı
* Provakatörlerin engellenmesi için efektif bir yöntem
* Ortak akıl ve haraketin koordinasyonu

##Çözüm düşünürken dikkat edilmesi gereken hususlar
* Alan içi ve dışı olmak üzere iki ayrı kullanıcı grubu düşünülmeli
* Çözümler teknik olarak karmaşık olabilir ama kullanım olarak twitter kullanmaktan daha zor olmamalı
* Olabildiğince çok platform desteklemeli ya da platform destegi kolayca verilebilmeli
* Kısıtlı kaynak kullanmalı, pil ömrü, bant genişliği bu ortamlarda önemli kaynaklar
* Çözümler merkezi olmamalı
* İçerik saglayıcıların kullanıcılar olmalı
* Üretilen içerik bir puanlama sistemi ile dogrulanmalı, yanlış, yalan bilgiler altlarda kalmalı

#Sosyal medya bilgi kirliliği
##Tespitler
* Sosyal medya iletişimin tam merkezine
* Manipulasyon ve dezenformansyona cok müsait
* Bilginin dogrulugunu gösteren bir mekanizma yok. İnsanlar bilginin dogrulugundan önce verdigi heyecan ile haraket etmeyi tercih ediyorlar
* Twitter ve Facebook kullanılıyor, daha çok twitter etkili

#Erişim ihtiyacı (Internet, GSM, walkie-talkie, ...)
##Tespitler
* İnsanlar yogun olarak internet kullanıyorlar.
* İnternet genellikle mesajlaşma, sosyal mecra ve harita servisleri için kullanılıyor.
* Yüksek ses nedeni ile sesli görüşme yerine mesajlaşma tercih ediliyor
* Baz istasyonları yoğunluk nedeni ile kesintili erişim sağlayabiliyorlar
* Ortamda bir çok kurumun ya da evin wireless access pointleri var. Kurumlar ya da insanlar paylaşmak istiyorlar ama nasıl yapacaklarını bilmiyorlar.Twitter üzerinden bir çok wireless sifresi paylaşıldı ama efektif degil. İnternet erişimi olmadan, internetteki bir bilgiye ulaşarak erismek mantıksız.
* Yogun olarak telefon kullanılıyor ve hizla pil bitiyor
* Sarj etmek için mekanlar elektrik sağlayabiliyorlar ama sarj kablosu, adaptörü bulmak zor


##Öneri
Protestolara katılan kullanıcının akıllı telefonuna kolayca yükledigi bir uygulama. Uygulama kullanıcıların kendi ürettigi bilgileri gösterir bu bilgilerin dogrulugu DM(dogrulama mekanizması) ile otomatik belirlenir ve yukarı/aşağı itilir.

####Özellikler
* Lokasyon bazlı güncel durum. Kullanıcı girdiginde bulundugu bölgedeki ya da merak ettigi bölgedeki son durumu(DB) anlık görebilmeli. Gösterim için heatmap kullanılabilir. Kendi bölgesi ile ilgili DB(durum bildirimi) yapabilmeli
* Yardım anonslarını görebilmeli ya da yapabilmeli. Twitter da bir çok kisi evini/ofisini açtı ama kapasiteleri nedeni ile gidenler yardım alamadan dönebilir. Dolayısı ile yardım anonsunu yapan kisi kapasite ile ilgili bilgi güncellemesi yapabilmeli.
* Etraftaki açık eczaneler ve durumları. Eczane açık olabilir ama amacınız talsid almak ise, talsid olup olmadıgını bilmek işe yarar.
* Doktor/Ambulans iletisimleri ve çagrıların GPS kullanılarak yapılması. Doktorlar gonullu olarak kosuyor ama yaralıları bulmaları cok zor.Bir doktor talebine mudehale edildi ise güncellenmeli.
* Avukat ve hukuki yardım. Uygulamaya önceden avukata soylemeniz gereken bilgileri girmeniz ve avukata iletmenizi kolaylastırmak. Bu bilgileri basınıza bir sey geldiginde hızla avukat gruplarına paylasmanız yararlı olabilir. Elinizden telefon alınmıs olabilir ama tutuklanmadan hemen önce boyle bir anons yapabilmek yararlı olabilir.
* Twitter, Facebook reputasyon integrasyonu. Twitter da gördügünüz tweetlerin dogrulugu ile ilgili geri besleme alabildiginiz bir uygulama. Dogrulugunu bildiginiz bir tweet'i dogrulama (DM gibi bir mekanizma ile)
* Tweetler puanlanarak Yukarı/Aşagı itilebilmeli. Bu sekilde dogru tweetlerin üste cıkması saglanmalı 
* Paylaşılan wireless erisim noktalarının listesi, lokasyonu ve şifrelerine offline erişim.
* Wireless modemlerin konfigürasyonlarının nasıl yapılacagı ile ilgili bilgiler, varsayılan sifre ve nasıl paylaşıma açılabilir. Açılan wirelessların nasıl kapatılacagı ile ilgili bilgilerin, firma ya da wireless sahibi ile paylaşılması.
* Paylaşılmış wireless kullanılırken bağlantıyı güvenli hale getirecek yöntemler. Örnegin transparan proxy ya da uygulama üzerinde önlemleri alan bir tarayıcı kullanılması. Ortak wireless kullanıldıgında kötü niyetli kullanıcılar şifre çalabilir.
* Provakatör listesi, DM ile yukarı/asağı itilebilen bir liste. Provakatörlerin cekilmiş fotografları, isim, esgal gibi bilgiler. Meydandaki polisle de paylaşılabilmeli ya da email gibi yollarla emniyete gönderilebilmeli.


##Durum bildirimi
* yesil --- kirmizi renk paletinden bir renk secimi
* GPS lokasyon ya da haritadan seçim (cihaz veriyorsa +DM puani, kullanıcı seçiyorsa puan katkısı olmamalı)
* Text içerik (opsiyonel)
* Fotograf (opsiyonel, exif bilgisi varsa +DM)
* Video (opsiyonel, exif bilgisi varsa +DM, band genişligi nedeni ile tercih edilmemeli)


##Dogrulama Mekanizması(DM)
* Kullanıcılar puanlanmalı (reputasyon)
* Kullanıcılar puanları ile yapabilecekleri işlemleri belirler
* Kullanıcı puanı (reputasyon) yaptığı işlemleri katsayı olarak etkiler. Örneğin bir tweetin dogrulugunu onayladığında, reputasyonu yüksek kullanıcı puanını 10 puan attırırken, duşuk kullanıcı ancak 1 puan arttırabilmeli.
* Kullanıcılar puanlamalarına göre seviyelere ayrılmalı. 
* Örnek olarak http://stackoverflow.com/  gibi soru sitelerindeki puanlama mekanizmaları incelenmeli
* GPS, fotograf, dijital imza gibi mekanizmalar puanlamayı etkilemeli
