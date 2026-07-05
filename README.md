# Peace Beam AR

カメラで手を認識し、ピース判定で画面上にビームを撃つブラウザAR試作です。

## 使い方

1. GitHub Pagesで公開する
2. 公開URLをスマホのSafari/Chromeで開く
3. 「カメラを開始」を押す
4. ピースする
5. 認識が通ればビームと音が出ます

## 重要

このアプリはMediaPipe Hand Landmarkerをブラウザで読み込みます。ChatGPT内プレビューや `file://` 直開きでは、カメラ・WASM・外部モデル読み込みが失敗することがあります。

GitHub Pages、Netlify、Vercel、localhostなど、HTTPS相当の環境で開いてください。

## ファイル構成

- `index.html`：アプリ本体。CSS/JS込みの単一HTML
- `.nojekyll`：GitHub Pagesで余計なJekyll処理を避けるための空ファイル

## 切り分け

- 「ビームと音だけテスト」で出る → CanvasとWeb Audioは正常
- カメラは映るがモデル失敗 → MediaPipe/WASM/モデル読み込みの問題
- カメラも映らない → ブラウザ権限またはHTTPS環境の問題
- 「診断ログ」で MODULE / WASM / MODEL のどこで落ちたか確認できます
