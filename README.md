# KenG Tools

KenGが作成した業務ツールとポートフォリオの公開用静的HTMLサイトです。

## 公開URL

https://keng079s.github.io/keng-tools-public/

## 開くページ

- `index.html`: 共有用トップページ
- `tools/hotpepper-post-manager.html`: Hot Pepper 投稿PDCA
- `tools/iphone-storage-organizer.html`: iPhoneストレージ整理ナビ
- `tools/ark-commission-calculator.html`: ARK歩合計算機
- `portfolio.html`: ポートフォリオ

## iPhone整理ナビ

- 現在の総容量・使用量を入力
- アプリごとの容量と削減予定を入力
- 整理後の空き容量を自動計算
- LINE、Lightroom、写真、大容量アプリを安全な順番で整理
- 入力値と進捗はSafariの端末内ストレージだけに保存
- iPhone内の写真・動画・アプリを自動削除しない安全設計

## Hot Pepper 投稿PDCA

- 投稿テーマ、投稿種別、閲覧数、予約数をiPhone内に保存
- 直近15日間の投稿数、閲覧数、予約数、予約率を自動計算
- 次の投稿案と共有用まとめを作成
- JSONバックアップと復元に対応
- Hot Pepper Beautyへの自動ログイン・自動投稿は行わない

## 使い方

1. 公開URLをSafariで開きます。
2. 使うツールを押します。
3. Hot Pepper 投稿PDCAでは、顧客情報を入れずに投稿テーマと合計値だけを記録します。
4. よく使うツールはSafariの共有ボタンから「ホーム画面に追加」します。

## 方針

- npmやビルド環境は不要です。
- 個人情報や認証情報は保存・送信しません。
- ログインが必要な外部ツールへのリンク集にはしません。
- 自動ログイン、自動投稿、外部サイトの自動取得はしません。
- データ削除は本人確認を前提とし、Webページから自動実行しません。
