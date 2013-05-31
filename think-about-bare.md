# 広島Git

subtitle
:	Bareリポジトリについて

author
:   @ryosms

date
:   2013/06/01

theme
:	rabbit

allotted-time
:	15m

# 自己紹介(1)

* Twitter: [@ryosms](https://twitter.com/ryosms)
* GitHub: [ryosms](https://github.com/ryosms)
* 岡山Gitユーザ会([#okagit](https://twitter.com/search/realtime?q=%23okagit&src=typd))代表
	* [http://okagit.github.io/](http://okagit.github.io/)
* 広島にはIngressやりに来ました

# 自己紹介(2)

![](./images/tweet.png){:relative_height="90" reflect_ratio='0.5'}

# お品書き

* Bareリポジトリとは
* どーやって作るの？
* どこに置けばいいの？

# Bareリポジトリとは

* 所謂「中央リポジトリ」
	* ワーキングディレクトリを持たない
	* 操作はpushで
* remote ≒ Bare
* Bare != Bear

# 作り方(1)

* 新規作成

		git init --bare

* 既存リポジトリから

		git clone --bare hoge fuga

# 作り方(2)

* ホスティングサービス(GitHub)

![](./images/github.png){:relative_width="90" reflect_ratio="0.5"}

![](./images/github2.png){:relative_width="45" reflect_ratio="0.5"}

# 置き場所(分類)

* Gitガチ勢
* ホスティングサービス活用勢
	* 課金兵士
	* 無課金兵士
* ぼっち開発者

# Gitガチ勢

* [GitLab](http://gitlab.org/)
* [gitolite](https://github.com/sitaramc/gitolite)
* [ALMinium](http://alminium.github.io/alminium/)
* [Gitblit](http://gitblit.com/)
* etc...

# ホスティングサービス

* [GitHub](https://github.com/)
* [Bitbucket](https://bitbucket.org/)
* [Google Code](https://code.google.com/intl/ja-JP/)
* [assembla](https://www.assembla.com/home)
* etc...

# ぼっち開発者

* オンラインストレージ
	* [Dropbox](https://www.dropbox.com/)
	* [SugarSync](http://www.sugarsync.jp/)
	* etc…
* ファイル共有

# で、どれがいいの？

* 1番はホスティングサービス
	* GitHubは別格
	* アカウントだけはとっとけ
* 次にオンラインストレージ
* 自前サーバーは趣味の世界


# おしまい

* ご静聴ありがとうございました

![](./images/bell6.png){:relative_height='90' reflect_ratio='0.5'}

