# Laravel製オリジナルCMS

このリポジトリは、Laravelを使用して開発したオリジナルのCMS（コンテンツ管理システム）です。  
WordPressのような投稿管理機能をベースに、独自の管理画面やフォーム機能なども実装しています。

## 🚀 主な機能

- 投稿・固定ページの管理機能
- カテゴリ（階層あり）・タグ（人気順ランキング付き）機能
- お問い合わせフォーム（確認画面・完了画面あり、DB保存対応）
- メディアアップロード・管理機能
- 管理者権限によるアカウント管理（複数ユーザー対応）
- Laravel標準のバリデーション・認証機能を活用

## 🛠 使用技術

- Laravel 10
- PHP 8.2
- MySQL
- Docker（Laravel Sailをベース）
- Bladeテンプレート / Vue.js（必要に応じて）
- GitHubによるバージョン管理

## ⚙️ セットアップ手順

```bash
git clone https://github.com/chehshs/laravel-cms-portfolio.git
cd laravel-cms-portfolio
# Laravel SailやDocker環境に応じたセットアップを記載
cp .env.example .env
composer install
php artisan key:generate
# など
```

## 📚 補足
投稿に紐づけられるカテゴリは単一選択、タグは複数選択対応です。
お問い合わせフォームの項目は管理画面から選択可能な仕組みです。
今後、記事へのいいね機能やコメント機能の追加も検討しています。

## 💬 ライセンス・問い合わせ
MITライセンスに基づき自由にご利用いただけます。
開発や導入に関するご質問があれば、お気軽にご連絡ください。
