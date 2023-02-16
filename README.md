# venvの作り方

```
python3 -m venv venv
```
２つ目のvenvがフォルダ名を表す

## .gitignore
.gitignoreのファイルを作成し，その中にvenvを追加する

##　venvの起動
```
source venv/bin/activate.fish
```
抜けるとき
```
deactivate
```
何が入ってるかを探し書き出す
```
pip freeze > requirements.py
```

## requirements.txtをいんすトール
```
pip install -r requirements.txt
```