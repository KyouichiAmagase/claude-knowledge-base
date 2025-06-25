# コーディング規約

## JavaScript/TypeScript
### 基本ルール
- ESLint + Prettier使用
- const/let優先、var禁止
- アロー関数優先
- async/await優先

### 命名規則
- 変数・関数: camelCase
- 定数: UPPER_SNAKE_CASE
- クラス: PascalCase
- ファイル: kebab-case

### コメント
```javascript
/**
 * 関数の説明
 * @param {string} param - パラメータの説明
 * @returns {boolean} 戻り値の説明
 */
function example(param) {
  // 処理の説明
  return true;
}
```

## Python
### 基本ルール
- PEP 8準拠
- Black使用
- Type hints推奨

### 命名規則
- 変数・関数: snake_case
- クラス: PascalCase
- 定数: UPPER_SNAKE_CASE

## 共通ルール
### エラーハンドリング
- 適切な例外処理
- 意味のあるエラーメッセージ
- ログ出力

### テスト
- 単体テスト必須
- カバレッジ80%以上
- テストケース名は日本語OK