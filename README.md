# Matematiksel Araştırmalar

Bu bir ders defteri değil, bir **araştırma defteri**.

## Nasıl çalışıyoruz

Burada formül ezberlemiyoruz. Şunu yapıyoruz:

1. **Bir soru buluyoruz** — kuralı bir cümlede anlatılabilen, ama cevabı belli olmayan.
2. **Deniyoruz** — bilgisayara binlerce, milyonlarca örnek hesaplatıyoruz.
3. **Bakıyoruz** — sayılarda bir örüntü, bir tuhaflık var mı?
4. **Yazıyoruz** — ne gördüğümüzü, neyi hâlâ anlamadığımızı kaydediyoruz.

Gerçek matematikçiler de aşağı yukarı böyle çalışıyor. Fark şu ki
onlar dördüncü adımdan sonra bir de *ispat* yazmaya çalışıyor.
Biz oraya gelene kadar önce görmeyi öğreneceğiz.

## Kural

**Anlamadığın hiçbir şeyi geçme.** "Bu ne demek?" sorusu bu defterde
en değerli sorudur — çünkü bir şeyi gerçekten anlamadan onunla
araştırma yapılamaz. Aptalca soru yok.

## Araştırmalar

| # | Konu | Durum |
|---|------|-------|
| [01](01-collatz/) | Collatz sanısı — sayıların 1'e düşüşü | Giriş / açık soru |
| [02](02-cp20-task6-bagimsiz-dogrulama/) | CP20 Task 6 teorem adayı — bağımsız sayısal doğrulama | Sayısal bileşenler doğrulandı, denetim açık |

## İki katman

Bu defterde iki farklı seviye var ve karışmamaları önemli:

- **01** — sıfırdan giriş. Collatz nedir, neden zor, elle takip edilebilir örnekler.
- **02** — Google Drive'daki CP01–CP20 araştırma arşivinin aktif cephesine
  yapılan bağımsız kontrol. Bu seviye teknik ve arşivin kendi
  denetim disiplinine tabi.

Arşivin STOP kuralı yürürlükte: CP20 Task 6 teoremi bağımsız denetimden
geçmeden downstream kullanılmamalı.

## Deneyleri çalıştırmak

```bash
python3 01-collatz/deney.py
```

Ek bir program kurmanız gerekmiyor, sadece Python yeterli.
