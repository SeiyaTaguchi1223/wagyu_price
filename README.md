# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
リモートリポジトリはネット上に配置して複数人で共有するためのリポジトリで、
ローカルリポジトリは開発者一人ひとりが使用するために自分のPC上に配置するリポジトリである。
リモートリポジトリは開発内容を共有・公開したりすることでその内容を他の人が確認できたり、作業内容を取得することができる。

## プッシュとマージの違いは何でしょうか？
マージとは異なるブランチの作業内容や変更を統合するプロセスを指し、
プッシュはローカルリポジトリで行った変更をリモートリポジトリにアップロードするプロセスのことを指す。
マージは異なるブランチの作業内容を統合するもので、
プッシュはローカルリポジトリでの変更をリモートリポジトリへ共有するもの。


## コミットとプッシュの違い
コミットは変更をローカルリポジトリに永続的に記録する操作を指し、
それぞれの変更に意味のあるメッセージを付けて説明することができる。
コミットによりファイルやコードの状態が特定の時点で確定され、バージョン管理の中で変更の履歴が残る。
プッシュはローカルリポジトリで行った変更をリモートリポジトリにアップロードするプロセスのことを指す。
コミットはローカルリポジトリ内での変更の確定と記録、
プッシュはローカルリポジトリの変更をリモートリポジトリに共有する操作である。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
履歴を見返したときにそのコミットメッセージから「どんな変更を行ったのか」が
分かるよう、一目で変更内容がわかるものにする。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
前者は直接マスター（メイン）ブランチにマージして、リモートのブランチにプッシュするだけでリモートに変更が更新されるが、
後者は、変更した内容を他の開発者に確認してもらってからメインブランチにマージされるので、
メインブランチに変更内容が統合される前にバグなどに気づくことができる。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
コンフリクトの解決には自分以外の人が書いたソースコードの内容を把握する必要があるため、
少しでも意図が読み問えない処理とぶつかってしまった場合は、
そのソースコードを書いた人と相談しながら作業を進めるようにする。
