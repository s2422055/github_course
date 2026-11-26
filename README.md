# github-practice-sample

GitHub使い方講座で使う、練習用の小さなリポジトリです。

## ファイル構成
- `src/hello.py` : あいさつを表示するプログラム
- `src/calculator.py` : 足し算・引き算をするプログラム
- `.env.example` : 秘密情報の置き方の見本（本物の `.env` は push しない）
- `.gitignore` : Gitに入れないファイルの一覧
- `PRACTICE.md` : 練習の手順

## 動かし方
```
python src/hello.py
python src/calculator.py
```

## ブランチ
| ブランチ | 用途 |
| --- | --- |
| main | 完成した状態（直接作業しない） |
| feature-greeting | あいさつ変更。mainへマージ済み（Git Graphで線が見える） |
| feature-multiply | 掛け算の追加。Pull Request練習用（未マージ） |
| conflict-a / conflict-b | コンフリクト練習用（同じ行を別々に変更） |
