# Nasıl Katkıda Bulunulur?

Katkıda bulunmanın en kolay yollarından biri, GitHub sorunları üzerinde tartışmalara katılmaktır. Ayrıca kod değişiklikleri içeren pull request'ler göndererek katkıda bulunabilirsiniz.

## Genel geri bildirim ve tartışmalar?

[Tartışmayı başlatmak için repo'nun issue takip sayfasını](https://github.com/dotnet/aspnetcore/issues) kullanın.

## Hatalar ve özellik istekleri?

❗ **ÖNEMLİ: Eğer güvenlikle ilgili bir sorun bildirmek istiyorsanız, lütfen aşağıdaki `Güvenlik sorunları ve hataları bildirme` bölümüne bakın.**

Yeni bir sorun bildirmeden önce, mevcut bir sorun olup olmadığını kontrol edin. Eğer varsa, ona oy verin (👍). Ayrıca, o sorunla ilgili benzersiz senaryolarınızı ve gereksinimlerinizi yorum olarak eklemeyi düşünün. Oylar ve sorunun etkisiyle ilgili net detaylar, en önemli sorunları daha hızlı önceliklendirmemize yardımcı olur. Mevcut bir sorun bulamazsanız, sorun değil, bir kopya bildirimde bulunmak hiç bildirmemekten iyidir.

Eğer mevcut bir sorun bulamazsanız, uygun GitHub deposunda yeni bir sorun kaydedin. İşte en yaygın depolar:

* [Dokümantasyon](https://github.com/aspnet/Docs)
* [AspNetCore](https://github.com/dotnet/aspnetcore)
* [Entity Framework Core](https://github.com/dotnet/efcore)
* [Tooling](https://github.com/aspnet/Tooling)
* [Runtime](https://github.com/dotnet/runtime)

Veya [aspnet](https://github.com/aspnet/) organizasyonundaki tüm depo listesine göz atın.

## Güvenlik sorunları ve hataları bildirme

Güvenlik sorunları ve hataları, Microsoft Güvenlik Yanıt Merkezi'ne (MSRC) özel olarak secure@microsoft.com adresine e-posta yoluyla bildirilmelidir. 24 saat içinde yanıt almanız gerekir. Herhangi bir sebepten dolayı yanıt almazsanız, orijinal mesajınızı aldığımızdan emin olmak için lütfen e-posta yoluyla takip edin. MSRC PGP anahtarı dahil olmak üzere daha fazla bilgi için [Güvenlik TechCenter](https://technet.microsoft.com/security/ff852094.aspx) adresine bakabilirsiniz.

## Diğer tartışmalar

Ekibimiz ayrıca birkaç diğer tartışma forumunu da takip etmektedir:

* [ASP.NET Core forumu](https://forums.asp.net/1255.aspx/1?ASP+NET+5)
* [`asp.net-core`](https://stackoverflow.com/questions/tagged/asp.net-core), [`asp.net-core-mvc`](https://stackoverflow.com/questions/tagged/asp.net-core-mvc) veya [`entity-framework-core`](https://stackoverflow.com/questions/tagged/entity-framework-core) etiketleriyle [Stack Overflow](https://stackoverflow.com/).

## PR nasıl gönderilir?

Topluluk üyelerinden gelen hem hata düzeltmeleri hem de yeni özellikler için pull request'leri her zaman memnuniyetle karşılıyoruz.
Başarılı olmanıza yardımcı olmak için kod tabanına katkıda bulunurken takip etmeniz gereken birkaç basit kural derledik:

### Üzerinde çalışılacak bir sorun bulma

Yıllar içinde çerçevenin o sırada genişletilmesi planlanmayan alanlarına yönelik birçok PR gördük. Bu gibi durumlarda, bu PR'ları kabul edemeyip kapatmak zorunda kaldık. Bu, bizim için harika bir sonuç değil. Katkıda bulunan kişi içinse daha da kötü, çünkü değişikliği hazırlamak için çok fazla çaba harcadılar. Bu sorunu çözmek için topluluk üyelerinin katkıda bulunabileceği sorunları belirledik ve bu sorunları `help wanted` etiketi ile işaretledik. Bu sorunların tamamını [burada bulabilirsiniz](https://aka.ms/aspnet/helpwanted). Çalışmak istediğiniz bir sorun seçtiğinizde, bazılarına ekibimizden bir yorumun eşlik ettiğini göreceksiniz. Bu yorum, hem sorunun ne olduğunu anlamayı hem de nasıl yaklaşılacağına dair referanslar ve ipuçları sağlamayı kolaylaştırır.

Bu set içinde, ilk kez katkıda bulunanlar için iyi aday olan sorunları da işaretledik. Bunlar çerçeveye aşinalık gerektirmeyen ve daha yeni başlayanlara uygun sorunlardır. Bu sorunlar `good first issue` etiketi ile işaretlenmiştir. Bu tür sorunların tam listesini [burada bulabilirsiniz](https://aka.ms/aspnet/goodfirstissues).

Burada belgelenmemiş bir alana katkıda bulunmak isterseniz, bir pull request göndermeden önce yapılacak değişikliğin bir tanımını içeren bir sorun açarak tartışılmasını sağlayın.

### Kod yazmadan önce

Müşterilerin bir sorunu çerçeveye uygun olmayan bir şekilde çözdüğü veya çerçeveyi istenmeyen bir şekilde değiştirdiği PR'lar gördük. Bu durumlardan kaçınmak ve potansiyel olarak çok fazla zamanınızı kurtarmak için, müşterilerin tercih edilen tasarımı ekibimizle önceden tartışmalarını öneririz. Bunu yapmak için yeni bir `tasarım önerisi` sorunu açın, ele almak istediğiniz sorunun bağlantısını ekleyin ve belirli bir sorunu nasıl çözmek istediğinize dair ayrıntılı bilgiler sağlayın. Sorunları periyodik olarak değerlendiriyoruz ve ekibimizden biri bu öneriniz hakkında sizinle hızlıca etkileşime geçecektir. Ekibimizin üyelerinden tasarım önerinizin sağlam olduğu konusunda bir anlaşma aldığınızda, PR hazırlamaya başlayabilirsiniz.
Bir tasarım önerisi açmak için, `New issue` sayfasındaki ilgili sorunu arayın veya [bu bağlantıya](https://github.com/dotnet/aspnetcore/issues/new?assignees=&labels=design-proposal&template=4_design_proposal.md) tıklayın:
![image](https://user-images.githubusercontent.com/34246760/107969904-41b9ae80-6f65-11eb-8b84-d15e7d94753b.png)

### Pull request göndermeden önce

Pull request göndermeden önce şu gereksinimleri karşıladığınızdan emin olun:

* "help-wanted" etiketli mevcut bir sorun buldunuz veya ekiple tartışarak bu etiketi içeren yeni bir sorun eklemeye karar verdiniz
* Yüksek düzeyde bir uygulama tasviri paylaştınız ve ekibin bu yaklaşım hakkında olumlu bir geri dönüş aldınız
* Kod tabanındaki mevcut desenleri izleyerek test kapsamı eklediniz
* Kodunuz kod tabanındaki mevcut sözdizimi kurallarıyla eşleşiyor
* PR'ınız küçük, odaklanmış ve ilgisiz değişikliklerden kaçınıyor

PR'ınız aşağıdaki unsurları içeriyorsa, birleştirilme olasılığı daha düşüktür:

* Geriye dönük uyumluluğu bozan değişiklikler
* Sadece bir kişi/şirket tarafından istenen değişiklikler. Değişikliklerin, ASP.NET geliştiricilerinin yeterince büyük bir bölümüne fayda sağlaması gerekir.
* Önceden anlaşmaya varılmamış tamamen yeni özellik alanları ekleyen değişiklikler
* Mevcut kodu veya kod stilini yeniden düzenlemeye yönelik değişiklikler
* Saatler sürecek incelemelere neden olacak çok büyük PR'lar. Daha büyük çalışma alanları için, bunu daha küçük, kademeli parçalara ayırma yollarını tartışmak için bizimle iletişime geçin.

### Pull request inceleme sırasında

Bir çekirdek katkıcı, PR'ınızı inceleyecek ve geri bildirim sağlayacaktır. Aktif olmayan PR'ların büyük bir birikimi olmaması için, pull request iki hafta boyunca hiçbir etkinlik olmadığında `stale` olarak işaretlenecektir. Dört gün daha geçtikten sonra kapatılacaktır.

### Başlamanıza yardımcı olacak kaynaklar

İşte kod veya yeni içerik katkısında bulunmaya nasıl başlayacağınızı öğrenmenize yardımcı olacak bazı kaynaklar.

* Kaynak kodu kendi başınıza oluşturmak için başlamak adına [Katkıcı dokümantasyonuna](/docs/README.md) göz atın.
* ["Help wanted" sorunları](https://github.com/dotnet/aspnetcore/labels/help%20wanted) - bu sorunlar katkıda bulunmaya açıktır. Bir çözüm oluşturmak isterseniz bir sorun üzerinde yorum yapın.
* ["Good first issue" sorunları](https://github.com/dotnet/aspnetcore/labels/good%20first%20issue) - bunların yeni başlayanlar için iyi olduğunu düşünüyoruz.

### Ölçeği Belirleme

Depolarımızdan birine katkıda bulunmak istiyorsanız, önce katkıda bulunmak istediğiniz şeyin ölçeğini belirleyin. Eğer küçükse (dil bilgisi/ yazım veya bir hata düzeltmesi), bir düzeltme üzerinde çalışmaya başlayabilirsiniz. Eğer bir özellik veya önemli bir kod katkısı gönderiyorsanız, lütfen bunu ekibimizle tartışın ve ürün yol

 haritasına uygun olduğundan emin olun. Ayrıca bu iki blog yazısını da okuyabilirsiniz: Miguel de Icaza'dan [Açık Kaynak Katkı Etiketi](http://tirania.org/blog/archive/2010/Dec-31.html) ve Ilya Grigorik'ten [Pull Request'lerinizi "Zorlamayın"](https://www.igvita.com/2011/12/19/dont-push-your-pull-requests/). Tüm kod gönderimleri ASP.NET ekibi tarafından titizlikle incelenecek ve test edilecektir. Yalnızca kalite ve tasarım/yol haritası uygunluğu açısından yüksek standartlara uyan kodlar kaynakla birleştirilecektir.

### Pull request gönderme

Pull request gönderdiğinizde bir [Katkıcı Lisans Sözleşmesi](https://cla.dotnetfoundation.org/) imzalamanız gerekecektir. Katkıcı Lisans Sözleşmesi'ni (CLA) tamamlamak için, pull request'i gönderdiğinizde CLA botu tarafından sağlanan talimatları izleyin. Bu, herhangi bir .NET Foundation OSS projesi için yalnızca bir kez yapılmalıdır.

Pull request'in ne olduğunu bilmiyorsanız şu makaleyi okuyun: <https://help.github.com/articles/using-pull-requests>. Depoyu derleyebildiğinizden ve tüm testlerin geçtiğinden emin olun. Proje iş akışı ve kodlama kurallarımızla tanışın. Kodlama, stil ve genel mühendislik kuralları [Mühendislik kuralları](https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines) sayfasında yayımlanmıştır.

### Testler

* Tamamlanan her hata/özellik için testler sağlanmalıdır.
* Yalnızca QA tarafından doğrulanması gereken sorunlar için testler olmalıdır (örneğin, görevler için değil)
* Test edilmesi çok zor bir senaryo varsa, test gerekli değildir.
  * "Çok zor" ekibin bir bütün olarak belirlediği bir karardır.

### Geri Bildirim

Pull request'iniz şimdi ekibimizdeki uzmanlar tarafından geniş kapsamlı kontrollerden geçirilecektir. Lütfen sabırlı olun; tüm depolarımızda yüzlerce pull request var. Geri bildirime göre pull request'inizi güncelleyin ve ASP.NET ekibinin bir üyesi tarafından onaylanana kadar sabırlı olun. Sonrasında, ekibimizden biri, beklenen sürüm takvimine göre birleştirme yapılacak dalı ayarlayabilir.

## Pull request'lerin birleştirilmesi

Pull request'iniz tüm geri bildirimlere yanıt verdiğinde, bir veya daha fazla yetkili incelemeci tarafından onaylandığında ve tüm kontroller başarıyla geçtiğinde, onu birleştireceğiz.

Pull request'leri tek bir Squash commit olarak birleştiriyoruz, özel durumlar dışında. Bu, Merge veya Rebase commit'lerinden daha basit bir geçmiş oluşturur. "Özel durumlar" nadirdir ve genellikle temiz bir şekilde ayrılmış bir dizi değişiklik anlamına gelir veya bunları birlikte sıkıştırmak zor olacağı için ayrı tutulmaları gerektiğini belirtir.

## Ek Kaynaklar

ASP.NET Core ekibinin bu projeye nasıl katkıda bulunulacağına dair rehberlik, tavsiye ve örnekler verdiği videolar (kısmen güncel değil):

* ASP.NET Core için - https://www.youtube.com/watch?v=hVdwb41FPvU
* Blazor için - https://www.youtube.com/watch?v=gRg0xxK8L6w

## Davranış kuralları

[DAVRANIŞ KURALLARI](./CODE-OF-CONDUCT.md) dosyasına bakın.
