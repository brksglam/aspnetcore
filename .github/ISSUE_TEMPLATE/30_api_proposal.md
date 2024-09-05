---
name: API önerisi
about: Genel API yüzeyinde bir değişiklik öner
title: ''
labels: api-suggestion
assignees: ''

---

## Arka Plan ve Motivasyon

<!--
API önerilerini memnuniyetle karşılıyoruz! Yeni bir API'nin değerini ve yapısını değerlendirmek için bir sürecimiz var. Sürecimize genel bakış [burada](https://github.com/dotnet/aspnetcore/blob/main/docs/APIReviewProcess.md) mevcuttur. Bu şablon, inceleme sürecini başlatmak için gereken bilgileri toplamamıza yardımcı olacaktır.
Lütfen öncelikle yeni API'nin amacını ve değerini burada açıklayın.
-->

## Önerilen API

<!--
Lütfen önerdiğiniz spesifik genel API imzası farkını sağlayın. Örneğin:
```diff
namespace Microsoft.AspNetCore.Http;

public static class HttpResponseWritingExtensions
{
+    public Task WriteAsync(this HttpResponse response, StringBuilder builder);
}
```
[Framework Tasarım Kılavuzları](https://github.com/dotnet/runtime/blob/master/docs/coding-guidelines/framework-design-guidelines-digest.md) size yardımcı olabilir.
-->

## Kullanım Örnekleri

<!--
Lütfen önerilen API eklemelerinin nasıl tüketilmesi gerektiğini gösteren kod örnekleri sağlayın.
Bu, API'nin işlevsel, performanslı ve kullanışlı olup olmadığını önermeye yardımcı olacaktır.
Kod bloklarını şu şekilde kullanabilirsiniz:
```csharp
// buraya birkaç satır kod
```
-->

## Alternatif Tasarımlar

<!--
Alternatif API yapıları gibi başka seçenekler düşündünüz mü?
Bu, diğer ekosistemlerdeki ve kütüphanelerdeki benzer API'lerle nasıl karşılaştırılır?
-->

## Riskler

<!--
API önerisinin bilginiz dahilinde barındırabileceği risklerden bahsedin, örneğin, kırılma değişiklikleri, performans gerilemeleri, vb.
-->
