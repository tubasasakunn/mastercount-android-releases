# mastercount for Android

カウント、ランキング、プライベートブラウザとホーム画面ウィジェットを備えたAndroidアプリです。このリポジトリでは、公式の署名付きAPKを配布します。

[最新のリリース](https://github.com/tubasasakunn/mastercount-android-releases/releases/latest)

## インストール

[スクリーンショット付きの入れ方・ダウンロード](https://mastercount-api.testbasaapp.workers.dev/android)で、保存したファイルの開き方から設定の許可、インストール、LINEログインまで案内しています。画像はタップして拡大できます。

1. 一般的なスマートフォンでは `mastercount-arm64-v8a.apk` をダウンロードして開きます。
2. Androidに確認された場合は、APKを開いたブラウザやファイルアプリからのインストールを許可します。
3. mastercountを開き、LINEでログインして表示名を設定します。

64ビット版Android 9以上、LINEアカウント、更新済みのAndroid System WebViewが必要です。x86_64端末・エミュレーターには `mastercount-universal.apk` を使えます。更新時はアプリを削除せず、新しいAPKを上書きインストールしてください。

## ウィジェット

アプリの設定から「ホーム画面ウィジェット」を追加するか、ホーム画面のウィジェット一覧でmastercountを選びます。「＋」はオフラインでも記録し、接続後に同期します。

## 保存データ

表示名とカウント回数はランキングに公開されます。ブラウザからカウントすると、そのときのタブのURLをカウント履歴に保存し、タブとサイトのログイン情報を消去します。履歴・ブックマーク・設定のクラウド同期は、それぞれ初期状態ではオフです。Cookieやサイトのログイン情報は同期しません。

## ファイルの確認

各リリースの `SHA256SUMS`、`provenance.json` と署名証明書のSHA-256を確認できます。署名鍵を継続して使うため、同じ提供元の新しいAPKで更新できます。

Swift、AndroidX、Rust adblock engine、フィルターリストなどのライセンスはアプリの「オープンソースライセンス」に収録しています。MPL対象のadblock-rust 0.13.5の未改変ソースは[公式crate](https://crates.io/api/v1/crates/adblock/0.13.5/download)から入手できます。フィルターのソースとライセンスはAPK内にも含まれます。

[プライバシー](https://mastercount-api.testbasaapp.workers.dev/privacy) · [利用規約](https://mastercount-api.testbasaapp.workers.dev/terms) · [お問い合わせ](mailto:bassa.application@gmail.com)

BasaApp Technologies
