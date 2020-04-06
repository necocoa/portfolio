# ポートフォリオ
## プロフィール
### 主な言語
* Ruby (Ruby on Rails)

### 利用した技術
* RDBMS (PostgreSQL, MySQL)
* RSpec (Railsテストコード)
* Docker
* CircleCI
* AWS (EC2, RDS, Lambda, EB, ECR)
* Vagrant

### GitHub
[GitHub](https://github.com/necocoa)

### Qiita
[Qiita](https://qiita.com/necocoa)

### AtCoder
[AtCoder コンテスト成績表](https://atcoder.jp/users/necocoa/history)


## 制作物
### Ruby on Rails
#### (製作途中)5秒でデートプランを提案してくれるアプリ
* フロント: Vue.js
* アプリ: Swift
* バックエンド: Ruby on Rails

サービス設計からDB構成、インフラ構成、APIサーバーのコーディングまで一気通貫で担当しました。

また、同時にPMとしてPJの進行管理も担当しました。

[GitHub](https://github.com/quelcode-0-teamA/date-suggester-rails)

[APIドキュメント](https://github.com/quelcode-0-teamA/date-suggester-rails/wiki)

[実行環境 (AWS Elastic-Beanstalk)](https://api.date-suggester.com/)

※SSL化と独自ドメインは近日中に実装します。

![](https://raw.githubusercontent.com/necocoa/img-stock/master/date-suggester-app-top.jpg)

##### Server構成
![](https://raw.githubusercontent.com/necocoa/img-stock/master/date-suggester-app.jpg)

#### デプロイフロー
1. GitHubにPush
2. CircleCIにて、テスト(RSpec & Rubocop)
3. CircleCIにて、ECRにDockerImageをBuild & Push
4. S3にECRのimage名を保存(Dockerrun.aws.json)
5. Elastic-Beanstalkのアプリバージョンを更新(S3に保存したDockerrun.aws.jsonを指定)
6. Elastic-Beanstalkのバージョンアップデートを行い、ECRからImageをPullしデプロイ完了

### プログラミング学習の流れ

  <img src="https://raw.githubusercontent.com/necocoa/img-stock/master/portfolio/program-11.jpeg" width="600px" max-width="100%">
  <img src="https://raw.githubusercontent.com/necocoa/img-stock/master/portfolio/program-12.jpeg" width="600px" max-width="100%">
  <img src="https://raw.githubusercontent.com/necocoa/img-stock/master/portfolio/program-01.jpeg" width="600px" max-width="100%">
  <img src="https://raw.githubusercontent.com/necocoa/img-stock/master/portfolio/program-02.jpeg" width="600px" max-width="100%">
  <img src="https://raw.githubusercontent.com/necocoa/img-stock/master/portfolio/program-03.jpeg" width="600px" max-width="100%">
  <img src="https://raw.githubusercontent.com/necocoa/img-stock/master/portfolio/program-04.jpeg" width="600px" max-width="100%">

### その他の制作物
####  mercariのサービスを模倣したAPIサーバー
[GitHub](https://github.com/necocoa/rails-make-api-for-mercari)

[API ガイド](https://github.com/necocoa/rails-make-api-for-mercari#api-mercari)

[実行環境 (heroku)](https://rails-mercari-api-201372.herokuapp.com/)

### Python
#### AtCoderのコンテスト情報を投稿するSlackBOT
AWS Lambda利用
[GitHub](https://github.com/necocoa/python-lambda-slack-bot)

### HTML/CSS/Sass
#### 珈琲店
[GitHub](https://github.com/necocoa/html-narita-caffee)

[実際のサイト](https://necocoa.github.io/html-narita-caffee/)

#### 家具屋
[GitHub](https://github.com/necocoa/html-furniture-store)

[実際のサイト](https://necocoa.github.io/html-furniture-store/)

### JavaScript
#### トピック投稿SlackBOT
GAS利用（Google App Script）

[GitHub](https://github.com/necocoa/gas-send-topic-to-slack)

#### 席替えアプリ
[GitHub](https://github.com/necocoa/js-change-seats)

[実際のサイト](https://necocoa.github.io/js-change-seats/)
