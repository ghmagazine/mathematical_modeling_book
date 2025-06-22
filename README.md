# mathematical_modeling_book


『ビジネス課題を解決する技術〜数理モデルの力を引き出す3ステップフレームワーク』のサンプルコードです。

## 書籍情報
著者：森下光之助<br>
定価：3,300円（本体3,000円＋税10%）<br>
発売日：2025年6月27日<br>
頁数：320ページ<br>
ISBN：978-4-297-14992-5

## 出版社サポートサイト

https://gihyo.jp/book/2025/978-4-297-14992-5

## 動作環境とセットアップ手順

Pythonのバージョンは3.12.9を利用しています。


1. リポジトリのクローン
```bash
git clone https://github.com/ghmagazine/mathematical_modeling_book.git
cd mathematical_modeling_book
```

2. 仮想環境の作成と有効化

```bash
python -m venv .venv
source .venv/bin/activate
```

3. 依存パッケージのインストール
```bash
pip install -r requirements.txt
```

4. Jupyter labの起動
```bash
jupyter lab
```

## その他の注意点
### グラフの日本語フォント

グラフの日本語フォントとしてNoto Sans Japaneseを指定しています。
必要に応じて、以下サイトからフォントをダウンロードして、インストールして下さい。
https://fonts.google.com/noto/specimen/Noto+Sans+JP

または、`setting/visualization.json`内のフォントを変更して下さい。