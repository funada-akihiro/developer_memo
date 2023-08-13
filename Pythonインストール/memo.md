# homebrewを使ったPythonのインストール方法
※今回は python@3.8を例に実施する

## インストール
brew install python@3.8

## インストール場所を確認
```
% which python3.8
/opt/homebrew/bin/python3.8
```

## コマンド登録(/usr/local/bin)
```
% ln -s /opt/homebrew/bin/python3.8 /usr/local/bin/python3.8
```

## 起動確認
```
% python3.8
```
