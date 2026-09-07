# Honeymoon 2026 — Travel Research

Spain & France 9-day journey research digest.

## Reports

- **Index**: <https://ryota-09.github.io/honeymoon-plan/>
- **France**: <https://ryota-09.github.io/honeymoon-plan/french/summary.html>
- **Spain**: <https://ryota-09.github.io/honeymoon-plan/spanish/summary.html>

## Structure

```
.
├── index.html                  # Landing page
├── robots.txt                  # noindex policy
├── base.md                     # Trip basics
├── results.md / .html          # 9日間旅程(改訂版v5・現行)
├── hotels.md / .html           # ホテル調査(確定2軒 + 候補)
├── msm-tour.md / .html         # MSM ツアー(VELTRA・予約確定)
├── private/                    # 🔒 予約番号・暗証番号(gitignore 済み・非公開)
│   ├── bookings.local.md       #    予約控え一覧
│   └── tickets/                #    e チケット・入場券 PDF の原本
├── french/
│   ├── summary.html            # Cross-section summary (rendered)
│   ├── summary.md              # Cross-section summary (source)
│   ├── 01_paris.md
│   ├── 02_mont_saint_michel_normandy_loire.md
│   ├── 03_south_france.md
│   ├── 04_other_regions.md
│   └── 05_honeymoon_insights.md
└── spanish/
    ├── summary.html            # Cross-section summary (rendered)
    ├── summary.md              # Cross-section summary (source)
    ├── 01_barcelona.md
    ├── 02_madrid.md
    ├── 03_andalusia.md
    ├── 04_other_regions.md
    └── 05_honeymoon_insights.md
```

## Notes

- Private travel planning document.
- Crawlers are blocked via `<meta name="robots" content="noindex">` and `robots.txt`.
- Prices in JPY (1 EUR ≈ 170 yen, as of 2026-05).
- **⚠️ This repository is PUBLIC on GitHub.** Booking reference numbers, PINs, e-ticket
  numbers, card details and dates of birth are **never** written into the tracked
  documents. They live in `private/bookings.local.md`, which is excluded via
  `.gitignore`. Keep it that way when editing.
