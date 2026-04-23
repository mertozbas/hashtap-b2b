# HashTap B2B — Partner Programı Sunumu

Bu repo HashTap'in **B2B reseller kanalı** için hazırlanan landing sayfasını ve partner sunum deck'ini içerir.

## 🌐 Yayında

Repo GitHub Pages'te yayındadır:

- **Landing sayfası** → [mertozbas.github.io/hashtap-b2b/landing.html](https://mertozbas.github.io/hashtap-b2b/landing.html)
- **Partner sunumu (deck)** → [mertozbas.github.io/hashtap-b2b/](https://mertozbas.github.io/hashtap-b2b/)

## 📦 İçerik

```
.
├── index.html       # 14 slaytlık B2B partner sunumu (deck-stage)
├── landing.html     # Partner başvuru landing sayfası + form
├── deck-stage.js    # Slide deck shell (scaling, keyboard nav)
├── assets/          # HashTap logoları
├── PARTNER_PROGRAM.md
├── PRICING.md
└── adr/             # Mimari karar kayıtları
```

## 🚀 GitHub Pages'i etkinleştirmek

1. Bu repo'nun **Settings → Pages** bölümüne git
2. **Source**: `Deploy from a branch`
3. **Branch**: `main` · **Folder**: `/ (root)` seç ve Save
4. 1–2 dakika sonra `https://mertozbas.github.io/hashtap-b2b/` yayında olur

`.nojekyll` dosyası zaten repo'da — underscore ile başlayan path'lerin 404 vermesi engellenir.

## 🎤 Sunumu kullanmak

- `index.html` — 1920×1080 tasarlanmış, tarayıcıda otomatik ölçeklenir
- **Klavye**: `←` `→` ile gezinti, `F` tam ekran
- **Speaker notes**: yok (istenirse eklenir)
- **PDF'e çıktı al**: Tarayıcıdan `Cmd/Ctrl + P` → Landscape, Background graphics on

## 📊 Slayt listesi

| # | Slayt | İçerik |
|---|---|---|
| 01 | Kapak | HashTap B2B Partner Programı v1.1 |
| 02 | Problem | Doğrudan satışın ölçek sorunu |
| 03 | Roller | HashTap vs Partner sorumluluk matrisi |
| 04 | Paketler | A/B kısıtlı lisans, C/D full ERP |
| 05 | Fiyat modeli | MSRP sabit, 3 katmanlı |
| 06 | Tier sistemi | Tekil / Bronze / Silver / Gold |
| 07 | Partner alış matrisi | 4 paket × 4 tier |
| 08 | Gerçek senaryolar | Bronze Ege / Silver Konya / Gold İzmir |
| 09 | Onboarding | 90 günlük yolculuk |
| 10 | Destek & SLA | L1/L2 zinciri + P0–P3 tablosu |
| 11 | Bakım & Lifetime | Upgrade yolları |
| 12 | Partner profili | Aranan vs eşleşmeyen |
| 13 | Hedefler | 12/24 ay KPI |
| 14 | Kapanış | İletişim |

## 📜 Referans dokümanlar

- `PARTNER_PROGRAM.md` — tam partner programı dokümantasyonu
- `PRICING.md` — fiyatlandırma ve margin modeli
- `adr/0012-partner-channel.md` — kanal mimarisi kararı

## 🏢 İletişim

Hashtag World Company
📧 info@hashtagworldcompany.com
