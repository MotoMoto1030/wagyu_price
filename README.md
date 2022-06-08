# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリはネット上でコードを管理している場所のこと。
- ローカルリポジトリは管理場所が各個人のPC内部。

## プッシュとマージの違いは何でしょうか？
- プッシュはローカルリポジトリの内容をリモートリポジトリに反映させること。
- マージは作成(または変更)したブランチの内容を別のブランチに反映させること。


## コミットとプッシュの違い
- コミットはローカル内で編集した内容をGitに保存すること。
- プッシュはコミットされた内容をリモートリポジトリに反映させること。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 一目で何があったのかどういう変更がされたのか分かるように記述するのが最適。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- プルリクエストでマージをするフローは自分ではない第三者がマージをするためリモートは変更されたのに
- ローカルは変更されていない現象が起こってしまうためリモートの内容を同期させるためローカルをpullする必要がある。
- ローカルの場合はローカル内でマージを行うのでプルリクエストフローのような変更内容が食い違うことがない。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 先にマージされた内容を取り込むか、後からマージされた内容を取り込むか、両方とも取り組むよう対処する。
