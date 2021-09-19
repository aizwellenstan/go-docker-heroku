## Usage

### ローカル環境を立ち上げる

下記コマンドを入力後に http://localhost:8080 で確認できます。

```
% make up
```

### Herokuにビルドする

```
# herokuログイン
% heroku container:login

# herokuアプリの作成
% heroku create -a go-heroku

# herokuリポジトリをgit登録
% heroku git:remote -a go-heroku

# herokuへデプロイ
% git push heroku master 
```

