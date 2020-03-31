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

### GitHub
[GitHub](https://github.com/necocoa)

### AtCoder
[AtCoder コンテスト成績表](https://atcoder.jp/users/necocoa/history)


## 制作物
### Ruby on Rails
#### (製作途中)5秒でデートプランを提案してくれるアプリ
* フロント: Vue.js
* アプリ: Swift
* バックエンド: Ruby on Rails

[GitHub](https://github.com/quelcode-0-teamA/date-suggester-rails)

[API ガイド](https://github.com/quelcode-0-teamA/date-suggester-rails/wiki)

[実行環境 (AWS Elastic-Beanstalk)](http://datesuggestersta-env.eba-tjsexdfx.ap-northeast-1.elasticbeanstalk.com/)

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
