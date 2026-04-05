# images/1x フォルダー

実案件用の 1x 素材を置くフォルダーです。

## 主なファイル

- `navi_bg.png`
  - ナビゲーション背景画像

- `hero-bg.png`
  - Hero セクション背景

- `hero-company-name.png`
  - Hero 内の会社名画像

- `hero-venue-logo.png`
  - Hero 内のロゴ素材

- `clm_bg_v1.png`
  - カラム背景

- `clm_icon.png`
  - カラム用アイコン

- `h2-icon-v1.png`
  - 見出しアイコン

- `h2-text-v1.png`
  - 見出しテキスト画像

- `p-text-v1.png`
  - 本文系画像素材

## 運用ルール

- 新しい画像は用途がわかる名前にする
- `v1`, `v2` が増える場合は、使っていない旧版を整理する
- デザイン差し替え時は、HTML / CSS の参照先も確認する

## ナビ背景について

現在のナビ背景は `custom.css` から以下の画像を参照しています。

```css
background-image: url("../images/1x/navi_bg.png");
```
