---
name: Analiz Aracı Önerisi
about: Yeni bir analiz aracı/kod düzeltici veya mevcut birine güncelleme öner
title: ''
labels: api-suggestion, analyzer
assignees: ''
---

## Arka Plan ve Motivasyon

<!--
ASP.NET deposunda yeni analiz araçlarını ve kod düzelticilerini memnuniyetle karşılıyoruz!

Yeni analiz aracı/kod düzeltici gönderimlerini ve API önerilerini gözden geçirmek için aynı süreci kullanıyoruz. Sürecimize genel bakış [burada](https://github.com/dotnet/aspnetcore/blob/main/docs/APIReviewProcess.md) mevcuttur. Bu şablon, inceleme sürecini başlatmak için gereken bilgileri toplamamıza yardımcı olacaktır.

Bu başlık altında, analiz aracınızın çözmeye çalıştığı sorunu açıklayın. Performans sorunlarını önlemeye, potansiyel olarak güvensiz kodu önlemeye veya belirli bir senaryo için daha iyi API'ler önermeye yardımcı olan senaryoları açıklamak harika motivasyon örnekleri olacaktır.
-->

## Önerilen Analiz Aracı

### Analiz Aracı Davranışı ve Mesajı

<!--
Analiz aracının ne zaman tetikleneceğini ve ilgili analiz aracı mesajını açıklayın.
-->

<!--
Analiz aracı kategorileri, https://learn.microsoft.com/dotnet/fundamentals/code-analysis/categories adresinde belgelenen kategorilerden türetilmiştir.
Her kategorinin açıklamasını gözden geçirerek analiz aracınızın işlevselliğine göre en iyi kategoriyi seçin.

Analiz aracı şiddet düzeyleri, https://learn.microsoft.com/visualstudio/code-quality/use-roslyn-analyzers#configure-severity-levels adresinde belgelenmiştir.
Bu düzeylerin yapı zamanında ve düzenleyicide nasıl bir davranış sergileyeceğini gözlemleyin ve göreviniz için en uygun seviyeyi seçin.
-->

### Kategori

- [ ] Tasarım
- [ ] Dokümantasyon
- [ ] Küreselleşme
- [ ] Uyumluluk
- [ ] Sürdürülebilirlik
- [ ] İsimlendirme
- [ ] Performans
- [ ] Güvenilirlik
- [ ] Güvenlik
- [ ] Stil
- [ ] Kullanım

### Şiddet Düzeyi

- [ ] Hata
- [ ] Uyarı
- [ ] Bilgi
- [ ] Gizli

## Kullanım Senaryoları

<!--
Analiz aracınızı tetiklemek için örnek kodlar sağlayın. Analiz aracının hangi kod parçalarında tetikleneceğini belirleyin.
Uygun olduğunda, değişiklikle ilgili kod düzeltmesinin sonucunu açıklayın.
-->

## Riskler

<!--
API önerisinin bilginiz dahilinde barındırabileceği risklerden bahsedin, örneğin, kırılma değişiklikleri, performans gerilemeleri, vb.
-->
