# Dog Villa Holoholo の室内空間改善LP

## 概要
* 広告開始 2026-02-18〜
* 公開URL: https://app.kona-resort.jp/dvh/
* ホスティング: GitHub Pages（`main` ブランチ / ルートから配信）
* カスタムドメイン: `app.kona-resort.jp`（組織リポジトリ `app-kona.github.io` の apex CNAME を継承し、本リポジトリは `/dvh/` 配下で配信）

## 旧構成（〜2026-05-22）
* 旧URL: https://kona-resort.jp/holoholo202601/（Xserver へ直接アップ）
* GitHub Actions（SFTP / `deploy.yml`）で Xserver へ自動デプロイしていたが、GitHub Pages へ移行したため廃止
* 旧URLは新URLへリダイレクト（Xserver 旧フォルダの `index.html` をリダイレクトページに差し替え）

## 担当スタッフ
* 福永作成

## バージョン履歴
| 版 | ファイル | 時期 | 変更点・判断理由 |
|---|---|---|---|
| v1 | `index_v1_original.html` | 〜2026-06 | 初版 |
| v2 | `index_v2_夏プール.html` | 2026-07〜09 | 夏限定ドッグプールを看板に（ヒーローのポップ＋FV直下セクション） |
| v3 | `index.html` | 2026-10〜 | 秋冬仕様。薪ストーブと焚き火を看板にし、旧Warmthセクションを FV直下へ移して拡張（1日の流れ・FAQ3問追加）。薪は年中付くため「限定」とは書かない。ストーブにガードが無いため「安心」とは書かず注意書きで明記。犬と炎の実写が無いため、当面は既存の実写（`plan-bg.webp` / `stove.jpg`）で構成し、撮影後に差し替える |
