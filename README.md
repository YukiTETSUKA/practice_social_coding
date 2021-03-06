# ソーシャルコーディング

## 目的
githubを用いてソーシャルコーディングを体得する．

## 作るもの
ホームページ．随時変更アリ．

## やり方
1. github(https://github.com/whitech0c0/practice_social_coding) Forkをクリック.  
(自分のgithub上にフォークされます)   

2. ローカル環境にクローンする
```sh
$ git clone https://github.com/[user_name]/practice_social_coding
```
3. ブランチを作成
```sh
$ cd practice_social_coding
$ git checkout -b [branch_name]
```
4. ファイル追加・修正・削除などしてから
```sh
$ git add [file_name]
$ git commit -m "[commit_message]"
```
5. 自分のgithubリポジトリ(forkしたやつ)にpushする
```sh
$ git push origin [branch_name]
```
6. guthubのページからPull Reauest  ボタンをクリック
 
## 注意
* 自分が作業するときは常に最新からのブランチにしよう
* 自分のgithubリポジトリも常に最新のものにしよう( remoteにupstream追加する )

### 本家から最新をもってきて自分のところも最新状態にする

1. masterブランチに切り替える
```sh
$ git checkout master
```

2. リモート先を追加する
```sh
$ git remote add upstream https://github.com/whitech0c0/practice_social_coding
```
3. 自分のローカルのmasterを最新にする
```sh
$ git pull upstream master
```
4. github側も最新にする
```sh
$ git push origin master
```

※わざと失敗するのもありだと思います

## 他の人のブランチを検証したいとき
あとで書く

## Pull Request が Merge されたあとですること
あとで書く

## 約束ごと
* 失敗を恐れない
* issueとかgithubの機能をいろいろ使ってみる
* わからないことは積極的に調べる＆聞く

このREADMEも間違っている＆わかりずらい箇所があると思うのでみんなで修正していきましょう．

## 参考資料
* [いつやるの？git入門](http://www.slideshare.net/matsukaz/git-17499005)
* [こわくないgit](http://www.slideshare.net/kotas/git-15276118)
* [デザイナー向けGit解説](http://uniq.heteml.jp/blog/2012/06/22/%E3%83%87%E3%82%B6%E3%82%A4%E3%83%8A%E3%83%BC%E5%90%91%E3%81%91git%E8%A7%A3%E8%AA%AC-%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%81%A8%E5%90%8C%E3%81%98%E3%83%96%E3%83%A9%E3%83%B3%E3%83%81/)
* [Git初心者に捧ぐ！Gitの「これなんで？」を解説します。](http://kray.jp/blog/git-why-explanation/)
