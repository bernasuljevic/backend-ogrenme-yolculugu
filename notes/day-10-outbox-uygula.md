# Gün 10: Transactional Outbox: uygula

**Tarih:**
**Süre:**

## 1. Benzetme
AI'a sorulacak: "Transactional Outbox: uygula konusunu gerçek hayattan bir benzetmeyle anlat, sonra 'bu olmasaydı ne bozulurdu?' sorusunu cevapla."

Başlangıç fikri: Siparişi ve 'mutfağa haber ver' notunu aynı deftere yazarsın; ayrı bir görevli o notları sırayla mutfağa taşır.

Benim benzetmem:

>

## 2. Atlas'ta bul
Atlas'taki outbox işleyicisinin (processor) döngüsünü satır satır oku.

Dosya yolları:
-

Kendi cümlelerimle (3-4 cümle):

>

## 3. Mini projeye ekle
Mini projede sipariş kaydıyla aynı transaction'da OutboxMessages tablosuna kayıt at. Arka plan servisi bu kayıtları okuyup 'bildirim gönder'.

- [ ] AI'sız denedim (30 dk)
- [ ] Çalışıyor
- [ ] Commit attım

Takıldığım yer:

>

## 4. Mülakat cevabım (1 dk)
**Soru:** Outbox 'en az bir kez' (at-least-once) teslim eder. Bu neden tekrar işlemeye (idempotency) ihtiyaç doğurur?

**Cevabım:**

>

## Bugün öğrendiğim tek cümle
>
