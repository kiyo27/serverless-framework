# Serverless Framework

インストール

```
npm install -g serverless
```

サービスの作成

```
serverless create --template aws-nodejs --name my-special-service --path my-special-service
```


ローカル実行

```
serverless invoke local --function hello
```


依存パッケージをデプロイパッケージにバンドルしてくれるプラグインをインストール

```
sls plugin install -n serverless-python-requirements
```


