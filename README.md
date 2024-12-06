# CRMアプリケーション

## 概要
Vue3とLaravel11を使用したCRMシステムです。
Inertia.jsを使用してSPA（シングルページアプリケーション）として設計します。

## 主要機能
1. 顧客管理
   - 顧客の基本情報
   - 購入履歴
   - 商品情報の追跡
2. 商品管理
   - 商品カタログ
   - 商品詳細情報
   - 在庫管理

## 技術スタック
- フロントエンド：Vue3
- バックエンド：Laravel11
- データベース：MySQL
- 開発環境：Docker


## アプリケーションアーキテクチャ
1. フロントエンド（Vue3 + Inertia）
   - コンポーネント設計
   - ルーティング
   - 状態管理

2. バックエンド（Laravel11）
   - APIエンドポイント
   - DB設計
   - 認証・認可機能

## 開発環境構築
1. リポジトリをクローン
   ```
   git clone git@github.com:Izumi-cmd/CRM.git
   ```

2. Dockerコンテナを起動
   ```
   docker-compose up -d --build
   ```

3. マイグレーションの実行
   ```
   docker-compose exec -it php bash php artisan migrate
   ```

4. ブラウザにアクセス
   ```
   http://localhost:5173
   ```
