# Peace Beam Invaders v10.1

v10のボタン無反応を修正した版です。

## 修正内容

- `SHIELD_CD` と `SHIELD_DURATION` の未定義エラーを修正
- `enemyBullets`, `dangerBombs`, `barriers` の未宣言エラーを修正
- 1人プレイ時のパー防御クールダウン表示を修正
- JavaScript構文チェック済み

## v10系の追加機能

- 敵弾
- 1人プレイ時のパー防御
- 2人プレイ時のパー妨害
- チャージャー突進予兆
- Lv10 / Lv20 ボス攻撃
- カウントダウン爆弾

## GitHub Pages公開方法

このzipを解凍し、以下3ファイルをリポジトリ直下に置いてください。

- `index.html`
- `.nojekyll`
- `README.md`

GitHub Pages設定は以下です。

- Source: Deploy from a branch
- Branch: main
- Folder: /(root)

zipのままアップロードしても動きません。
