# brace.md
## 概要

```bash
touch {1..10}.md #1から10までのマークダウンファイルを作成する
touch {a..z}.md  #aからzまでのマークダウンファイルを作成する

#3文字指定するとステップ数を指定出来る
echo {1..10..2}  #1 3 5 7 9

#指定をする
echo I {am,are} #I am ,I are

#カンマをなにもない場所に指定すると直前の文字をいれる
#e.g. バックアップファイルもついでに作成
cp somefile{,.bak} # somefile , fomefile.bak

```
* コマンドを指定する時に{}を使うとうまいことコマンドを実行してくれる
	* これをブレーズ展開と言う。

