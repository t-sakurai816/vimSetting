# vimSetting

プラグインを使わないでvimを快適に使う。  
おすすめの設定があれば教えて下さい

## vimrcの適用

次のコマンドで本体に`.vimrc`を適用します

```bash
curl https://raw.githubusercontent.com/t-sakurai816/vimSetting/main/vimrc > ~/.vimrc
mkdir -p ~/.vim/colors
curl https://raw.githubusercontent.com/t-sakurai816/vimSetting/main/molokai.vim >> ~/.vim/colors/molokai.vim
```

## カラースキーム `molokai` のインストール

```
$ mkdir ~/.vim
$ cd ~/.vim
$ mkdir colors

$ git clone https://github.com/tomasr/molokai
$ mv molokai/colors/molokai.vim ~/.vim/colors/
```
