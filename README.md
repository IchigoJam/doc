# IchigoJam doc

## appdoc - アプリで見るドキュメント

- [IchigoJam BASIC 1.4 コマンド一覧](https://fukuno.jig.jp/app/csv/ichigojam-cmd.html)  
- [IchigoJam BASIC 1.4 command list (English)](https://fukuno.jig.jp/app/csv/ichigojam-cmd.html#lang=en)  

## printdoc - 印刷用ドキュメント

- [IchigoJam BASIC 1.4 コマンド一覧 やさしい順](https://fukuno.jig.jp/app/csv/ichigojam-cmd-paper.html)  
- [IchigoJam BASIC 1.4 コマンド一覧 ABC順](https://fukuno.jig.jp/app/csv/ichigojam-cmd-paper.html#1)  
- [IchigoJam BASIC 1.4 コマンド一覧 カテゴリ順](https://fukuno.jig.jp/app/csv/ichigojam-cmd-paper.html#3)  

- [IchigoJam BASIC 1.4 commnad list - sorted by easy](https://fukuno.jig.jp/app/csv/ichigojam-cmd-paper.html#0en)  
- [IchigoJam BASIC 1.4 commnad list - sorted by alphabet](https://fukuno.jig.jp/app/csv/ichigojam-cmd-paper.html#1en)  
- [IchigoJam BASIC 1.4 commnad list - sorted by category](https://fukuno.jig.jp/app/csv/ichigojam-cmd-paper.html#3en)  

## doc for IchigoJam 1.5β

- [IchigoJam BASIC 1.5β コマンド一覧](https://ichigojam.github.io/doc/IchigoJam-1.5.html)  

## IchigoJam pins - IchigoJamピン機能

|label|in_n|out_n|IchigoJam 1.4|IchigoJam 1.5|
|-|-|-|-|-|
|IN1|1|8||ANA|
|IN2|2|9|ANA、プルアップ不可|ANA, DAC対応|
|IN3|3|10|プルアップ不可、I2C併用|ANA, DAC対応|
|IN4|4|11||ANA|
|BTN|9||ANA(), BTN()|ANA(), BTN()|
|LED||7|LED n|LED n|
|OUT1|5|1|ANA|PWM対応|
|OUT2|6|2|ANA, PWM対応|ANA, PWM対応|
|OUT3|7|3|ANA, PWM対応|ANA, PWM対応|
|OUT4|8|4|ANA, PWM対応|ANA, PWM対応|
|OUT5|10|5|PWM対応|ANA, PWM対応|
|OUT6|11|6||ANA, PWM対応|

- ANA ANA(in_n) (BTNのアナログ入力は ANA()、ANA* = 対応予定)
- 入力プルアップ設定 OUT out_n,-2 (入力プルアップなし設定 OUT out_n,-1)
- DAC out_n,val (val: 0-1023)
- PWM out_n,val (val: 0-2000、第三パラメータで周期変更可能 1.5でも対応予定）


