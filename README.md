# BIND風タブスワイプデモ

ネイティブアプリのようなスワイプ操作を実装したWebデモ。

## デモ

**[https://hide5459.github.io/bind-swipe-demo/](https://hide5459.github.io/bind-swipe-demo/)**

## 特徴

- **ネイティブライクなスワイプ** - タッチ/マウスドラッグ対応
- **慣性スクロール** - velocity検知でフリック操作に対応
- **端での抵抗感** - 最初/最後のタブで自然な抵抗
- **スナップアニメーション** - なめらかな収束動作
- **iOS風デザイン** - ダークモード対応

## 技術スタック

- Pure JavaScript (依存なし)
- CSS Transform + Transition
- Touch Events API
- GPU加速 (`translateX`)

## ローカルで試す

```bash
open index.html
```
