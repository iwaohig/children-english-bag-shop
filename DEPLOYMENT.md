# GitHub Pages デプロイ手順 🚀

## 1. GitHubリポジトリ作成

1. [GitHub](https://github.com) にログイン
2. 「New repository」をクリック
3. Repository name: `children-english-bag-shop`
4. 「Public」を選択（GitHub Pages用）
5. 「Create repository」をクリック

## 2. ローカルからプッシュ

```bash
# 現在のディレクトリで実行
git add .
git commit -m "Initial commit: WOFF lesson bag shop"
git remote add origin https://github.com/YOUR_USERNAME/children-english-bag-shop.git
git push -u origin main
```

## 3. GitHub Pages 設定

1. GitHubのリポジトリページで「Settings」タブ
2. 左サイドバーの「Pages」をクリック
3. Source: 「GitHub Actions」を選択
4. 自動的にデプロイが開始されます

## 4. デプロイ完了確認

- 数分後に `https://YOUR_USERNAME.github.io/children-english-bag-shop/` でアクセス可能
- 「Actions」タブでデプロイ状況を確認

## 5. WOFF Developer Console 設定

1. [LINE WORKS Developer Console](https://developers.worksmobile.com/jp/console/)
2. 対象のWOFFアプリを選択
3. **Service URL** に以下を追加:
   ```
   https://YOUR_USERNAME.github.io/children-english-bag-shop/
   ```

## 6. テスト方法

- LINE WORKS アプリでWOFFを開いてテスト
- または直接ブラウザでアクセス（WOFF機能は制限あり）

---

✨ デプロイ完了後は、LINE WORKS内でフル機能をテストできます！