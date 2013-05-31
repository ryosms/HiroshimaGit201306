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
* 広島まで来た理由
	* Ingressだよ言わせんな恥ずかしい

# 自己紹介(2)

![](./images/tweet.png){:relative_width="70" reflect_ratio='0.5'}

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

	* sharedオプションとかもあるけど

# 作り方(2)

* ホスティングサービス
	* 例）GitHub

![](./images/github.png){:relative_width="90" reflect_ratio="0.5"}

![](./images/github2.png){:relative_width="60" reflect_ratio="0.5"}

# おしまい

* ご静聴ありがとうございました

![](./images/bell6.png){:relative_height='90' reflect_ratio='0.5'}

