# 立命館大学３回生　メディア処理実験　CG最終課題
## 概要

CG最終課題のために作ったThreeJS+Canvasの簡単なゲームです。<br />
プレイヤーは画面上から降ってくる３個の敵（ブロック）と衝突して、ブロックの色に相当するポイントをもらう簡単なゲームです。<br />
プレイヤーは横からでしか動けません（左はA、右はDボタンを押す）

## Canvasの上のボタン
最初は、StartボタンとResetボタンがあります。<br /><br />
Startボタンを押すとゲームが始まり（Canvas表示）、StartボタンがPauseボタンに変わります。Pauseボタンを押すと、ゲームはボタンが押された瞬間に止まり、PauseボタンがRestartボタンに変わります。Restartボタンを押すと、ゲームが再開され、RestartボタンがPauseボタンに変わります。<br /><br />
Resetボタンを押すとゲームが一回止まり、すべてのゲームデータ（ポイント等）が消えます。そして、上のボタンがStartボタンに戻り、Startボタンを押すとゲームが１からスタートします。

## 敵の色とポイント
赤：-100ポイント　　ピンク：+100ポイント　　緑：+200ポイント

## ポイントについて
ポイントを獲得するにつれて敵の速度が上がります。<br />
また、今持っているポイントを消費して、プレイヤーの速度を上げることができる（キーボードのSpaceを押す）

## Statsについて
画面の右上に、フレームレート等のステータスを表示しています。

## 画面の下の情報
それぞれ、現在のポイント、合計ポイント、プレイヤーの速度、次の速度パワーアップに必要なポイント、を表しています。
