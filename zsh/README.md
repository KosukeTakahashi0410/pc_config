# ZSHの設定について
## Install Prezto
拡張としてまずはPreztoを入れる  
(Prezto)[https://github.com/sorin-ionescu/prezto]  
基本的にはGithubに記載されている内容に沿って実行すれば問題ないはず  
おすすめのthemeは**sorin**  
ディレクトリが短縮して表示されるので、とても見やすい  

## Prezto config
Prezto自体の設定をする  
Git（現在のブランチ名を表示してくれたりする）と自動補完機能が欲しいので下記を  
> zstyle ':prezto:load' pmodule \

の下、promptの上に追記する
> 'git' \  
'autosuggestions' \  

## ZSH config
Preztoを導入すると**.zshrc**ファイルが作成されているので、こちらに追記を行う。
zshrc.txtに記載している内容を
> Customize to your needs...
と記載のある行の下に記載していく  
各内容についてはコメントを見ること  
また、pecoについてはtxtファイルに記載されているQiitaを参照、brewによってインストールを行って対応すること  