# HITGS 応援法 / 3列表示

HITGSの応援法を3列で確認するための静的HTMLサイトです。

## 内容

- `index.html`: 8曲を表示する単一HTMLファイル。CSSとJavaScriptを内蔵し、外部の依存ライブラリはありません。
- `.nojekyll`: GitHub PagesがJekyllを用いた処理を行わないようにするための空ファイル。

## ローカル表示

`index.html` をブラウザで開いてください。

## GitHub Pagesでの公開

1. GitHubで公開用リポジトリ（例: `hitgs-fanchants`）を作成します。
2. このフォルダのファイルをリポジトリのルートに配置して、`main` ブランチにコミットします。
3. GitHubのリポジトリの **Settings → Pages** を開きます。
4. **Build and deployment → Source** で **Deploy from a branch** を選択します。
5. **Branch** を `main`、フォルダを `/(root)` に設定して保存します。
6. 公開URLの形式は `https://<GitHubユーザー名>.github.io/<リポジトリ名>/` です。

GitHubで `index.html` を編集し、`main` ブランチにコミットすると、通常は自動で更新されます。
