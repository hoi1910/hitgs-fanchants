# HITGS 応援法 / 3列表示

HITGSの応援法を3列で確認するための静的HTMLサイトです。

## 内容

- `index.html`: 8曲を表示する単一HTMLファイル。CSSとJavaScriptを内蔵し、外部の依存ライブラリはありません。
- `.nojekyll`: GitHub PagesがJekyllを用いた処理を行わないようにするための空ファイル。

## ローカル表示

`index.html` をブラウザで開いてください。

## GitHub Pagesでの公開（必要な権利許諾を確認したうえで実施）

1. GitHubで公開用リポジトリ（例: `hitgs-fanchants`）を作成します。
2. このフォルダのファイルをリポジトリのルートに配置して、`main` ブランチにコミットします。
3. GitHubのリポジトリの **Settings → Pages** を開きます。
4. **Build and deployment → Source** で **Deploy from a branch** を選択します。
5. **Branch** を `main`、フォルダを `/(root)` に設定して保存します。
6. 公開URLの形式は `https://<GitHubユーザー名>.github.io/<リポジトリ名>/` です。

GitHubで `index.html` を編集し、`main` ブランチにコミットすると、通常は自動で更新されます。

## 著作権に関する注意

このHTMLには第三者が著作権を保有する可能性がある歌詞が含まれます。私的利用と不特定多数への公開は異なります。公開前に権利者・著作権管理者の許諾や利用条件を確認してください。GitHub Pagesはプライベートリポジトリを使用しても、通常サイト自体は公開されます。
