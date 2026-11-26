# 練習の手順

## 練習1: Git Graphを見る
1. VSCodeでこのフォルダを開き、Git Graphを開く
2. 丸（commit）と線（ブランチ）を確認する。feature-greetingがmainに合体している

## 練習2: ブランチを作って変更する
1. mainで「Create Branch」（またはgit switch -c my-work）
2. src/hello.py の名前を自分の名前に変える
3. commit → push

## 練習3: Pull Request
1. feature-multiply を push して、GitHubでPull Requestを作る
2. タイトルと説明を書き、レビューしてマージする

## 練習4: コンフリクト
1. conflict-a をチェックアウトする
2. conflict-b をマージする（git merge conflict-b）
3. src/hello.py に印が出るので、残す内容を選んで commit する
