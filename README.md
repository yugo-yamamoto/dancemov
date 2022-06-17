## これは何？

ダンス動画から部分的にループするためのJavaScriptデモです。

## TODO

- デモ用データを持ってくる（済）
  - Twiceのmomoでいいか
  - andoridプレーヤーのエミュレータをPC上で動かすみたい


- まずはvideoタグに埋め込む（済）
- JavaScriptで反転させてみる（済）
- FlashでいうEvent.ENTER_FRAME みたいなイベントを探す
  - durationはvideoの長さでした
  - requestAnimationFrame というのがあるけどこれはvideoとは関係ない
  - ENTER_FRAMEはHTML5にはなさそう
  - あったとしてもcanvasアニメーションでした
- ENTR_FRAMEは諦めてsetIntervalで繰り返し処理を作る
  - setIntervalで今の再生時刻を知る
  - 指定の時間より超えていたら今の再生時刻を戻す
  - これで繰り返す
- 遅く再生する機能を探す
- ここまでプレイしましょう的なメソッドを探す
- 最初はハードコーディングでデモが動くところまで実現する
- 徐々に変数にする
- それをJSONで渡すだけで動くものにする
- そのJSONを作るUIを作る

