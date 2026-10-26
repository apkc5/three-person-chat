# 3人チャット — API代ゼロの手動連携MVP

## 使い方
1. 公開されたページをブラウザで開きます。
2. 君 / ChatGPT / Muse を選び、発言を保存します。
3. 「ChatGPT用にコピー」または「Muse用にコピー」を押し、各サービスの画面に貼り付けて送信します。
4. AIの返答をコピーし、発言者を選んでこのアプリに保存します。
5. 共有記憶を編集し、定期的にJSONバックアップを保存してください。

## GitHub Pages
Settings → Pages → Build and deployment で「Deploy from a branch」を選択し、Branch を `main)、folder を `/ (root)` にして Save します。

## 制約
ブラウザ内保存のため自動同期はありません。ログイン、クラウド同期、暗号化、自動送信は未実装です。MuseのURLは利用中サービスの正式なURLを設定してください。