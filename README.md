# pc-setup
markdownでの改行は行末に半角スペースを2つつける
## Lhaplus
https://forest.watch.impress.co.jp/library/software/lhaplus/
## Sakuraエディタ
https://github.com/sakura-editor/sakura/releases
### Settings
Monokai色にする  
https://keitetsu.blogspot.com/2015/06/monokai-cc.html (C/C++以外)
## Cygwin
https://cygwin.com/install.html
### 追加インストール
- vim
- openssh

### Settings
```
vi ~/.bash_profile

alias la='ls -la'
alias ll='ls -la'
```
## Git
https://git-scm.com/download/win
### 鍵の作成・設定
```
# 鍵の生成
ssh-keygen -f ~/.ssh/id_rsa_github
# configファイル
vim ~/.ssh/config
#### config ####
Host github github.com
  HostName github.com
  IdentityFile ~/.ssh/id_rsa_github
  User git
####
chmod 700 ~/.ssh/config
```

## VSCode
https://code.visualstudio.com/
### Settings
ファイルをPreviewで表示させない  
`workbench.editor.enablePreview`をfalseにする  
半角スペース表示  
`Render Whitespace`をallにする

### Plugins
- Japanese Language Pack
- Vim