# GitとGitHubについて

## ■　Gitとは
> 説明

## ■　種類
### 1、ワーキングツリー
> 説明
### 2、インデックス
> ひとまとめにしてコミットしたいファイルをとりあえず置いておくところ
### 3、ローカルリポジトリ
> 説明
### 4、リモートリポジトリ  
> 説明

## ■　branchを分ける理由
> 説明

## ■　コマンド集

* リポジトリを作成
`git init`  

* インデックスに追加(Git管理の対象にあげる)
`git add <ディレクトリ名やファイル名>`
(例) `git add test`、`git add test.md`  

* コミットする
`git commit -m <"コメント">`
(例) `git commit -m "テストです"`  

* addとcommitを同時に行う
`git commit -a <ディレクトリ名やファイル名>`
(例) `git commit -a test`、`git commit -a test.md`   

* リモートリポジトリの追加
`git remote add origin <追加したいリポジトリ>`
(例) `git remote add origin https://github.com/○○○/×××.git`  

* リモートリポジトリの削除
`git remote rm origin`  

* プッシュする
`git push -u origin master`
(2回目以降は `git push` で可能)

* ブランチを作成
`git branch <ブランチ名>`
(例) `git branch new-branch`

* ブランチの一覧を表示(＊が付いているのが現在のブランチ)
`git branch`

* addはローカルからステージにあげるコマンド
