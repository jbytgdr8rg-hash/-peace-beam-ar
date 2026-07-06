# Peace Beam Invaders v10

ブラウザARゲーム「ゆびビーム / Peace Beam Invaders」のv10です。

## v10追加機能

- 敵弾
  - 敵弾はビームで撃ち落とせます
  - 防衛ラインに到達するとライフが減ります
- 1人プレイ時のパー防御
  - パーで短時間バリア
  - クールタイム10秒
  - 下段の敵弾を防ぎます
- 2人プレイ時のパー妨害は維持
  - 相手ゾーンに敵を追加
  - クールタイム20秒
- チャージャーの突進予兆
  - 赤い「!」とフラッシュで突進前に知らせます
- ボス攻撃
  - Lv10ボス：3方向弾
  - Lv20ボス：扇状弾、カウントダウン爆弾、ノイズ演出、雑魚召喚
- カウントダウン爆弾
  - 数秒以内に撃つと解除
  - 放置するとライフ減少＋敵追加

## 公開方法

GitHub Pagesのブランチ公開で使う前提です。

1. このzipを解凍
2. `index.html`, `.nojekyll`, `README.md` をリポジトリ直下に置く
3. Settings → Pages
4. Source: Deploy from a branch
5. Branch: main / Folder: /(root)

`file://` ではMediaPipeモデルの読み込みが失敗しやすいため、必ずGitHub PagesのHTTPS URLで開いてください。
