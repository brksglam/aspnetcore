ASP.NET Core
============

[![.NET Foundation](https://img.shields.io/badge/.NET%20Foundation-blueviolet.svg)](https://www.dotnetfoundation.org/)
[![MIT License](https://img.shields.io/github/license/dotnet/aspnetcore?color=%230b0&style=flat-square)](https://github.com/dotnet/aspnetcore/blob/main/LICENSE.txt) [![Help Wanted](https://img.shields.io/github/issues/dotnet/aspnetcore/help%20wanted?color=%232EA043&label=help%20wanted&style=flat-square)](https://github.com/dotnet/aspnetcore/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) [![Good First Issues](https://img.shields.io/github/issues/dotnet/aspnetcore/good%20first%20issue?color=%23512BD4&label=good%20first%20issue&style=flat-square)](https://github.com/dotnet/aspnetcore/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
[![Discord](https://img.shields.io/discord/732297728826277939?style=flat-square&label=Discord&logo=discord&logoColor=white&color=7289DA)](https://aka.ms/dotnet-discord)

ASP.NET Core, modern bulut tabanlı ve internet bağlantılı uygulamalar (web uygulamaları, IoT uygulamaları, mobil arka uçlar gibi) geliştirmek için kullanılan açık kaynaklı ve çapraz platform bir çerçevedir. ASP.NET Core uygulamaları, ücretsiz, çapraz platform ve açık kaynaklı bir uygulama çalışma zamanı olan [.NET](https://dot.net) üzerinde çalışır. Bu framework, buluta dağıtılan veya yerinde çalışan uygulamalar için optimize edilmiş bir geliştirme çerçevesi sunmak üzere tasarlanmıştır. Modüler bileşenlerden oluşur ve minimum yük ile maksimum esneklik sağlar, böylece çözümlerinizin inşasında özgür kalırsınız. ASP.NET Core uygulamalarınızı Windows, Mac ve Linux platformlarında çapraz platform olarak geliştirebilir ve çalıştırabilirsiniz. [ASP.NET Core hakkında daha fazla bilgi edinin](https://learn.microsoft.com/aspnet/core/).

## Başlangıç

[Başlangıç Rehberi](https://learn.microsoft.com/aspnet/core/getting-started) talimatlarını takip edin.

.NET'in yayımlanmış sürümleri, başlangıç rehberleri ve öğrenme kaynakları için [.NET Ana Sayfası](https://www.microsoft.com/net)'na göz atın.

Yeni gelen sorunları nasıl ele aldığımız hakkında daha fazla bilgi için [Triage Süreci](https://github.com/dotnet/aspnetcore/blob/main/docs/TriageProcess.md) belgesine bakın.

## Katılım, katkı ve geri bildirim

Katkıda bulunmanın en iyi yollarından bazıları; denemeler yapmak, sorun bildirmek, tasarım konuşmalarına katılmak ve pull-request yapmaktır.

* [En son günlük yapıları indirin](./docs/DailyBuilds.md)
* ASP.NET Core geliştirme sürecini takip edin:
    * [Topluluk Standup](https://live.asp.net): Topluluk standup'ı her hafta yapılır ve YouTube üzerinden canlı yayınlanır. Geçmiş standup'ları ilgili oynatma listesinde izleyebilirsiniz.
    * [Yol Haritası](https://aka.ms/aspnet/roadmap): ASP.NET Core için takvim ve dönüm noktası temaları.
* [ASP.NET Core kaynak kodunu derleyin](./docs/BuildFromSource.md)
* Sorunları kaydetme ve tartışmalara başlama konusundaki en iyi yerleri görmek için [katkıda bulunma](CONTRIBUTING.md) sayfasına göz atın.

## Güvenlik sorunları ve hataları bildirme

Güvenlik sorunları ve hataları, Microsoft Güvenlik Yanıt Merkezi'ne (MSRC) gizli bir şekilde e-posta yoluyla bildirilmelidir: secure@microsoft.com. 24 saat içinde yanıt almalısınız. Herhangi bir sebepten ötürü yanıt almazsanız, orijinal mesajınızı aldığımızdan emin olmak için lütfen e-posta yoluyla takip edin. Daha fazla bilgi, MSRC PGP anahtarı dahil, [Güvenlik Teknoloji Merkezi](https://technet.microsoft.com/en-us/security/ff852094.aspx) adresinde bulunabilir.

## İlgili projeler

İlgili bazı projeler şunlardır:

* [Dokümantasyon](https://github.com/aspnet/Docs) - https://learn.microsoft.com/aspnet/core/ için dokümantasyon kaynakları
* [Entity Framework Core](https://github.com/dotnet/efcore) - veri erişim teknolojisi
* [Çalışma Zamanı](https://github.com/dotnet/runtime) - bulut, mobil, masaüstü ve IoT uygulamaları için çapraz platform çalışma zamanı
* [Razor](https://github.com/dotnet/razor) - Razor söz dizimi (.cshtml, .razor) ile çalışma için Razor derleyici ve araçları

## Davranış Kuralları

[DAVRANIŞ KURALLARI](./CODE-OF-CONDUCT.md) sayfasını inceleyin.

## Gece Yapıları

Bu tabloda, ASP.NET Core Paylaşılan Framework'ünün en son yapılarının indirme bağlantıları yer almaktadır. Ayrıca, Windows Hosting Paketi'ni indirme bağlantıları da yer almakta olup, bu paket ASP.NET Core Paylaşılan Framework'ü, .NET Runtime Paylaşılan Framework'ü ve IIS eklentisini (ASP.NET Core Modülü) içermektedir. En son .NET Runtime yapıları için [buraya](https://github.com/dotnet/runtime/blob/main/docs/project/dogfooding.md#nightly-builds-table), en son .NET SDK yapıları için [buraya](https://github.com/dotnet/installer#table) bakabilirsiniz. **Emin değilseniz SDK'yı yükleyin; IIS eklentisi hariç her şey bu pakette mevcuttur.**

| Platform        | Paylaşılan Framework (Yükleyici) | Paylaşılan Framework (İkili Dosyalar) | Hosting Paketi (Yükleyici) |
| :-------------- | :----------------------------:  | :-----------------------------------: | :-------------------------: |
| **Windows x64** | [Yükleyici](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-win-x64.exe) | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-win-x64.zip) | [Yükleyici](https://aka.ms/dotnet/9.0/daily/dotnet-hosting-win.exe) |
| **Windows x86** | [Yükleyici](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-win-x86.exe) | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-win-x86.zip) | [Yükleyici](https://aka.ms/dotnet/9.0/daily/dotnet-hosting-win.exe) |
| **Windows arm64** | [Yükleyici](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-win-arm64.exe) | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-win-arm64.zip) | [Yükleyici](https://aka.ms/dotnet/9.0/daily/dotnet-hosting-win.exe) |
| **macOS x64** | **N/A** | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-osx-x64.tar.gz) | **N/A** |
| **macOS arm64** | **N/A** | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-osx-arm64.tar.gz) | **N/A** |
| **Linux x64** | [Deb Yükleyici](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-x64.deb) - [RPM Yükleyici](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-x64.rpm) | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-linux-x64.tar.gz) | **N/A** |
| **Linux arm** | **N/A** | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-linux-arm.tar.gz) | **N/A** |
| **Linux arm64** | [RPM Yükleyici](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-aarch64.rpm) | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-linux

-arm64.tar.gz) | **N/A** |
| **Linux-musl-x64** | **N/A** | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-linux-musl-x64.tar.gz) | **N/A** |
| **Linux-musl-arm** | **N/A** | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-linux-musl-arm.tar.gz) | **N/A** |
| **Linux-musl-arm64** | **N/A** | [İkili Dosyalar](https://aka.ms/dotnet/9.0/daily/aspnetcore-runtime-linux-musl-arm64.tar.gz) | **N/A** |
