# saselab-clock

東北学院大学の授業時間がひと目でわかる、黒背景のシンプルな時計ウェブアプリです。フルHDのテレビ表示を想定しています。

公開ページ: https://sasekazu.github.io/saselab-clock/

![表示例](docs/screenshot-weekday-no-austria.png)

## 機能

- 日本時間（Asia/Tokyo）のアナログ時計と、日付・曜日・時刻のデジタル表示
- 早朝・朝・昼・夕・夜をアイコンと色で表示
- 東北学院大学の時間割（1校時 8:45〜 / 礼拝 / 2校時 / 昼休み / 3〜5校時）に合わせて、いま何校時か、あと何分で終わる／始まるかを表示
  - 土日・祝日は表示しません。休校日は考慮していません
- オーストリア時間（Europe/Vienna）のサブ時計。画面右下の薄いボタン、`A` キー、URL の `?austria=off` で非表示にできます

## 構成

ビルド不要の静的サイトです（`index.html` のみ。README 用の画像は `docs/`）。
フォントは Google Fonts の Murecho を読み込みます（オフラインでは代替フォント）。
