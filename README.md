# Enterprise Systems Portal

WealthAI Enterprise Systemsの統合ポータル画面

## 機能

- 各システムへの統一アクセスポイント
- システム状態の可視化
- レスポンシブデザイン対応

## システム一覧

- **WealthAI CRM** (Port 8000) - 顧客管理システム
- **ProductMaster** (Port 8001) - 商品情報管理システム  
- **AIChat** (Port 8002) - AI対話システム
- **Database** (Port 8006) - データベース管理
- **LogAPI** (Port 8005) - システムログ監視

## デプロイ

```bash
# Nginxドキュメントルートにコピー
sudo cp index.html /var/www/html/
```

## 技術仕様

- **フレームワーク**: Bootstrap 5
- **アイコン**: Font Awesome 6
- **レスポンシブ**: モバイル対応
- **バージョン**: v1.0.0
