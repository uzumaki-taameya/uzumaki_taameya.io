# Personal Site (GitHub Pages)

note.comのコンテンツファースト思想とAndroidアプリ向けデザインシステムに準拠した、個人向けブログ・Webサイトです。

## 構成ファイル
- `index.html`: 記事一覧ページ（プロフィール、タブ、カードグリッド、ボトムナビゲーション）
- `article.html`: 記事詳細ページ（アイキャッチ、メタ情報、タイポグラフィ、リアクション・スキ機能）
- `style.css`: note風デザインシステムCSSトークン・コンポーネントスタイル

## GitHub Pagesへのデプロイ手順
1. 本フォルダ内のファイルをGitHubのリポジトリにプッシュします。
2. GitHubリポジトリの **Settings** > **Pages** に移動します。
3. **Build and deployment** の Source で **Deploy from a branch** を選択します。
4. Branch に `main` (または `master`)、フォルダに `/ (root)` を指定して **Save** をクリックします。
5. 数分後に発行されるURL（`https://<ユーザー名>.github.io/<リポジトリ名>/`）でアクセス可能になります。
