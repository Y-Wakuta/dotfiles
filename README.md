# README

## 対応OS

ubuntu 18.04

* ubuntu 16.04も出来なくは無いですが、`install.sh`の中の`golang`をそのまま入れると下記のサイトに書いてある問題が発生するため、先にgolangをインストールしてください。powerline-goを入れるためにgoは必須です。

[今日からGoをはじめる人に伝えたい$GOPATHではまった話](https://www.slideshare.net/ohashiyuta/gogopath)

## install手順

* dockerコンテナ内で行う際はGUI周りのpackage等のinstall項目を取り除く必要がある

1. install.shの実行

```sh
./dotfiles/install.sh
```

1. default shellの変更

```
chsh -s `which zsh` $USER
```

## 注意

.XModmapは適用する際は内容を確認してからにしてください。
