以下の markdown を参考にして、html を出力してください。
```md
# アルカディア零式固定募集要項
## クリア目安
4 ~ 5 週目 目標

## 活動頻度・時間
週3 ~ やる気次第
22:00 スタートを予定

## 活動開始時期
初週から

## 活動終了時期
全員最終装備が揃うまで(4 層を 8 回クリアが目安)

## ロット
未定(DPS 優先するかも？)

## 募集ロール
下記のロールから 2 名募集中です

- TANK
  MT or ST どちらでも
- DPS
  近接

## メンバー(仮)
- Regco Citrine
  MT or ST or 近接
- Misara Orangepekoe
  学者
- Kulo Neko
  ピュアヒーラー
- Torino Bulibas
  レンジDPS
- Sino  R'gray
  ピクトマンサー or 近接 or ST
- Et Cetra
  赤 or 侍

## 備考
- 勝手に野良練習・クリア OK
  クリアした層の消化は一緒にやります！活動日には参加してください！
  先にクリアした場合、キャリーお願いします！
- 欠員 OK
  欠員ある場合、野良補充して出発します！
- VC 参加自由
  聞き専 OK
  喋っても OK
  参加しなくても OK
```

要件は以下の通りです。

- FF14のジョブのロールごとに色分けをすること
  TANK: 青, HEALER: 緑, DPS: 赤
  - この色分けは、一番左に書いてあるジョブをもとに決めること
  - キャラクター名のみに色を付けて、ジョブ名には色をつけないこと
- 以下のスタイルを利用すること
```html
<style>
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
  }
  .container {
    max-width: 800px;
    margin: 20px auto;
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  h1, h2 {
    color: #333;
  }
  ul {
    padding: 0;
    margin: 0;
    list-style-type: none;
  }
  li {
    margin-bottom: 10px;
  }
  .note {
    background-color: #f9f9f9;
    padding: 20px;
    border-left: 4px solid #ccc;
    margin-top: 20px;
  }
  .note h2 {
    margin-top: 0;
  }
  .note ul {
    list-style-type: none;
    padding-left: 20px;
  }
  .note li {
    position: relative;
  }
  .note li:before {
    content: "•";
    position: absolute;
    left: -20px;
    color: #999;
  }
  .tank { color: blue; }
  .healer { color: green; }
  .dps { color: red; }
</style>
```
