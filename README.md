calc.
====

## 概要
* C言語で作成した電卓プログラム
* printf 以外の標準ライブラリ関数は，使用していない．

## 動作確認環境
* FreeBSD 4.3-RELEASE において，gcc-2.95.3 でコンパイルし，動作することを確認している．
* macOS Sierra 10.12.6 において，gcc-4.2.1 でコンパイルし，動作することを確認している．

## 入力と出力
入力は，標準入力のみ可能である．  
パイプによるファイルからの入力の場合，最初の 1 行のみを入力として受け取る．  
出力は，すべて標準出力で行う．  
その他の詳しい仕様については，Help コマンドを参照されたい．

##### コマンド一覧

|  コマンド文字列  |  機能  |
| ---- | ---- |
|  Help  |  本プログラムの仕様を表示する．  |
|  Exit  |  本プログラムを終了する．  |

## 使用例
        calc. > -1 + (+2) * 3 / (5%4) +sin(pi/2)-cos(pi)+tan(5*pi/4)-sqrt(4)+exp(2)+last+e^2-5!
                = -99.221888
        calc. > Exit
        good bye!
