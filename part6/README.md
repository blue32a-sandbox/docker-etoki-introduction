## 第６部　ウェブサービス開発環境の構築例

### すべてのコンテナを起動する

```
docker compose up --detach --build
```

### すべてのコンテナとイメージとボリュームを削除する

```
docker compose down --rmi all --volumes
```
