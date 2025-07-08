# レッスンバッグ販売サイト 🎒

ワークス英語教室向け LINE WORKS WOFF 対応のレッスンバッグ販売ページです。

## 🚀 デモサイト

GitHub Pages で公開中: [https://your-username.github.io/children-english-bag-shop/](https://your-username.github.io/children-english-bag-shop/)

## 📱 機能

- **モバイル最適化デザイン**: スマートフォンでの利用を重視
- **WOFF SDK 統合**: LINE WORKS内でユーザー情報を自動取得
- **商品ラインナップ**:
  - しまじろうレッスンバッグ (¥2,980)
  - ワークスロゴレッスンバッグ (¥2,480)
- **購入履歴表示**: ユーザーの過去の購入履歴を確認可能
- **購入完了通知**: LINE WORKS Bot による通知機能

## 🛠️ 技術スタック

- **フロントエンド**: HTML5, CSS3, JavaScript
- **WOFF SDK**: LINE WORKS Office SDK
- **バックエンド**: AWS Lambda + API Gateway
- **データベース**: DynamoDB
- **通知**: LINE WORKS Bot API

## 🔧 WOFF Developer Console 設定

1. [LINE WORKS Developer Console](https://developers.worksmobile.com/jp/console/) にアクセス
2. 対象のWOFFアプリを選択
3. **設定 > Basic Info > Service URL** に以下を追加:
   ```
   https://your-username.github.io/children-english-bag-shop/
   ```
4. **Bot > Webhook URL** (オプション): 通知機能用

## 📦 API エンドポイント

- **購入API**: `https://im1swit6p3.execute-api.ap-northeast-1.amazonaws.com/prod/purchase`
- **メソッド**: POST (購入), GET (履歴取得)

## 🎯 使用方法

1. LINE WORKS アプリ内でWOFFを開く
2. 商品を選択して「購入する」をタップ
3. 確認モーダルで「購入する」を選択
4. 購入完了！

## 📋 環境設定

WOFF ID: `ZA6K3pOTK1amAQ0di7QJng`
Bot ID: `10370300`

---

© 2025 ワークス英語教室