# transformer-riiid
Kaggleにアップした[transformer入門（日本語）](https://www.kaggle.com/tomokiyoshida/transformer/)のバックアップ

Transformerの説明はこちら: [図で理解するTransformer](https://qiita.com/birdwatcher/items/b3e4428f63f708db37b7)

## 1. データセットの準備
### 1.1 データセットのダウンロード
[Kaggle](https://www.kaggle.com/competitions/riiid-test-answer-prediction/data)からデータセットをダウンロード
### 1.2 データセットを追加
以下の構造になるようにデータセットを追加
```
.
├── data
│   ├── example_sample_submission.csv
│   ├── example_test.csv
│   ├── lectures.csv
│   ├── questions.csv
│   ├── riiideducation
│   │   ├── __init__.py
│   │   └── competition.cpython-37m-x86_64-linux-gnu.so
│   └── train.csv
```
## 2. 実行方法
### 2.1 Ryeのインストール
```bash
brew install rye
```
### 2.2 依存関係のインストール
```bash
rye sync
```
### 2.3 仮想環境の実行
```bash
source .venv/bin/activate
```
## 3. 終了方法
```bash
deactivate
```