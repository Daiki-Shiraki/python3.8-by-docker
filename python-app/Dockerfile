# ベースイメージを選択
FROM python:3.8

# ワークディレクトリを設定
WORKDIR /app

# 必要なファイルをコピー
COPY app.py /app/
COPY requirements.txt /app/

# 依存関係をインストール
RUN pip install -r requirements.txt

# アプリケーションを実行
CMD ["python", "app.py"]
