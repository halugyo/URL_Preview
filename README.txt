Link Tiles v3 — URLプレビュー一覧（iPad / Windows）

この版では「取得」を押すと即座にURL件数とカード一覧を表示し、先頭4件のサムネイル取得を開始します。スクロールで見えるカードのサムネイルを順次取得します。改行なしで連結したURL、空白区切り、改行区切りに対応します。「各リンクごとに改行」ボタンで、貼り付けたURLを1リンク1行に整形できます（重複も保持）。

重要：iPadOSでは、このフォルダのHTMLを「ファイル」アプリのクイックルックで開いても、JavaScriptが実行されない場合があります。iPadで利用するにはHTTPSで公開し、Safariからアクセスしてください。

GitHub Pagesで公開する手順
1. ZIPを展開し、GitHubで新規リポジトリを作成（Publicにする場合、個人情報を含むものは置かない）。
2. ZIP内のファイル一式（index.html / manifest.webmanifest / sw.js / icon-*.png / README.txt）をリポジトリのルートにアップロード。index.htmlがルート直下にある状態にします。
3. Settings → Pages → Build and deployment で「Deploy from a branch」を選び、main / /(root) を指定して保存。
4. 公開されたHTTPS URLをiPadのSafariで開く。
5. Safariの共有ボタン →「ホーム画面に追加」→「Webアプリとして開く」を有効にして追加。

Windowsなら単体版 link_tiles.html をChrome/Edgeで開いても動作します。

プレビュー画像について
サムネイル生成にはThum.ioのスクリーンショットAPIを使います。入力URLはこの外部サービスへ送信されます。非公開URL、ログイン必須URL、個人情報を含むURLは入力しないでください。API制限・ページ側の保護・ネットワーク制限により取得できない場合があります。数百件は一括しても一覧は作成されますが、画像はスクロールに合わせて順次取得します。
