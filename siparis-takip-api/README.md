# Sipariş Takip API (mini proje)

21 günlük [öğrenme programının](../README.md) uygulama alanı. Amaç büyük bir ürün değil, her günün konusunu somut bir yerde kullanmak.

## Özellikler (günlere göre eklenir)
| Gün | Özellik |
|---|---|
| 1-2 | Kayıt, giriş, JWT + refresh token |
| 3 | Admin / Customer rolleri, login'de rate limit |
| 4-5 | Sipariş oluşturma (Command) ve listeleme (Query), MediatR |
| 6 | Redis ile sipariş listesi cache'i |
| 8 | SignalR ile canlı sipariş durumu |
| 9-10 | Transactional Outbox ile güvenilir bildirim |
| 11 | Audit log |
| 12 | Unit + integration testler |
| 13 | Docker Compose + GitHub Actions |
| 16-18 | pgvector ile sipariş notlarında anlamsal arama, belge yükleme, basit RAG |

## Başlangıç (Gün 1)
```bash
dotnet new webapi -n OrderTracking.Api
cd OrderTracking.Api
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
```

## Mimari şema
_Gün 20'de eklenecek._

## Kurulum
_Gün 6'da yazılacak._
