# 英検3級 文法マスター 📚

英検3級レベルの文法問題ゲームです。現在完了・過去形・受動態の3つの文法項目を楽しく学習できます。

## 🎮 機能

- **現在完了形** (have/has + 過去分詞)
- **過去形** (動詞の過去形)
- **受動態** (be + 過去分詞)

- 単元選択：現在完了（34問）／過去形（33問）／受動態（33問）／まぜこぜ（全100問）
- 出題数：5・10・20・30・50問（時間制限なし）
- 答えたあとに「完成した文」と、根拠を①②③の順に示す解説を表示

### URLパラメータ（ポータルからの直接起動）

| パラメータ | 値 | 説明 |
|---|---|---|
| `unit` | `present-perfect`（`pp` / `1`）, `past`（`2`）, `passive`（`3`）, `mix`（`all` / `0`） | 単元 |
| `count` | 1〜（単元の全問題数まで） | 問題数 |
| `start` | `0` | 自動スタートせず、選択だけ反映 |

`unit` か `count` があれば、その設定ですぐ1問目を開きます。例：`?unit=passive&count=10`、`?unit=mix&count=10`

## 🚀 デプロイ方法

### 1. GitHubリポジトリを作成

```bash
# このフォルダでGitを初期化
git init

# ファイルを追加
git add .

# コミット
git commit -m "Initial commit: 英検3級文法ゲーム"

# GitHubでリポジトリを作成後、リモートを追加
git remote add origin https://github.com/YOUR_USERNAME/eiken-grammar-game.git

# プッシュ
git branch -M main
git push -u origin main
```

### 2. Vercelでデプロイ

1. [Vercel](https://vercel.com) にアクセス
2. GitHubアカウントでログイン
3. "Add New..." → "Project" をクリック
4. 作成したリポジトリを選択
5. "Deploy" をクリック

数秒でデプロイ完了！🎉

## 📱 スクリーンショット

- スタート画面：文法カテゴリを確認してゲーム開始
- 問題画面：4択から正解を選択、詳しい解説付き
- 結果画面：スコアとカテゴリ別の正答率を表示

## 🛠 技術スタック

- HTML5
- CSS3 (アニメーション付き)
- Vanilla JavaScript
- Google Fonts (M PLUS Rounded 1c, Outfit)

## 📝 ライセンス

MIT
