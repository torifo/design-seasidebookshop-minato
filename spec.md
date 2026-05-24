# 港綴じ — design-seasidebookshop-minato Spec

**Status:** Approved  
**Author:** torifo  
**Created:** 2026-05-24  
**Updated:** 2026-05-24

## 1. Overview

### Problem Statement
小さな港町の書店サイトは、観光案内か一般的なECに寄りやすく、船を待つ時間や島旅の静けさが伝わりにくい。

### Goal
「港綴じ」という架空書店を、瀬戸内の小港にある便箋のようなサイトとして実装する。旅人が来店前に、棚の気配と営業時間を静かに把握できることを目指す。

### Non-Goals
- EC機能
- 派手な波アニメーション
- 大型キャンペーン導線

## 2. User Stories

| ID | Persona | Want to | So that |
|---|---|---|---|
| US-01 | 島旅の旅人 | 船の待ち時間に読める本を知りたい | 短時間でも一冊を選べる |
| US-02 | 静かな旅を好む30〜50代 | 店の雰囲気を事前に知りたい | 入店しやすいか判断できる |
| US-03 | 紙ものが好きな来店者 | 本以外の便箋や栞も知りたい | 旅の記念を選べる |

## 3. Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | 縦書きヒーローと港写真 | P0 |
| FR-02 | 航路に見立てた4分類の棚 | P0 |
| FR-03 | 港日誌の2x2掲示板 | P1 |
| FR-04 | 船便に合わせた営業時間表示 | P0 |
| FR-05 | 820px以下で1カラム化 | P0 |

## 4. Architecture

```text
index.html
├── nav
├── section.hero
├── section.shelf
├── section.diary
├── section.visit
└── footer
```

## 5. Design System

```css
--paper: #f8f3e7;
--ink:   #172333;
--ai:    #1f4d65;
--rust:  #a35a42;
--line:  #c9bdab;
```

## 6. Testing Strategy

| Layer | Scenarios |
|---|---|
| Desktop | 縦書きヒーロー、港日誌、棚4列 |
| Mobile | 1カラム化、縦書き解除、ナビ折り返し |
| Typography | 明朝体とゴシック体の読み込み |
