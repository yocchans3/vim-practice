# vim-practice

## 移動
:set number

|コマンド|内容|
|---|---|
|G|ファイルの末尾に移動|
|gg|ファイルの先頭に移動|
|$|行の最後に移動|
|0|行の先頭へ移動(インデント無視して先頭へ)|
|^|行の先頭へ移動|
|{|段落毎に上へ移動|
|}|段落毎に下へ移動|
|ctrl+o|移動前に戻る|
|w|単語の先頭に進む|
|e|単語の先頭に戻る|

## 削除
|コマンド|内容|
|---|---|
|dd|行を削除|
|dw|単語を削除(カーソル先頭)|
|x|1文字削除|
|u|undo|
|ctrl+r|redo|


## 入力
|コマンド|内容|
|---|---|
|i|インサートモード|
|a|次の文字からインサートモード|
|o|改行してインサートモード|

## 検索/置換
|コマンド|内容|
|---|---|
|/serch|検索|
|n|次の検索結果へ移動|
|N|前の検索結果へ移動|
|:%s/search/replace/g|一括置換|
|:%s/search/replace/gc|確認しながら置換|

## vimの設定
```
set shell=/bin/zsh
set shiftwidth=4
set tabstop=4
set textwidth=0
set expandtab
set autoindent
set hlsearch
set clipboard=unnamed
syntax on
```

# tmux
<img width="1348" alt="image" src="https://user-images.githubusercontent.com/29517703/211590663-21947989-7357-490a-ad8f-655f11c20c0f.png">
<img width="1335" alt="image" src="https://user-images.githubusercontent.com/29517703/211590938-9d9d399e-9621-4b90-bd66-a7f8a3452c68.png">


set hlsearch
