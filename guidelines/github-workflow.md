# GitHub ワークフローガイドライン

## ブランチ戦略
### ブランチ命名規則
- `main`: 本番環境
- `develop`: 開発環境
- `feature/機能名`: 新機能開発
- `bugfix/バグ名`: バグ修正
- `hotfix/修正名`: 緊急修正

## コミットメッセージ
### 形式
```
[type]: [subject]

[body (optional)]

[footer (optional)]
```

### Type一覧
- `feat`: 新機能
- `fix`: バグ修正
- `docs`: ドキュメント更新
- `style`: コードフォーマット
- `refactor`: リファクタリング
- `test`: テスト追加・修正
- `chore`: その他（依存関係更新など）

### 例
```
feat: ユーザー認証機能を追加

JWT認証を使用したログイン/ログアウト機能を実装
- ログインフォーム作成
- JWT トークン管理
- 認証状態の保持

Closes #123
```

## プルリクエスト
### テンプレート
```markdown
## 概要
変更内容の簡潔な説明

## 変更内容
- [ ] 機能A追加
- [ ] バグB修正

## テスト
- [ ] 単体テスト追加
- [ ] 手動テスト完了

## 関連Issue
Closes #番号
```