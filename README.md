# setup-app-practice

## 概要
COACHTECH 教材 Tutorial 9-1「環境構築ハンズオン」で作成した成果物です。
Laravel Sail と Docker を使って、Tutorial 9〜10 のハンズオンで使う開発環境を構築しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- Laravel Sail（Docker Compose）
- MySQL, phpMyAdmin


## 学んだこと
Lravel Sailを使った開発環境を正しく構築する方法について
ディレクトリを作成からブラウザでLaravelとphpMyadminが表示されるまでの方法 

## 動作確認
cd ~/laravel-practice/9-1-7_hands-on/setup-app-practice（プロジェクトディレクトリへ移動）
./vendor/bin/sail up -d（Sailを起動）
./vendor/bin/sail artisan key:generate（Lravelアプリケーションキーを生成）
http://localhost・http://localhost:8080（ブラウザで動作確認）
./vendor/bin/sail down（確認終了）
