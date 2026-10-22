# taskel-privacy-policy

Taskel（iOS アプリ）のプライバシーポリシーと利用規約。GitHub Pages で配信する静的ファイル。
アプリ本体のリポジトリ（private）からは submodule `web/privacy-policy` として参照する。

- 内容の正はアプリ本体リポジトリの `docs/legal/`。ここは公開物（HTML）。
- **公開済み（Version 1.1、Effective date 2026-10-22。1.1 でネイティブ広告の記述を削除）。** 未確定項目の印・draft バナー・noindex は残っていない。Crashlytics（#110）と Analytics（#112）は develop 入り済み。
- URL（Pages を有効化後）:
  - https://norinoriver.github.io/taskel-privacy-policy/privacy-policy.html
  - https://norinoriver.github.io/taskel-privacy-policy/terms-of-use.html
- v2 以降で Cloudflare Workers へ移す予定。
- 注意: `app-ads.txt` は AdMob がドメイン直下（`https://<domain>/app-ads.txt`）しか読まない。
  プロジェクトサイト（`https://norinoriver.github.io/taskel-privacy-policy/`）では直下にならないので、
  広告の配信開始までに置き場所（ユーザーサイトか独自ドメイン）を決める。

## Pages の設定

Settings > Pages > Source: Deploy from a branch / Branch: `main` / `/ (root)`。
