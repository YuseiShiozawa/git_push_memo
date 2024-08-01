# git_push_memo
ブランチを切ってpushするまでの流れ

* 目的のリポジトリをクローン
```bash
$ git clone https://...
```

* branchを切る
```bash
$ git switch -c Newbranch

* リポジトリに変更を加えたら
```bash
$ git add -A
$ git commit -m "initial commit"
$ git push --set-upstream origin Newbranch

 * ここでアカウント名を聞かれるので自分のアカウント名を入力

 * 次にパスワードを聞かれるのでGitHubにログインし, プロフィールアイコンから[Settings] -> [Developer settings] -> [Personal access tokens] -> [Generate new token] の順にクリック
 
 * repoにチェックマークを入れて[Generate token]をクリック, その後表示されるパスワードをコピー
  * 念の為どこかに保存すること

 * ターミナルに戻りパスワードをペースト


