# pc-setup
markdownでの改行は行末に半角スペースを2つつける
## Google Chrome
https://www.google.com/intl/ja/chrome/
## Lhaplus
https://forest.watch.impress.co.jp/library/software/lhaplus/
## Clibor
https://forest.watch.impress.co.jp/library/software/clibor/
## Google日本語入力
https://www.google.co.jp/ime/
### Settings
[設定ファイル](./googleime)
## WinShot
https://forest.watch.impress.co.jp/library/software/winshot/
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
## Slack
https://slack.com/intl/ja-jp/downloads/windows
## Google Chrome Canary
https://www.google.com/intl/ja/chrome/canary/
## FireFox
https://www.mozilla.org/ja/firefox/
## Zoom
https://zoom.us/download
## WinSCP
https://forest.watch.impress.co.jp/library/software/winscp/