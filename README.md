## 環境構築
### クローン
```
git clone git@github.com:Rihitonnnu/Laravel_test_db.git
```

## プロジェクトセットアップ
### ビルドとコンテナ起動
```
docker compose up -d
```

### envファイルコピー
```
cp .env.example .env
```

### コンテナに入る
```
docker compose exec laravel bash
```

### Composerインストール
```
composer install
```

### 認証キー作成
```
php artisan key:generate
```
