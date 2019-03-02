# data-scienece-starter-jupyter-notebook

## Initialization


1. docker & docker-composeをインストール

Docker のインストール — Docker-docs-ja 17.06.Beta ドキュメント
http://docs.docker.jp/engine/installation/

Docker Compose のインストール — Docker-docs-ja 17.06.Beta ドキュメント
http://docs.docker.jp/compose/install.html



2. 立ち上げコマンド



```
docker-compose up -d
```

⬆︎で、コンテナを立ち上げる


```
ct=jupyter
docker logs $ct
```


⬆︎で、tokenを確認する

例:
```
Copy/paste this URL into your browser when you connect for the first time,
to login with a token:
http://(c33e967ee0f1 or 127.0.0.1):8888/?token=dffe7c6b3883385cf4adc9f285054b5d31b5f68fd8075164
```

⬆のtoken=以下がloginに必要なパスワード


http://localhost:8899に、アクセスして、パスワードを入力する
