# Node in Docker with DevContainer

## Docker操作
### コンテナを立ち上げ
```
# ビルド
docker-compose build
# アプリの起動
docker-compose up -d
# 確認
docker-compose ps

# workdirに入る （node-app はコンテナ名）
docker exec -it node-app sh
```

### Docker終了
```
docker-compose down
```

## shで入ったら、サイト立ち上げ
```
npm run dev -- --host 0.0.0.0
```

## フォルダ構成
* ./app : 作業場

## 参考
*[Astro Docker環境作成](https://qiita.com/mayomayo/items/6e640a067b2cd6592bcf)
* [Docker Compose な開発環境にちょい足し3分で作るVSCode devcontainer](https://zenn.dev/saboyutaka/articles/9cffc8d14c6684)