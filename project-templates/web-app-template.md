# Webアプリケーションテンプレート

## 基本構成
```
my-web-app/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   ├── styles/
│   └── index.js
├── tests/
├── docs/
├── package.json
├── README.md
└── .gitignore
```

## 必須ファイル
### package.json
```json
{
  "name": "my-web-app",
  "version": "1.0.0",
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "jest",
    "lint": "eslint src/"
  },
  "dependencies": {
    "react": "^18.0.0",
    "react-dom": "^18.0.0"
  },
  "devDependencies": {
    "eslint": "^8.0.0",
    "prettier": "^2.0.0",
    "jest": "^28.0.0"
  }
}
```

### README.md構成
1. プロジェクト概要
2. セットアップ手順
3. 使用方法
4. API仕様
5. 開発・貢献ガイド
6. ライセンス