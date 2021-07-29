# **Yoyuncak Oyun Alanı Yönetim Sistemi**
# [Playground Management System Project](#Playground)

Oyun alanlarına yatırım yapan insanlar gelen müşterilerin eğlenerek güzel vakit geçirmelerini amaçlamaktadır. Bunun için buralarda yetişkinlere ve çocuklara yönelik oyuncaklar ve oyun etkinlikleri bulunmaktadır. 

Oyun alanlarındaki oyuncakları ve oyun etkinliklerini aşağıdaki gibi gruplayabiliriz;

* Soft alanlar: Top havuzları, trambolin parklar vb.
* Kum havuzları.
* Jeton veya kart ile çalışan oyuncaklar:
    1. Ekranlı oyuncaklar.
    2. Kiddie Rides, olarak adlandırılan ekranlı yada binek tip oyuncaklar.

Bir oyun alanında yukarıdaki gruplardan bir veya bir kaçı aynı anda bulunurlar. 

Her bir işletmeci işletmesini en verimli ve kazançlı hale getirebilmek için bu alana giren müşterilerin ödedikleri ücretleri, oyun sürelerini, kampanyaları yönetmek ister. Sonuçta işletmeci bu işten **para kazanmak** için yatırım yapar. 

İyi yönetim iyi kazanç getirir.

![oyun alanı](img/alan.jpg)
Resim : Oyun alanı örneği.

Oyun merkezine/alanına gelen müşterilerin geldiği andan itibaren geçirdikleri süreçleri şu şekilde özetleyebiliriz:

1. Müşteri oyun makinesi veya etkinliği seçer.
2. Jeton alır veya karta kontur yükletir.   
3. Eğer oyun makinesini tercih etti ise kartı okutur veya jeton atar.
4. Eğer Top Havuzu veya kum havuzunu vb. seçti ise ;
    * Kalma süresini belirler.
    * Gerekli ücret miktarı için ödeme (Nakit, kredi kartı, jeton, temassız kart vb. ile) yapar. 
    * Görevli süre bitiminde oyun alanından misafiri çıkartmak için ailesi ile iletişime geçer.
  
  ![kum havuzu](img/kum_havuzu.jpg)
  Resim : Kum havuzu.
  
 Bu senaryo birçok oyun alanında yaklaşık aynıdır.
  
  ![Yönetim](img/Money-icon.png)Günümüz teknolojileri de dikkate alınarak bu basit yaklaşımda bile etkili ve verimli bir yönetim için :
 1. Günlük ve anlık kazanç bilinmeli ve geriye dönük haftalık-aylık-yıllık vb. saklanarak gerektiğinde incelenebilir olmalı. 
 
 2. Günlük veya anlık müşteri sayısı takip edilebilmeli ve kaydedilmeli.
 
 3. İşletme kart kullanıyorsa kullanımdaki kartlar ve stok takip edilebilmeli.
 
 4. İşletmede yapılan kampanyalar vb. ücret sistemine yansıtılmalı ve takip edilebilmeli.
 
 5. İşletmede ürün satışı yapılıyorsa bu ürünlerin satışı ve stok takibi yapılıp kaydedilmeli.
 
 6. Top havuzu ve kum havuzunda müşterilere farklı süre seçenekleri olmalı.

 7. Top havuzu ve kum havuzunda bulunan müşteriler için müşteri takip ve ödeme sistemi olmalı.

 8. Anlık ve günlük olarak hangi oyuncaktan veya oyun etkinliğinden ne kadar kazanıldığı kaydedilmeli ve takibi yapılmalı.

 9. Sistemde yaşanması muhtemel bir takım problemlere (PC bozulması, internet bağlantı arızaları vb.)  karşı alternatif çözümler olmalı.
 
Yukarıda sayılan bütün maddelerde belirtilen konulara işletmeci tarafından web ve mobil  üzerinden anlık ve geriye dönük olarak erişilebilir olmalı. 

Böylece işletmeci anlık-günlük-haftalık-aylık-yıllık vb. durum değerlendirmesi yaparak müşteri ilgi ve alakasına göre süre ve fiyatlandırmada, oyun makinesi değiştirme yada güncelleme, personel sayısı vb. değişikliklere karar verip uygulayabilmelidir.

![çözüm:](img/human-brain-icon_72x72.png)**Yoyuncak Oyun Alanı Yönetim Sistemi yaklaşımı**, işletmeciye oyun alanının yapısına, örnek veya uygulanmak istenen yönetim senaryosuna göre gerekli tüm bileşenler için çeşitli çözümler sunarak işletmecinin oyun alanını en verimli-kazançlı şekilde kullanabilmesini amaçlar. Sunulan bütün bu çözümler yukarıda açıklanmaya çalışılan maddeleri bütünüyle kapsamaktadır. İşletmecinin ihtiyacına uygun bileşenler  oyun alanına uygulanır.

## Yoyuncak Oyun Alanı Yönetim Sisteminin Bileşenleri

Yukarıda yaptığımız analizdeki şartları sağlamak amacıyla sistemimiz aşağıdaki öğelerden oluşmaktadır.

* Oyun alanı yönetim programı.
* Kartlı sistem jeton kanalı yükleme cihazı. (Kablosuz haberleşme ve IOT  arge de).
* Kartlı sistem jeton kanalları (Kablosuz haberleşme ve IOT arge de).
* Bulut sistemi (Web ve mobil ).

<small>*( Geliştirme işlemi devam ediyor …)*</small>
* Self servis temassız kart verme ve yükleme otomatı.

![Bilesenler](img/bilesenler.png)
Resim : Etkileşimli oyun alanı.

### Oyun alanı yönetim programı ile yapabilecekleriniz:
###

![Ana Ekran](img/ana_ekran1.jpg)Resim: Oyun alanı yönetim programı ana ekranı.

1. Kartlı sistemlerde kartı şifreleme-kontur yükleme ve web- yerel veri tabanına kaydetme. Kart bilgisini görme. Ayar kartları oluşturma.
2. Kart stok takibi. Mevcut durumun web-yerel veri tabanına kaydetme.
3. Gün sonunda veya kasiyer değişimlerinde gün sonu veya kasa devretme işlemi yapma ve web-yerel veri tabanına kaydetme.
4. Ürün satışı, stok takibi. Mevcut durumun web -yerel veri tabanına kaydedilmesi.
5. Yönetici ve kasiyer olarak yetkilendirilmiş şifreli girişlerin olması. İstenilen sayıda kasiyer ekleyebilme.
6. Kasiyerlerin programa giriş ve çıkışlarının takibini yapabilme.
7. Havuzdaki (Kum-top) müşterileri zamanı olarak takip etme açısından çeşitli listeleri (iptal, süreli, süresiz, günlük vb) gösterme.
8. Kum havuzu ve top havuzlarındaki müşterilerin takip edilmesi;
    * Havuzdaki müşterilerin ilk girişte kaydını alma, web-yerel veri tabanına kaydetme.
    * Etiket kâğıdına misafir başlama ve bitiş zamanlarını yazdırarak bir tanesini misafirin sırtına yapıştırma diğerini de müşteriye verme. (Misafir güvenliği ve takip için)
    * Müşterinin farklı kalma sürelerini belirleyebilme ve bunları fiyatlandırma.
    * Seçilen süreyle ilgili ücreti, nakit, kredi kartı ve temassız karttan tahsil edebilme.
    * İçerde bulunan anlık günlük müşteri sayısını gösterme web-yerel veri tabanına kaydetme.
    * Aynı anda kum havuzu ve top havuzunda bulunan müşterileri ayrı ayrı takip etme.
    * Müşterilerin süresi bitmeden 5dk öncesinde kasiyere haber verme. 
    * Müşterilere izin verme (tuvalet, yemek vb.) işlemlerinde süreyi dondurma.
    * Müşterileri havuz dışına alma.
    * İsme göre müşteri arama.
    * Ayakkabılık varsa müşteri ayakkabı no takibi yapma.
    * İptal işlemi uygulayabilme. İptal işleminden sonra temassız karta iptal edilen kontürün geri yüklenmesi.
    * Promasyon ve kampanya takibi yapabilme.
    * Çeşitli indirim seçenekleri uygulayabilme( kardeş indirimi vb.).
    * Belirlenen süre tarifeleri arasında geçiş yapma veya müşteriye ek süre (belirlenen tarifeler kadar) verebilme. İndirim alan misafire süre geçişlerinde de indirim uygulama.
    * Misafir bilgi güncelleme yapma.
    * Hızlı grup misafir kaydı yapma.
9. Top ve kum havuzları için abonelik oluşturma ve gelen abonelerin ödemelerini temassız karttan alabilme.
###
![abone :](img/abone_ekrani.jpg)Resim : Kum-top  havuzu abone işlemleri.

10. Farklı çalışma modları:

    Program bu çalışma modları ile bir oyun alanında farklı noktalarda farklı işlevleri gerçekleştirip raporlayabilmektedir. Örneğin Oyun alanının girişinde satış modunda temassız karta kontür yükleyip ürün satılmasını sağlarken top havuzu veya kum havuzunun ya da müşterinin süreli takibinin yapılması gereken herhangi bir noktada takip modunda çalışmaktadır.
    
    * Satış Çalışma Modu : Program sadece kart yükleme ve ürün satışı işlemlerini gerçekleştirir. Gün sonunda ciro buradan hesaplanır.
    * Takip Çalışma Modu : Programı sadece kum ve top havuzunun takibini yapar.
    * Satış-Takip Çalışma Modu : Program hem satış hem de takip yapar
11. Kartlara ait varsa yada kullanılmak isteniyorsa deposito bilgilerini takip eder.
12. Her bir karttın anlık olarak kullanım bilgisini gösterebilir. 
13. Veri toplama kartı ile her oyuncaktan istenilen peryotta bilgi toplama ve kaydetme.

<small>*( Geliştirme işlemi devam ediyor …..)*</small>

14. Kartlı sistem jeton kanalı programlama cihazına kablosuz olarak gelen oyun makinelerine ait bilgileri alır web-yerel veri tabanına kaydeder.
15. Her oyun makinesinin kablosuz ağdaki durumunu gösterme ve oyun makinelerindeki jeton kanallarına ait çeşitli ayarları yapma

### Kartlı Sistem Jeton Kanalı Yükleme Cihazı Özellikleri :
###
![](img/kart_okuyucu_yukleyici.png)  ![](img/kart_okuyucu_yukleyici2.png)

Resim : Yükleme cihazı PCB görünümü.

1. Mikrodenetleyici tabanlı gömülü sistem mimarisine göre dizayn edilmiş tasarım..
2. MIFARE kartları şifreleme, kontur yükleme, okuma, silme işlemlerini yapma.
3. PC den bağımsız olarak çalışma. (Dokunmatik ekran programlama paneli ile. İsteğe bağlı olarak ayrıca yapılır.)
4. PC ye tak-kullan olarak bağlanma (Sürücü kurmak gerekmez).
5. Sesli ve ışıklı durum göstergeleri.

<small>*( Geliştirme işlemi devam ediyor …..)*</small>

6. Kablosuz jeton kanallarıyla birlikte bir kablosuz ağ oluşturma ve ağı yönetebilme. Kablosuz jeton kanallarından gelen bilgileri web-yerel veri tabanına kaydedilmek üzere PC ye gönderme.
7. Oyun makinelerinin çeşitli ayarlarını kablosuz olarak gerçekleştirme.

### Kartlı Sistem Jeton Kanalı Özellikleri :
1. Mikrodenetleyici tabanlı gömülü sistem mimarisine göre dizayn edilmiş tasarım.
2. Şifrelemesine uygun MIFARE kartları okuyabilme. Kontur miktarını düşüp karta tekrar geri yükleme ve son durumu gösterme.
3. Işıklı se sesli uyarı.
4. Ayar kartlarıyla ayarları değiştirilebilir olma.
5. 	Klasik jeton kanalları yerine kolayca monte edilme.

<small>*( Geliştirme işlemi devam ediyor …..)*</small>

6. Kablosuz olarak verileri ana makineye gönderme.
7. Kablosuz olarak gelen ayar bilgilerini alma ve uygulama.

### Bulut Sistemi (Web ve mobil ) Özellikleri :
###
![](img/web.png)Resim : Bulut sisteminde bulunan web sayfası anlık ve son gun sonu görünümü.

1. Günlük ve anlık müşteri sayısını, ciroyu vb.  takip edebilme.
2. Günsonu işlemlerini görme.
3. Kasiyer girişlerini takip etme.
4. Farklı raporlama seçenekleri.
5. Süre ve fiyatları güncelleme.
6. İşletmecinin oyun alanı hakkında çeşitli verilerin analizlerini yapabilmesini sağlama.
 
Yukarıda anlatılan bütün bu çözüm yaklaşımlarının yanında işletmecinin isteğine göre oyun alanının yapısına uygun farklı çözümler de geliştirilerek işletmeciye sunulabilmektedir.

![](img/draw-icon.png) 08.06.2021 YOYUNCAK ARGE ve DANIŞMANLIK  

## Playground
## Management System Project

People investing in playgrounds aim to have their customers have a good time while having fun. For this, there are toys and game activities for adults and children.





