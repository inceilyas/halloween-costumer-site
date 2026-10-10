title: Gizlilik Politikası
description: {{APP_NAME}} fotoğraflarını ve verilerini nasıl işler: yapay zeka hizmetine ne gönderilir, hukuki dayanaklar, neyin ne kadar süre saklandığı ve dünya genelindeki haklarının neler olduğu.

# Gizlilik Politikası

> Yürürlük tarihi: {{EFFECTIVE_DATE}}

{{APP_NAME}} ("Uygulama"), üçüncü taraf bir yapay zeka görsel hizmetini kullanarak fotoğraflarını Halloween canavarı portrelerine dönüştürür. Bu politika, Uygulamanın hangi bilgileri işlediğini, bunu neden ve hangi hukuki dayanakla yaptığını, bilgilerin kimlere ulaştığını, ne kadar süre saklandığını ve nerede yaşıyor olursan ol hangi hak ve seçeneklere sahip olduğunu açıklar. Uygulamayı {{DEVELOPER_NAME}} ("biz") işletir; kişisel verilerinin veri sorumlusu (verilerin hangi amaçla ve hangi yöntemlerle işleneceğini belirleyen taraf) da odur. İletişim bilgilerimiz 14. bölümdedir.

## 1. Kısa özet

- Seçtiğin fotoğraflar, yalnızca istediğin portreyi oluşturmak için dış bir yapay zeka hizmetine (OpenAI) gönderilir. Bu ilk kez gerçekleşmeden önce açık iznini isteriz; izni istediğin zaman geri alabilirsin.
- Gönderdiğin fotoğrafları saklamayız. Onları bellekte yapay zeka hizmetine iletir, sonucu telefonuna geri göndeririz. Uygulama, özgün fotoğrafın küçültülmüş bir kopyasını yalnızca telefonunda, önce/sonra karşılaştırması için saklar (bölüm 2c).
- Hazır portrelerin telefonunda saklanır. Portre hazırlanırken bağlantın kesilirse ya da Uygulama kapatılırsa portre kaybolmasın diye, yeni oluşturulan her portrenin şifreli bir kopyasını sunucumuzda en fazla 24 saat tutarız. Bu kopya yalnızca portreyi telefonuna ulaştırmak için kullanılır ve telefonun kaydedildiğini onaylar onaylamaz, en geç 24 saat sonra silinir.
- Fotoğraflarını ya da yüzünü yapay zeka modellerini eğitmek, reklam veya analiz için kullanmayız. İnsanları yüzlerinden tanımayız ve kimliklerini belirlemeyiz.
- Hesap yoktur; Uygulamada reklam ya da analiz SDK'sı yoktur; diğer şirketlerin uygulama ve sitelerinde seni izleme de yoktur. Sunucumuz, anonim kimliğini ve satın alım kayıtlarını (asla fotoğrafları değil) bir abonelik analizi sağlayıcısıyla (RevenueCat, 4. bölüm) paylaşır.
- Verilerini Uygulama içinden istediğin zaman silebilir (Profil > Tüm verilerimi sil) ve yapay zeka iznini geri alabilirsin (Profil > Yapay zeka iznini geri çek).

## 2. İşlediğimiz bilgiler

**a. Seçtiğin ya da çektiğin fotoğraflar.** Kitaplığından bir fotoğraf seçtiğinde ya da kamerayla çektiğinde ve portre oluşturmak için dokunduğunda, fotoğraf (yeniden boyutlandırılmış bir JPEG) ve seçtiğin görünüm arka uç sunucumuza ve oradan yapay zeka hizmetine gönderilir. Her kişi için ayrı selfie'lerle bir grup ya da çift görünümü seçersen, her selfie gönderilir. Fotoğraflarda senin ve başka insanların yüzleri görünebilir. Yalnızca açıkça seçtiğin fotoğraflara erişiriz; Uygulama fotoğraf kitaplığını taramaz.

**b. Cihazında yüz kontrolü.** Bir fotoğraf gönderilmeden önce Uygulama, uygun sayıda yüz olup olmadığını (örneğin çift görünümü için tam olarak iki) kontrol etmek üzere cihazında Apple'ın Vision çerçevesini kullanır. Bu kontrol tamamen telefonunda çalışır. Yüzlerin nerede olduğunu ve kaç tane olduğunu bulur. Yüz şablonu ya da herhangi bir biyometrik tanımlayıcı oluşturmaz, kimin kim olduğunu belirlemez ya da tanımaz; sonuçları, yapay zeka hizmetine verilecek yönergeleri yazmak için kullanılan yüz sayısı dışında hiçbir yere gönderilmez. Tek fotoğraftan yapılan bir üretimde yüzün konumu (fotoğrafa göre normalleştirilmiş basit bir dikdörtgen) ayrıca yalnızca telefonundaki üretim verisinde, önce/sonra karşılaştırmasını hizalamak için saklanır (bölüm 2c).

**c. Oluşturulan portreler.** Yapay zeka hizmetinin sonucu Uygulamaya döner ve telefonuna kaydedilir. Bağlantı koparsa portreyi telefonuna ulaştırmak için, oluşturulan her portrenin geçici bir kopyası bulut depolamamızda şifreli olarak en fazla 24 saat tutulur; selfie'lerini ve diğer girdi fotoğraflarını sunucularımızda hiçbir zaman saklamayız. Yalnızca telefonunda, tek fotoğraftan yapılan bir üretim (solo ya da tek bir grup fotoğrafı) portrenin yanında özgün fotoğrafın küçültülmüş bir kopyasını (uzun kenar 1280 piksel) de tutar; bu, önce/sonra karşılaştırmasını göstermek içindir. Bu kopya hiçbir zaman yüklenmez, cihaz yedeklerinin dışında tutulur ve üretimle birlikte ya da Tüm verilerimi sil ile silinir. Ayrı selfie'lerle yapılan üretimlerde ve 24 saatlik teslim kopyamızdan kurtarılan portrelerde özgün fotoğraf kopyası yoktur.

**d. Anonim tanımlayıcı ve krediler.** Uygulama, kurulumun için anonim bir Firebase tanımlayıcısı oluşturur. Bunu kredi bakiyeni tutmak ve satın alımları ile kredi hareketlerini (işlem kimliği, ürün, tarih) kaydetmek için kullanırız. Hesap açmanı istemeyiz; Uygulamada adını, e-posta adresini ya da telefon numaranı toplamayız. Yapay zeka hizmetini çağırırken, anonim kimliğinden tek yönlü anahtarlı bir özetleme (hash) ile türetilmiş takma adlı bir tanımlayıcı ekleriz; bu gerçek tanımlayıcın değildir ve yapay zeka hizmeti onu seninle ilişkilendiremez. Kötüye kullanımı tespit etmesine yardımcı olur.

**e. Satın alımlar.** Satın alımları ve abonelikleri Apple işler. Ödeme kartı bilgilerini ya da Apple Hesabı bilgilerini hiçbir zaman almayız. Kredi verebilmemiz veya kaldırabilmemiz için bir işlemin onayını (işlem kimliği, ürün, tarihler, yenileme veya iade durumu) alırız. Satın Alımları Geri Yükle'ye dokunursan Uygulama, Apple'ın imzaladığı satın alım kayıtlarını doğrulayıp satın alımlarını ve kalan kredilerini bu cihazdaki Uygulamayla yeniden ilişkilendirebilmemiz için sunucumuza gönderir. Bu kayıtlar ürünü, tarihleri ve bizim oluşturduğumuz, kuruluma özgü rastgele satın alım tanımlayıcısını içerir; adını, e-posta adresini ya da ödeme bilgilerini içermez. Kayıtlar Uygulamanın başka bir kurulumuyla eşleşirse, o kurulumun kalan kredileri bu kuruluma taşınır (kopyalanmaz). Geri yükleme için oturum açmak gerekmez ve yeni türde kişisel veri oluşturmaz. Bu satın alım kayıtlarını anonim tanımlayıcınla birlikte, abonelik ve gelir istatistiklerini görebilmek için sunucumuzdan RevenueCat'e (4. bölüm) de iletiriz; Uygulamanın kendisinde RevenueCat yazılımı yoktur ve RevenueCat'e hiçbir şey göndermez.

**f. Cihaz bütünlüğü.** Hizmeti kötüye kullanıma karşı korumak için, isteklerin Uygulamanın gerçek bir kopyasından geldiğini doğrulamak amacıyla Apple'ın App Attest'ini (Firebase App Check üzerinden) ve bir cihazın ücretsiz ilk portresini kullandığını Apple tarafından saklanan tek bir açık/kapalı ayarıyla hatırlamak için Apple'ın DeviceCheck'ini kullanırız. DeviceCheck bize kim olduğunu söylemez.

**g. Teknik günlükler.** Bulut hizmetlerimiz ve yapay zeka hizmeti; güvenlik için ve hizmeti işletmek amacıyla IP adresi, istek zamanı ve hata kodları gibi teknik bilgileri günlüğe kaydedebilir. Kendi kodumuz fotoğrafları, yüz verilerini ya da kişisel verileri günlüklere yazmaz. Bu günlükleri hakkında profil çıkarmak için kullanmayız.

**h. Destek mesajları.** Bize e-posta yazarsan e-posta adresini ve yazdıklarını alırız; bunları yalnızca yanıt vermek için kullanırız.

**i. Cihazdaki ayarlar.** Uygulama telefonunda basit tercihleri saklar (örneğin tanıtımı tamamladığını ve yapay zeka bildirimini kabul ettiğini).

Kesin konumunu, kişilerini, sağlık verilerini ya da gezinme geçmişini toplamayız.

## 3. Bilgileri neden kullanırız ve hukuki dayanaklar

| Amaç | Bilgi | Hukuki dayanak (GDPR ve UK GDPR; diğer kanunlardaki eşdeğer dayanaklar) |
| --- | --- | --- |
| İstediğin portreyi oluşturmak: fotoğraflarını ve seçilen görünümü yapay zeka hizmetine göndermek | Fotoğraflar, seçilen görünüm, yüz sayısı, takma adlı tanımlayıcı | İlk oluşturmadan önce Uygulamada verdiğin rızan (Madde 6(1)(a)). Rızanı istediğin zaman geri alabilirsin; geri alma, öncesindeki işlemeyi etkilemez. |
| Krediler, satın alımlar, abonelikler, Satın Alımları Geri Yükle, kredi iadeleri | Anonim tanımlayıcı, kredi bakiyesi, satın alım kayıtları | Seninle aramızdaki sözleşmenin ifası (Madde 6(1)(b)); kanunen tutmamız gereken kayıtları tutmak (Madde 6(1)(c)) |
| Abonelikleri ve geliri anlamak (abonelik analizi) | Anonim tanımlayıcı, Apple tarafından imzalanmış satın alım ve yenileme kayıtları | Ücretli bir hizmeti işletmedeki ve geliştirmedeki meşru menfaatlerimiz (Madde 6(1)(f)). İtiraz edebilirsin (7. bölüm). |
| Dolandırıcılığı ve kötüye kullanımı önlemek, cihaz başına bir ücretsiz portre kuralını uygulamak, hizmeti güvende tutmak (App Check, DeviceCheck, hız sınırları, güvenlik filtreleri, günlükler) | Anonim tanımlayıcı, cihaz bütünlüğü sinyalleri, teknik günlükler | Hizmeti, diğer kullanıcıları ve kendimizi korumaktaki meşru menfaatlerimiz (Madde 6(1)(f)). İtiraz edebilirsin (7. bölüm). |
| Destek taleplerini yanıtlamak | E-posta adresi, mesaj, Destek Kimliği | Seninle aramızdaki sözleşme ve sana yardım etmedeki meşru menfaatimiz |
| Kanuna uymak ve hukuki talepleri yönetmek | 6. bölümde açıklanan kayıtlar | Hukuki yükümlülük ve meşru menfaatler |

**Yüzler ve fotoğraflar.** Resimlerindeki yüzler ve fotoğraflar yalnızca istediğin portreyi oluşturmak için kullanılır. Hiçbir yapay zeka modelini eğitmek veya geliştirmek, reklam ya da pazarlama, analiz ya da profilleme için kullanılmaz; bu amaçlarla satılmaz veya paylaşılmaz. Yüz veritabanı oluşturmayız ve fotoğrafları kimse hakkında hassas özellikler çıkarmak için analiz etmeyiz.

Fotoğrafları yapay zeka hizmetine göndermeyi kabul etmezsen Uygulamayı yine açabilirsin ama portre oluşturamaz.

## 4. Bilgileri kimler alır

Bilgileri yalnızca Uygulamayı çalıştırmak için gereken hizmet sağlayıcılarla paylaşırız:

- **OpenAI** (görsel oluşturma). Fotoğrafların ve seçilen görünüm, portreni üretmek için OpenAI'ın API'sine gönderilir. OpenAI, veri işleyen olarak hareket eder. OpenAI'ın yayımlanmış API veri politikasına göre, API'ye gönderilen veriler müşteri kabul etmedikçe (biz kabul etmedik) OpenAI'ın modellerini eğitmek ya da geliştirmek için kullanılmaz; API içeriği kötüye kullanım izleme günlüklerinde en fazla 30 gün, kanunen gerekiyorsa veya hizmetleri korumak için gerekiyorsa daha uzun süre tutulabilir. OpenAI'ın politikası: https://developers.openai.com/api/docs/guides/your-data . OpenAI ayrıca yüklenen görselleri çocuk cinsel istismarı materyali açısından tarayabilir ve işaretlenen bir görseli o politikada açıklandığı gibi inceleme için saklayabilir.
- **Google (Firebase ve Google Cloud)** (arka uç barındırma, anonim tanımlayıcı, kredi ve satın alım kayıtları, uygulama bütünlüğü kontrolleri, oluşturulan portrelerin geçici şifreli depolanması). Google, kendi veri işleme şartları kapsamında veri işleyen olarak hareket eder. Arka uç sunucumuz Amerika Birleşik Devletleri'nde (Iowa) çalışır.
- **RevenueCat, Inc.** (Amerika Birleşik Devletleri) (abonelik ve satın alım analizi). Sunucumuz RevenueCat'e anonim tanımlayıcını ve Apple'ın satın alımların için imzaladığı satın alım kayıtlarını (ürün, tarihler, ortam, rastgele satın alım tanımlayıcısı ile yenileme, iade ve iptal olayları) gönderir. RevenueCat, veri işleyen olarak hareket eder. Fotoğraflar, yüzler, adlar, e-posta adresleri ya da cihaz tanımlayıcıları gönderilmez ve Uygulamada RevenueCat yazılımı yoktur. Tüm verilerimi sil'i kullandığında, RevenueCat'ten de anonim tanımlayıcına ait kaydını silmesini isteriz.
- **Apple** (App Store satın alımları, App Attest, DeviceCheck ve portrelerini kendi başlattığın iOS paylaşım sayfasıyla isteğe bağlı paylaşmak). Apple, kendi hizmetleri bakımından bağımsız bir veri sorumlusu olarak hareket eder.
- **Yetkili makamlar ya da halefler**; kanunen gerektiğinde, hakları ve güvenliği korumak için ya da bir işletme devri kapsamında, gerekli olan hallerde bildirimle.

Kişisel bilgilerini satmayız ve bağlamlar arası davranışsal reklamcılık için paylaşmayız.

Bir portreyi başka bir uygulamaya paylaştığında (örneğin paylaşım sayfasından), paylaştığın içerik için o uygulamanın kendi gizlilik politikası geçerlidir.

## 5. Uluslararası aktarımlar

Merkezimiz Türkiye'dedir; hizmet sağlayıcılarımız verileri Amerika Birleşik Devletleri'nde ve faaliyet gösterdikleri diğer ülkelerde işleyebilir. Uygulamayı Avrupa Ekonomik Alanı'nda, Birleşik Krallık'ta, İsviçre'de, Türkiye'de, Brezilya'da, Güney Kore'de, Japonya'da ya da başka bir yerde kullanırsan, bilgilerin bu nedenle veri koruma mevzuatı seninkinden farklı olabilecek ülkeler dahil başka ülkelere aktarılır.

Bu aktarımlar için, uygulanabildiği ölçüde, kanununun gerektirdiği güvenceleri kullanırız: yeterlilik kararı (örneğin alıcının katıldığı durumlarda AB-ABD Veri Gizliliği Çerçevesi), hizmet sağlayıcılarımızın veri işleme şartlarındaki standart sözleşme hükümleri (AB ve Birleşik Krallık eki), yerel kanunun tanıdığı diğer hukuka uygun mekanizmalar (8. bölüme bak) ve kanunun izin verdiği hallerde rızan. Ayrıca gönderilenleri gerekenle sınırlarız, şifreli bağlantılar kullanırız ve adını, e-posta adresini ya da gerçek hesap tanımlayıcını yapay zeka hizmetine göndermeyiz. Güvenceler hakkında bizden bilgi isteyebilirsin (14. bölüm).

## 6. Bilgileri ne kadar süre saklarız

| Bilgi | Saklama süresi |
| --- | --- |
| Bir oluşturma için gönderilen fotoğraflar | Bizde saklanmaz. İstek işlenirken yalnızca bellekte tutulur. Yapay zeka hizmeti bunları kötüye kullanım izleme günlüklerinde en fazla 30 gün saklayabilir (4. bölüme bak). |
| Oluşturulan portreler ve tek fotoğraftan yapılan üretimlerde özgün fotoğraf kopyası | Sen silene ya da Tüm verilerimi sil'i kullanana kadar telefonunda. Küçültülmüş özgün fotoğraf kopyası ve yüz dikdörtgeni telefonundan hiç çıkmaz ve cihaz yedeklerinin dışında tutulur. Portrenin geçici bir teslim kopyası sunucumuzda şifreli olarak en fazla 24 saat tutulur (telefonun kaydı onayladığında ve Tüm verilerimi sil ile silinir). |
| Anonim tanımlayıcı, kredi bakiyesi, kredi hareketleri, satın alım kayıtları (Satın Alımları Geri Yükle için kullanılanlar dahil) | Verilerini Uygulamada silene kadar. Bakiyesi sıfır olan, etkin aboneliği bulunmayan ve 24 ay boyunca Uygulamanın hiç kullanılmadığı kayıtlar, anonim oturum kaydıyla birlikte otomatik olarak silinir (her gün kontrol edilir). |
| RevenueCat'teki kayıt (anonim tanımlayıcı, satın alım ve yenileme kayıtları) | Verilerini Uygulamada silene kadar ya da kayıt 24 aylık hareketsizlikten sonra otomatik olarak silinene kadar (yukarıya bak); ardından RevenueCat'ten silmesini isteriz. Yedek kopyalar için RevenueCat'in kendi şartları geçerlidir. |
| Verilerini Uygulamada sildikten sonra ya da otomatik silmeden sonra satın alım işlem kayıtları | İşlem kimliği, ürün ve tarihler; iadeleri işlemek, kredinin iki kez verilmesini önlemek ve kanunun gerektirdiği hallerde (örneğin muhasebe için) anonim tanımlayıcınla hiçbir bağlantı olmadan saklanır. Etkin bir aboneliğin varsa, anonimleştirilmiş abonelik kaydı, mevcut dönemin kalan haftalık kredilerini de, yine anonim tanımlayıcınla hiçbir bağlantı olmadan saklar; böylece abonelik yeni bir kurulumda geri yüklenebilir (Satın Alımları Geri Yükle). Bu krediler yalnızca bunun için kullanılır ve bu işlem kayıtları kadar süreyle saklanır. |
| Silme işareti | Verilerini sildikten sonra, silinen kaydın yeniden oluşturulamaması için eski rastgele anonim tanımlayıcını ve silme zamanını saklarız. Başka hiçbir bilgi içermez. |
| Teknik günlükler | Güvenlik ve işletim için gereken sınırlı bir süre (örneğin Firebase Authentication IP adreslerini birkaç hafta günlüğe kaydeder). |
| Destek e-postaları | Sana yardım etmek için gereken süre boyunca, sonra silinir. |

## 7. Haklarının ve seçeneklerin

Yaşadığın yere bağlı olarak şu haklardan bazılarına ya da tamamına sahipsin: verilerini işleyip işlemediğimizi öğrenme ve bir kopyasını alma (erişim); düzeltme; silme; işlemeyi kısıtlama; verilerini taşınabilir biçimde alma; meşru menfaate dayanan işlemeye itiraz etme; rızanı istediğin zaman geri alma; hukuki veya benzer şekilde önemli sonuçlar doğuran, yalnızca otomatik işlemeye dayalı kararlara tabi olmama (biz hiçbirini vermiyoruz) ve bir veri koruma otoritesine şikayette bulunma.

Nasıl kullanacağın:

- **Tüm verilerimi sil (Uygulamada).** Profil > Tüm verilerimi sil; telefonunda saklanan portreleri, özgün fotoğrafları, selfie küçük resimlerini ve yapay zeka iznini kaldırır ve anonim tanımlayıcına bağlı sunucu tarafı kaydı (kredi bakiyesi ve satın alım kayıtları) silmemizi, ayrıca RevenueCat'ten bu tanımlayıcıya ait kaydı silmesini ister. Bunu yaptığında kullanılmamış kredi paketleri kaybolur. Etkin bir aboneliğin kalan haftalık kredileri kaybolmaz: aboneliği yeni bir kurulumda geri yükleyebilmen için anonimleştirilmiş abonelik kaydıyla birlikte saklanır (bölüm 6). Yalnızca Uygulamayı silmek sunucu tarafı kaydı silmez.
- **Yapay zeka iznini geri çek.** Profil > Yapay zeka iznini geri çek. Sen yeniden kabul edene kadar fotoğraflar tekrar gönderilmez.
- **Erişim, taşınabilirlik, düzeltme, kısıtlama, itiraz.** {{SUPPORT_EMAIL}} adresine e-posta gönder ve kaydını bulabilmemiz için Profil sekmesinde görünen Destek Kimliğini ekle. Uygulama anonim olduğu için onsuz verilerini bulamayız. Destek Kimliğine bağlı kaydı (kredi bakiyesi, kredi hareketleri ve satın alım kayıtları) sana yaygın, makine tarafından okunabilir bir biçimde göndeririz. Portrelerin zaten telefonunda.
- **Fotoğraf erişimi.** Kamera ve fotoğraf izinlerini iOS Ayarlar'ından değiştirebilirsin. Uygulama sistemin fotoğraf seçicisini kullanır; bu, yalnızca seçtiğin fotoğraflara erişim verir. Kitaplığına yalnızca Kaydet'e dokunduğunda kaydeder.
- **Abonelikler** Apple Hesabı ayarlarından yönetilir ya da iptal edilir (Kullanım Koşullarımıza bak).

Talebini bir ay içinde yanıtlarız (GDPR ve UK GDPR; karmaşık taleplerde süreyi iki ay daha uzatabiliriz ve sana bildiririz) veya sana uygulanan kanunun belirlediği süre içinde. Talebin Destek Kimliğinin sahibinden geldiğini doğrulamanı isteyebiliriz. Ayrıca bulunduğun yerdeki veri koruma otoritesine şikayette bulunabilirsin (AEA'da yaşadığın ya da çalıştığın ülkenin otoritesi; Birleşik Krallık'ta Information Commissioner's Office; Türkiye'de Kişisel Verileri Koruma Kurulu; Brezilya'da ANPD; Güney Kore'de PIPC; Japonya'da PPC). Önce endişeni çözme fırsatını bize verirsen memnun oluruz.

## 8. Bölgelere özgü bilgiler

### 8.1 Avrupa Ekonomik Alanı, Birleşik Krallık ve İsviçre

Veri sorumlusu {{DEVELOPER_NAME}}'dır. Hukuki dayanaklar 3. bölümde, aktarımlar 5. bölümde, saklama süreleri 6. bölümde, haklarının ise itiraz etme ve rızayı geri alma hakları dahil 7. bölümde yer alır. Veri koruma görevlisi atamadık; gizlilikle ilgili sorular 14. bölümdeki adrese gönderilir. Ülkenin kanunu kişisel verilerin işlenmesine rıza verme yaşını 13'ten yüksek belirliyorsa (örneğin birçok Avrupa ülkesinde 14 ile 16 arası), 9. bölüme bak.

### 8.2 Türkiye (6698 sayılı Kanun, KVKK)

Veri sorumlusu {{DEVELOPER_NAME}}'dır. Kişisel verileri 3. bölümdeki amaçlarla; açık rızana (fotoğrafların yapay zeka hizmetine gönderilmesi), sözleşmenin kurulması ve ifasına, meşru menfaatlerimize (dolandırıcılığın önlenmesi ve güvenlik) ve hukuki yükümlülüklere dayanarak işleriz. 6698 sayılı Kişisel Verilerin Korunması Kanunu'nun 11. maddesi uyarınca; kişisel verilerinin işlenip işlenmediğini öğrenebilir, bilgi talep edebilir, işlenme amacını ve amacına uygun kullanılıp kullanılmadığını öğrenebilir, yurt içinde veya yurt dışında aktarıldığı üçüncü kişileri bilebilir, düzeltilmesini veya silinmesini isteyebilir, bu işlemlerin üçüncü kişilere bildirilmesini isteyebilir, aleyhine bir sonucun ortaya çıkmasına itiraz edebilir ve zararın giderilmesini talep edebilirsin. Bize 14. bölümdeki adresten, Destek Kimliğinle birlikte başvurabilirsin; en geç otuz gün içinde yanıt veririz. Memnun kalmazsan Kişisel Verileri Koruma Kurulu'na şikayette bulunabilirsin. Veriler yurt dışına (5. bölüm) 6698 sayılı Kanun'un 9. maddesindeki koşullara uygun olarak aktarılır.

### 8.3 Brezilya (LGPD)

Veri sorumlusu {{DEVELOPER_NAME}}'dır; veri sahipleri için iletişim noktası 14. bölümdeki adrestir. 13.709/2018 sayılı Kanun'un (Lei Geral de Proteção de Dados, LGPD) 7. maddesi uyarınca hukuki dayanaklarımız rıza, sözleşmenin ifası, hakların düzenli kullanılması ve meşru menfaatlerdir. 18. maddedeki haklara sahipsin (işlemenin teyidi, erişim, düzeltme, anonimleştirme, engelleme veya silme, taşınabilirlik, paylaşım hakkında bilgi, rızayı reddetmenin sonuçları hakkında bilgi ve rızanın geri alınması) ve ANPD'ye (Autoridade Nacional de Proteção de Dados) başvurabilirsin. Uluslararası aktarımlar 5. bölümde ve LGPD'nin 33. maddesinde belirtildiği gibi yapılır.

### 8.4 Güney Kore (PIPA)

Kişisel bilgileri (2. bölüm) yalnızca 3. bölümdeki amaçlarla işler ve 6. bölümdeki sürelerce saklarız. Kişisel bilgileri 4. bölümde açıklananlar dışında üçüncü taraflara sağlamayız. 4. bölümde açıklanan işlemeyi OpenAI, Google ve RevenueCat'e emanet ederiz ve onları sözleşme şartlarıyla denetleriz. Fotoğrafların ve ilgili bilgiler, Uygulamada verdiğin rızayla, yurt dışına aşağıdaki gibi aktarılır:

| Alıcı ve ülke | Öğeler | Amaç | Ne zaman ve nasıl | Saklama |
| --- | --- | --- | --- | --- |
| OpenAI, Amerika Birleşik Devletleri | Fotoğraflar, seçilen görünüm, takma adlı tanımlayıcı | Portreyi oluşturmak | Her portre oluşturduğunda, şifreli ağ üzerinden | Kötüye kullanım izleme günlüklerinde en fazla 30 gün |
| Google (Firebase ve Google Cloud), Amerika Birleşik Devletleri | Anonim tanımlayıcı, kredi ve satın alım kayıtları, oluşturulan portrenin geçici kopyası | Barındırma, kredi defteri, portrenin teslimi | Uygulamayı her kullandığında, şifreli ağ üzerinden | 6. bölümdeki gibi |
| RevenueCat, Amerika Birleşik Devletleri | Anonim tanımlayıcı, satın alım ve abonelik kayıtları | Abonelik analizi | Bir satın alım, yenileme ya da iade her işlendiğinde, şifreli ağ üzerinden | 6. bölümdeki gibi |

PIPA kapsamındaki erişim, düzeltme, silme, işlemeyi durdurma ve rızayı geri alma haklarını 14. bölümdeki adresten bize ulaşarak kullanabilirsin; rızayı reddedebilirsin, ancak bu durumda Uygulama portre oluşturamaz. Gizlilikten sorumlu kişi {{DEVELOPER_NAME}}'dır ({{SUPPORT_EMAIL}}). Ayrıca Kişisel Bilgileri Koruma Komisyonu'ndan (Personal Information Protection Commission) ya da KISA Gizlilik Merkezi'nden (118) yardım isteyebilirsin.

### 8.5 Japonya (APPI)

Kişisel bilgileri işleyen işletmeci {{DEVELOPER_NAME}}'dır. Kişisel bilgileri yalnızca 3. bölümdeki amaçlarla kullanırız. Uygulamada rıza verdiğinde, fotoğrafların ve ilgili bilgiler yabancı bir ülkedeki işletmelere sağlanır: OpenAI ve Google, Amerika Birleşik Devletleri'nde ve faaliyet gösterdikleri diğer ülkelerde. Anonim tanımlayıcın ve satın alım kayıtların ayrıca Amerika Birleşik Devletleri'ndeki RevenueCat'e sağlanır. Amerika Birleşik Devletleri'nde APPI gibi tek ve kapsamlı bir kişisel bilgilerin korunması kanunu yoktur; hizmet sağlayıcılarımız verileri 4. bölümde açıklanan kendi taahhütleri ve sözleşme şartları (API verileriyle eğitim yapılmaması, sınırlı saklama, şifreleme) çerçevesinde işler. Elde tutulan kişisel verilerin açıklanmasını, düzeltilmesini, silinmesini ve kullanımının durdurulmasını ve üçüncü taraflara sağlama kaydını, 14. bölümdeki adresten bize ulaşarak talep edebilirsin.

### 8.6 Amerika Birleşik Devletleri

Yaşadığın yere bağlı olarak (örneğin Kaliforniya, Colorado, Connecticut, Virginia, Texas, Oregon ve tüketici gizliliği kanunu olan diğer eyaletler) hangi kişisel bilgilerini tuttuğumuzu öğrenme, bunlara erişme, düzeltme, silme, taşınabilir bir kopya alma ve kararımıza itiraz etme hakkına sahip olabilirsin. Kişisel bilgileri satmayız, hedefli reklamcılık için paylaşmayız ve hukuki veya benzer şekilde önemli sonuçlar doğuran profilleme için kullanmayız. Fotoğrafları bir kişiyi benzersiz biçimde tanımlamak için işlemeyiz. Bu hakları kullanmak için Uygulamada Tüm verilerimi sil'i kullan ya da {{SUPPORT_EMAIL}} adresine e-posta gönder; 45 gün içinde yanıt veririz (kanunun izin verdiği hallerde bir kez uzatabiliriz) ve haklarını kullandığın için sana ayrımcılık yapmayız. Yetkili bir temsilci kullanabilirsin; talebi doğrulamak için Destek Kimliğini isteyebiliriz. Bir talebi reddedersek e-postamıza yanıt yazarak itiraz edebilirsin ve eyaletinin başsavcısına başvurabilirsin.

Kaliforniya "Shine the Light" ve Nevada talepleri aynı adrese gönderilebilir. Seni izlemediğimiz için "Do Not Track" sinyallerine yanıt vermeyiz.

### 8.7 Diğer ülkeler

Ülkenin kanunu kişisel verilerin üzerinde sana ek haklar tanıyorsa, bunlara bizim için geçerli oldukları ölçüde saygı gösteririz. 14. bölümdeki adrese yaz.

## 9. Çocuklar

Uygulama çocuklara yönelik değildir ve 13 yaşın altındaki çocuklardan bilerek kişisel bilgi toplamayız. Uygulamayı kullanma ya da 13 yaşın altındaki çocukların fotoğraflarını yükleme. Ülkenin kanunu kişisel verilerin işlenmesine rıza vermek için daha yüksek bir asgari yaş belirliyorsa (örneğin Güney Kore'de 14, birçok Avrupa ülkesinde 14 ile 16 arası), Uygulamayı kullanmak için en az o yaşta olmalı ya da ebeveynin veya vasinin rızasına sahip olmalısın. Bir çocuğun bilgilerinin bize gönderildiğini düşünüyorsan {{SUPPORT_EMAIL}} adresine yaz, silelim.

## 10. Otomatik işleme ve biyometri

Portreler, bir yapay zeka modeli tarafından fotoğrafından ve bizim seçtiğimiz bir görünümden oluşturulur. Hakkında hukuki veya benzer şekilde önemli sonuçlar doğuran hiçbir karar vermeyiz ve seni profillemeyiz. Tek otomatik kontroller dolandırıcılık ve kötüye kullanım denetimleridir (örneğin cihaz başına sınırlar ve içerik güvenlik filtreleri); bir oluşturma reddedilirse başka bir fotoğrafla yeniden deneyebilir ya da bize ulaşabilirsin.

Biyometrik kimlik belirleme kullanmayız. Yüz algılama yalnızca bir yüz olup olmadığını kontrol etmek ve yüzleri saymak için cihazında çalışır. Yüz şablonu oluşturmaz veya saklamayız, yüzleri karşılaştırmayız ve yüzleri kimseyi tanımlamak için kullanmayız. Önce/sonra karşılaştırması için telefonunda kalan yüz dikdörtgeni (yalnızca konum ve boyut) bir yüz şablonu değildir, başka hiçbir şey için kullanılmaz ve bize hiçbir zaman gönderilmez.

## 11. Başkalarının fotoğrafları

Yalnızca bunu kabul eden kişilerin fotoğraflarını ekle. Başkalarının fotoğrafları da seninkiler gibi yapay zeka hizmetine gönderilir. Onların iznini almaktan sen sorumlusun.

## 12. Güvenlik

Veriler Uygulama, arka uç sunucumuz ve yapay zeka hizmeti arasında şifreli bağlantılar (HTTPS/TLS) üzerinden taşınır. Bulut sağlayıcılarımız saklanan verileri bekleme halindeyken şifreler. OpenAI API anahtarı sunucumuzda tutulur ve hiçbir zaman Uygulamanın içinde bulunmaz. Hiçbir sistem tamamen güvenli değildir; bu yüzden mutlak güvenliği garanti edemeyiz. Bir ihlal kişisel verilerini etkilerse, kanunun gerektirdiği şekilde sana ve yetkili makamlara bildiririz.

## 13. Değişiklikler ve bu web sitesi

Bu politikayı önemli ölçüde değiştirirsek yukarıdaki tarihi güncelleriz ve değişiklik yapay zeka hizmetine gönderilenleri etkiliyorsa Uygulamada yeniden iznini isteriz. Bu politika senin dilinde gösteriliyorsa çeviri kolaylık için sunulmuştur; sürümler arasında fark varsa İngilizce sürüm geçerlidir.

Bu web sitesi statiktir. Çerez yerleştirmez, analiz ya da harici kaynak kullanmaz. GitHub Pages üzerinde barındırılır; tarayıcın bir sayfayı yüklediğinde GitHub IP adresin gibi teknik verileri işleyebilir.

## 14. İletişim

{{DEVELOPER_NAME}}
{{SUPPORT_EMAIL}}
{{SITE_URL}}/privacy.html
