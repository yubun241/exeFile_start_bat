##  exeFile_start_bat
exeファイルを起動するためのバッチファイルのつくり方


## コード
@echo off

set EXE_PATH=　# pathを入れて下さい


echo 実行中: %EXE_PATH%

start "" %EXE_PATH%

※添付ファイル参考


## 手順
① TEXTファイルに上記のプログラムを転記
② Pathを追加
③ ファイル名を.batに変更
