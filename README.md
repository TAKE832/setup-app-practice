## 概要
COACHTECH 教材 Tutorial 9-1「環境構築菅ズオン」で作成した成果物です。Laravel Sail と　Docker を使って、Tutorial 9~10 のハンズオンで使う開発環境を構築しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- Laravel Sail (Docker Compose)
- MySQL, phpMyAdmin

## 学んだこと
- phpMyAdminの設定を compose.yaml の MySQL のコードの下に追加することで、ブラウザで、データベースを管理できるようになることが分かった。
- アプリケーションキーを設定することで、セッションや暗号化データなどの機密情報を保護することができると知った。

## 動作確認
- ブラウザで、(http://localhost) にアクセスして、Laravelのウェルカムページが表示されるかの確認をする。
- ブラウザで、(http://localhost:8080) にアクセスして、phpMyAdminが表示されることの確認。さらに、Laravelデータベースが作られていることも確認する。
