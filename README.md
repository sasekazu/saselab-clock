# saselab-clock

黒背景のシンプルな時計ウェブアプリ。

- メイン: 日本時間（Asia/Tokyo）のアナログ時計 + 日付・曜日・時刻のデジタル表示
- サブ: オーストリア時間（Europe/Vienna、夏時間自動対応）の小さな時計

- 授業時間表示: 平日（土日・祝日を除く）に、いま何校時か・次のコマ開始/終了まであと何分かを表示
  （1校時 8:45〜 / 礼拝 / 2校時 / 昼休み / 3〜5校時。祝日は内蔵ロジックで判定、休校日は考慮しません）

ビルド不要の静的サイト（`index.html` のみ）です。

## 公開ページ

https://sasekazu.github.io/saselab-clock/

## GitHub Pages の設定

リポジトリの **Settings → Pages → Build and deployment** で
Source を「Deploy from a branch」、Branch を公開したいブランチ / `/ (root)` に設定してください。
