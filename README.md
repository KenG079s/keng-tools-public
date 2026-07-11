# KenG Tools

KenGが作成した業務ツールとポートフォリオの公開用静的HTMLサイトです。

## 公開URL

https://keng079s.github.io/keng-tools-public/

## 開くページ

- `index.html`: 共有用トップページ
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

## 使い方

1. 公開URLをSafariで開きます。
2. `iPhone整理を始める` を押します。
3. `設定 → 一般 → iPhoneストレージ` の現在値を入力します。
4. 安全確認チェックに沿って、iPhone側で整理します。
5. よく使う場合はSafariの共有ボタンから「ホーム画面に追加」します。

## 方針

- npmやビルド環境は不要です。
- 個人情報や認証情報は保存・送信しません。
- ログインが必要な外部ツールへのリンク集にはしません。
- 自動ログイン、自動投稿、外部サイトの自動取得はしません。
- データ削除は本人確認を前提とし、Webページから自動実行しません。
