# 港綴じ — design-seasidebookshop-minato

> **架空ブランド注記**: 港綴じは本デザイン研究のために作成した架空書店です。実在の店舗・商品ではありません。

## Overview

**seaside bookshop design research series** の「瀬戸内の小港」ペルソナ作品。

船を待つ旅人や、静かな島旅を好む30〜50代に向けて、便箋・港の掲示板・活版のような落ち着いたデザインで構成した。

## Brand

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

## Design Approach

- ヒーローは縦書き見出しと港写真の2カラムで、便箋の余白を作る
- 棚分類を「凪」「島影」「便り」「灯台」にし、通常のジャンル名を避ける
- 店主の日誌を港の掲示板のように短い文章で配置
- 予約や購入より、船便に合わせた来店情報を重視する

## Tech

- Vanilla HTML / CSS — single file (`index.html`)
- Google Fonts: Shippori Mincho, BIZ UDMincho, Zen Kaku Gothic New
- ビルドツール不要

## Local Development

```bash
open index.html
# または
python3 -m http.server 8080
```

## Series

このサイトは **seaside bookshop design research series** の一作です。
