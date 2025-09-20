# psql-sandbox
## 使用方法
```sh
# 起動
docker-compose up -d

# psqlで接続
docker-compose exec postgres psql -U testuser -d testdb

# 終了時にボリューム含めて完全削除
docker-compose down -v
```
