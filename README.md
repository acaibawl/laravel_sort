## プロジェクト作成
```composer create-project --prefer-dist "laravel/laravel=8.*" laravel_sort```

## 動作確認
```php artisan serve --port=8080```

## 開発時ストレージ
database.sqliteをdatabase直下に配置  
.envファイルに```DB_CONNECTION=sqlite```を記載してDB関連の行をコメントアウト
