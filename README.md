# Backend Öğrenme Yolculuğu (21 Gün)

Atlas ve MeetBrainz'de kullandığım teknolojileri **gerçekten anlamak** için hazırladığım günlük program. Her gün bir konu: benzetmeyle anla → kendi kodunda bul → mini projeye ekle → kendi cümlelerinle anlat.

## Günlük rutin (60-75 dk)

1. **Benzetme (10 dk):** AI'a: "X'i gerçek hayattan bir benzetmeyle anlat, sonra 'bu olmasaydı ne bozulurdu?' sorusunu cevapla."
2. **Kendi kodunda bul (20 dk):** Atlas'ta ilgili dosyaları oku, 3-4 cümlelik notunu `notes/` klasörüne yaz.
3. **Mini projeye ekle (25 dk):** Önce 30 dk AI'sız dene. Takılırsan AI'dan *kodu yazmasını* değil, *ipucu vermesini* iste.
4. **1 dakikalık mülakat cevabı (5 dk):** Sesli anlat veya yaz.

## İlerleme

Her günü bitirince kutuyu işaretle (`[ ]` → `[x]`) ve commit at.

### Hafta 1: Güvenlik ve yapı

- [ ] **Gün 1:** [JWT access token](notes/day-01-jwt-access-token.md)
- [ ] **Gün 2:** [Refresh token](notes/day-02-refresh-token.md)
- [ ] **Gün 3:** [Rol bazlı yetkilendirme + rate limiting](notes/day-03-rol-yetki-rate-limit.md)
- [ ] **Gün 4:** [CQRS](notes/day-04-cqrs.md)
- [ ] **Gün 5:** [MediatR](notes/day-05-mediatr.md)
- [ ] **Gün 6:** [Redis cache](notes/day-06-redis-cache.md)
- [ ] **Gün 7:** [TEKRAR 1](notes/day-07-tekrar-1.md)

### Hafta 2: Gerçek zamanlı ve güvenilirlik

- [ ] **Gün 8:** [SignalR](notes/day-08-signalr.md)
- [ ] **Gün 9:** [Transactional Outbox: sorun nedir?](notes/day-09-outbox-sorun.md)
- [ ] **Gün 10:** [Transactional Outbox: uygula](notes/day-10-outbox-uygula.md)
- [ ] **Gün 11:** [Audit logging](notes/day-11-audit-logging.md)
- [ ] **Gün 12:** [Unit test ve integration test](notes/day-12-test-turleri.md)
- [ ] **Gün 13:** [Docker Compose ve GitHub Actions](notes/day-13-docker-ci.md)
- [ ] **Gün 14:** [TEKRAR 2 + mock mülakat](notes/day-14-tekrar-2-mulakat.md)

### Hafta 3: AI ve arama

- [ ] **Gün 15:** [Embedding nedir?](notes/day-15-embedding.md)
- [ ] **Gün 16:** [pgvector ve vector search](notes/day-16-pgvector.md)
- [ ] **Gün 17:** [Belge yükleme → metin çıkarma → arama](notes/day-17-belge-pipeline.md)
- [ ] **Gün 18:** [Basit RAG](notes/day-18-rag.md)
- [ ] **Gün 19:** [Mini projeyi toparla](notes/day-19-toparla.md)
- [ ] **Gün 20:** [README ve mimari şema](notes/day-20-readme-sema.md)
- [ ] **Gün 21:** [Final: mülakat provası](notes/day-21-final-mulakat.md)

## Mini proje

[`siparis-takip-api/`](siparis-takip-api/README.md): öğrendiklerimi her gün üzerine ekleyerek büyüttüğüm küçük Sipariş Takip API'si.

## Kurallar

- Takıldığın günü atlama, bir gün uzat.
- Her gün en az 1 commit.
- Anlatamadığın konu bitmiş sayılmaz.
