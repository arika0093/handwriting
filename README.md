# Japanese Handwriting
## what's this
日本語の手書き文字生成css+javascript.

## how to use
1. 予め`jQuery`, `SugarJS`を読み込む  
2. `handwriting.js`, `handwriting.css`を読み込む
3. 手書き化したい要素に`hw`クラスを付与

## sample
![CharBeautyRate=500](https://qiita-image-store.s3.amazonaws.com/0/282132/06526093-d1eb-33c1-f834-151eea3c82d6.png)

## more
* `CharBeautyRate`の値を調節することで手書きの綺麗さ度合いを調節可能
* `.hw`クラスは`javascript`により自動で傾き調整等が行われます。
	* この際、内部タグ等は破壊されるので注意してください。
* `.hwp`クラスについては非破壊なので内部タグも自由に使えます。

## cf


## thanks
ダーツフォントおよびKalamフォントを使用しています。  
http://www.p-darts.jp/font/dartsfont/  
https://fonts.google.com/specimen/Kalam?selection.family=Kalam  
