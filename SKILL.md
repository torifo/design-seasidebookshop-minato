---
name: design-seasidebookshop-minato
description: "seaside bookshop landing-page design study — 'minato' theme/persona (pure HTML/CSS/JS, no build). Use when designing a 'minato'-style seaside bookshop site aesthetic. 船を待つ、頁を綴じる. seaside bookshopの「minato」テーマLPのデザイン参照スキル。"
---

# design-seasidebookshop-minato

A landing-page **design study** for a fictional **minato**-theme seaside bookshop (pure HTML + CSS + vanilla JS, no build, GitHub-Pages ready). Use this as a **style / design-system reference** when building a similar aesthetic.

架空の「minato」テーマのseaside bookshop LP デザイン研究。同種の世界観を作るときの**スタイル／デザインシステム参照**として使う。

## When to use / 使いどころ
- **EN:** designing a 'minato'-style seaside bookshop site — match its palette, typography and layout discipline.
- **JP:** 「minato」系のseaside bookshopサイトを設計するとき。配色・タイポ・レイアウト規律を流用。

## Bundled assets / 同梱アセット
This skill folder is the reference implementation — start from these files:
- `index.html` — full page markup
- `style.css` — design tokens (CSS custom properties) + layout
- `script.js` — vanilla JS (if present)
- `README.md` — full bilingual doc, brand context and series links

## Design reference / デザイン参照
_Lifted from the repo README — see README.md for the complete, bilingual version._

### Overview
**seaside bookshop design research series** の「瀬戸内の小港」ペルソナ作品。

船を待つ旅人や、静かな島旅を好む30〜50代に向けて、便箋・港の掲示板・活版のような落ち着いたデザインで構成した。

### Brand
| | |
|--|--|
| **Brand** | 港綴じ |
| **Tagline** | 船を待つ、頁を綴じる。 |
| **Aesthetic** | 瀬戸内の白壁 × 便箋 × 活版 |
| **Target Persona** | 島旅の途中で静かに本を選ぶ30〜50代 |
| **Books** | 随筆、短篇、島の小冊子、便箋、旅の紙もの |
| **Color** | Paper `#f8f3e7` + Ai `#1f4d65` + Rust `#a35a42` |
| **Display Font** | Shippori Mincho |
| **Body Font** | Zen Kaku Gothic New |

### Design Approach
- ヒーローは縦書き見出しと港写真の2カラムで、便箋の余白を作る
- 棚分類を「凪」「島影」「便り」「灯台」にし、通常のジャンル名を避ける
- 店主の日誌を港の掲示板のように短い文章で配置
- 予約や購入より、船便に合わせた来店情報を重視する

## Tech / 技術
- Vanilla HTML / CSS — single file (`index.html`)
- Google Fonts: Shippori Mincho, BIZ UDMincho, Zen Kaku Gothic New
- ビルドツール不要

## How to apply / 適用方法
1. Reuse `style.css` custom properties (color / type / spacing tokens) as the design-system base.
2. Copy `index.html` layout as the starting structure, then swap brand name and content.
3. Keep the palette, font pairing and layout discipline described above.

---
> The brand is fictional (design study) — replace all brand/content. Full context: see **`README.md`**.
