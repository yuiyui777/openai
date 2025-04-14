# GPT記事生成アプリ

StreamlitとOpenAI APIを使用した記事生成アプリケーションです。

## セットアップ手順

1. リポジトリをクローン
```bash
git clone [リポジトリのURL]
cd [リポジトリ名]
```

2. 必要なパッケージをインストール
```bash
pip install -r requirements.txt
```

3. 環境変数の設定
`.env`ファイルを作成し、以下の内容を記述：
```
OPENAI_API_KEY=あなたのAPIキー
```

4. アプリケーションの実行
```bash
streamlit run Untitled.ipynb
```

## 注意事項
- `.env`ファイルには機密情報が含まれているため、GitHubにアップロードしないでください。
- APIキーは安全に管理してください。 