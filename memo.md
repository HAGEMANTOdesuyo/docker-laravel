- Laravelプロジェクトの作成
```
composer create-project laravel/laravel .
```
- ドキュメントルートを以下に変更
```
/var/www/プロジェクト名/public
```
- apacheの再起動
コンテナ内ではsystemctlが使えない
```
service restart apache2
```
