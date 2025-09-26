# WebServiceBase

Kurumsal yaklaşımla hazırlanmış örnek microservice çözümü. ASP.NET Core Web API ile servisler, Blazor WebAssembly ile SPA ön yüzü; mesajlaşma için RabbitMQ, cache için Redis, veritabanı için SQL Server kullanılmıştır. Bir mikroservis örneği konsol uygulaması olarak ayrıca gösterilmektedir — eğitim ve portfolyo sunumu amaçlı.

## 🚀 Özet
Bu repo, modern .NET microservice mimarisi ve ilgili altyapı bileşenlerini (RabbitMQ, Redis, SQL Server) gösteren örnek bir uygulamadır. Amaç: gerçek dünya yaklaşımlarını (Loose Coupling, Event-driven, CQRS/Async Messaging) göstermek ve deploy/CI senaryoları için temel sağlamaktır.

## Özellikler
- ASP.NET Core Web API (microservice prensipleriyle)
- Blazor WebAssembly ön yüz (Standalone)
- Bir servis konsol uygulaması örneği (worker / producer)
- RabbitMQ ile asenkron mesajlaşma (event/message broker)
- Redis ile cache / distributed session örneği
- SQL Server (Entity Framework Core / Code-First örneği)
- Docker / Docker Compose ile lokal geliştirme ve entegrasyon
- Basit README + mimari dokümantasyon

## Mimari (kısa)
- Frontend: Blazor WebAssembly (statik deploy edilebilir)
- Gateway / API: ASP.NET Core Web API (servisler REST/HTTP)
- Messaging: RabbitMQ (event-driven communication)
- Cache: Redis
- DB: SQL Server (EF Core)
- Bir demo service: Console App (publisher/worker)

## Klasör Yapısı (örnek)
