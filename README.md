# 遊戯王

## 環境構築

```bash
python -m venv yugienv
# 仮想環境有効化。bash/zshの場合は以下
source yugienv/bin/activate
pip install -r requirements.txt
```

## 他PCから開く

`ip a` でIPアドレス確認。
`jupyter notebook --ip=* --no-browser` でサーバーを起動。
コンソールに表示されたアドレスの、127.0.0.1を読み替えてアクセスする。

## データ

こちらから頂いた。
<https://www.kaggle.com/tathor/yugioh-trading-cards-dataset>
