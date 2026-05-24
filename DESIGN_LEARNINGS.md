# 港綴じ Design Learnings

## 目的

瀬戸内の小港にある書店として、海辺らしさを「青い装飾」ではなく、船を待つ時間、便箋、掲示板、日誌で表現した。

## 設計したこと

- 縦書きの大型見出しで、日本語の静けさと港町の時間感覚を出した。
- 4つの棚名を通常ジャンルではなく「凪」「島影」「便り」「灯台」にした。
- `港日誌` はニュースカードではなく、店先の掲示板のような短文にした。
- CTAを購入ボタンにせず、船便に合わせた開店情報へ寄せた。

## CSS

```css
body {
  background-image: linear-gradient(90deg, rgba(31,77,101,.04) 1px, transparent 1px);
  background-size: 42px 42px;
}

h1 {
  writing-mode: vertical-rl;
  font-family: "Shippori Mincho", serif;
}
```

## 学び

静かな書店サイトでは、視線を奪う装飾よりも、棚名や日誌の言葉がデザインの中心になる。余白と罫線を便箋のように扱うと、写真に頼らず土地の気配を作れる。
