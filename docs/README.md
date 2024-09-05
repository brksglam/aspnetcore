Contributor Documentation
=========================

Bu klasördeki dokümantasyonun birincil hedef kitlesi, ASP.NET Core'a katkıda bulunan kişilerdir.  
ASP.NET Core'u *kullanma* ile ilgili belgeler arıyorsanız, <https://docs.asp.net> adresine gidin.

> :bulb: Eğer depoyu yerel olarak kurmak isteyen yeni bir katkıcıysanız, [kaynak koddan derleme belgesi](BuildFromSource.md) başlamanız gereken en iyi yerdir.

Aşağıdaki tablo, bu klasördeki çeşitli belgeleri ve ne amaçla faydalı olduklarını göstermektedir.

| Dokümantasyon        | Konusu   | Kime Yönelik?      |
|--------------------------------------------------------------------------|-------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| [API inceleme süreci](APIReviewProcess.md)      | ASP.NET Core'da API değişikliklerini gözden geçirme sürecini açıklar          | ASP.NET Core'da API değişiklikleri yapma sürecini anlamak isteyen herkes      |
| [Yapı artefaktları yapısı](Artifacts.md)            | Yapı sırasında üretilen artefaktları açıklar  | Azure DevOps yapısından üretilen artefaktları anlamak isteyen herkes          |
| [Yapı hatalarını giderme](BuildErrors.md) | Depoyu derlerken karşılaşılan yaygın hatalar ve bunları nasıl çözeceğiniz | Derleme sırasında sorun yaşayan herkes        |
| [Kaynak koddan derleme](BuildFromSource.md)     | ASP.NET Core deposunu kurulum talimatları  | İlk kez katkıda bulunanlar          |
| [EventSources ve EventCounters ile çalışma](EventSourceAndCounters.md) | Bir kütüphaneye olay izleme ekleme kılavuzu | Teşhis amaçları için olay izleme eklemesi gereken herkes      |
| [Teşhis Listesi](list-of-diagnostics.md) | Depoda kullanılan teşhis kodlarının listesi | Teşhis amaçları için yeni kodlar eklemesi gereken herkes |
| [Helix'te Testler](Helix.md)        | Helix test ortamına genel bakış     | Helix'teki testleri hata ayıklayan veya Helix yapılarının çıktısını anlamak isteyen herkes       |
| [Sorun yönetimi](IssueManagementPolicies.md) | Sorunları yönetmek için kullanılan politikaların genel bakışı| Kapalı sorunların nasıl ele alındığını, yazar geri bildirimi gerektiren sorunları anlamak isteyen topluluk üyeleri ve işbirlikçiler |
| [Yama güncellemesi hazırlama](PreparingPatchUpdates.md)        | ASP.NET Core için yama sürümü hazırlama dokümantasyonu       | Servis güncellemeleri yayınlamak isteyen herkes         |
| [Proje özellikleri](ProjectProperties.md)     | Depoda yapılandırılabilir MSBuild özelliklerinin genel bakışı    | Bir projenin nasıl paketlendiğini değiştirmek isteyen herkes   |
| [Bağımlılıkların nasıl çözümlendiği](ReferenceResolution.md)       | Depodaki bağımlılık referans yapılandırmasının genel bakışı         | Depodaki paket referanslarının nasıl yapılandırıldığını anlamak isteyen herkes |
| [Servis değişiklikleri](Servicing.md) | Önceki sürümlere servis PR'larının nasıl gönderileceğine dair dokümantasyon       | Önceki sürümlere yamalar veya geri taşımalar göndermek isteyen herkes, "Shiproom Şablonunu" içerir  |
| [Paylaşılan çerçeve](SharedFramework.md)         | ASP.NET Core Paylaşılan Çerçevesi'nin genel bakışı | Paylaşılan çerçeve kodunu yönetme politikalarını anlamak isteyen herkes         |
| [Alt modüller](Submodules.md)           | Git'teki alt modüllerle çalışma dokümantasyonu     |   Depodaki alt modüllerle çalışan herkes     |
| [Üçleme süreci](TriageProcess.md)| Depodaki sorun üçleme sürecinin genel bakışı     | Depodaki üçleme sürecini anlamak isteyen herkes  |
| [Ana Sürüm ve TFM Güncelleme](UpdatingMajorVersionAndTFM.md)| Yeni bir ana sürüm için depo markalamasını ve TFM'yi güncelleme talimatları     | Markalama ve sürüm süreci hakkında daha fazla bilgi edinmek isteyen depo geliştiricileri  |
| [Derleme Kırpma Kılavuzu](Trimming.md)| Bir ASP.NET Core derlemesine kırpma desteği ekleme kılavuzu     | ASP.NET Core'a kırpma desteği eklemek isteyen depo geliştiricileri  |
| [Depoya Yeni Projeler Ekleme](AddingNewProjects.md) | Depoya yeni projelerin (örneğin `.csproj` dosyaları) nasıl ekleneceğini açıklar | Yeni bir proje eklemek ve bunu derlemeye dahil etmek isteyen herkes  |
| [Kestrel'de WebTransport Kullanımı](WebTransport.md) | Kestrel'in WebTransport'u nasıl kullanacak şekilde yapılandırılacağını açıklar | WebTransport'u desteklemek isteyen herkes |
| [Performans Testi](Benchmarks.md) | PR'lar ve yerel değişikliklerin nasıl performans testine tabi tutulacağına dair talimatlar | .NET ekibi |
