# taskel-privacy-policy

Taskel（iOS アプリ）のプライバシーポリシーと利用規約。GitHub Pages で配信する静的ファイル。
アプリ本体のリポジトリ（private）からは submodule `web/privacy-policy` として参照する。

- 内容の正はアプリ本体リポジトリの `docs/legal/`。ここは公開物（HTML）。
- **まだ下書き（draft）。** `{{TODO:...}}` が残っている間は公開扱いにしない（各 HTML に draft バナーと `noindex` がある）。
- v2 以降で Cloudflare Workers へ移す予定。
- 注意: `app-ads.txt` は AdMob がドメイン直下（`https://<domain>/app-ads.txt`）しか読まない。
  プロジェクトサイト（`https://norinoriver.github.io/taskel-privacy-policy/`）では直下にならないので、
  広告の配信開始までに置き場所（ユーザーサイトか独自ドメイン）を決める。

## Pages の設定

Settings > Pages > Source: Deploy from a branch / Branch: `main` / `/ (root)`。
