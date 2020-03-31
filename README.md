# ポートフォリオ
## プロフィール
### 主な言語
* Ruby (Rails)
* Python

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
フロント: Vue.js
アプリ: Swift
バックエンド: Ruby on Rails

[GitHub](https://github.com/quelcode-0-teamA/date-suggester-rails)

[API ガイド](https://github.com/quelcode-0-teamA/date-suggester-rails/wiki)

[実行環境 (AWS Elastic-Beanstalk)](http://datesuggestersta-env.eba-tjsexdfx.ap-northeast-1.elasticbeanstalk.com/)
※SSL化と独自ドメインは近日中に実装します。

##### Server構成
![](https://raw.githubusercontent.com/necocoa/img-stock/master/date-suggester-app.jpg)

CircleCIからECRにビルド&プッシュ
Elastic-Beanstalkではそのイメージをプルする形のデプロイフローになっています。

####  mercariのサービスを模倣したAPIサーバー
[GitHub](https://github.com/necocoa/rails-make-api-for-mercari)

[API ガイド](https://github.com/necocoa/rails-make-api-for-mercari#api-mercari)

[実行環境 (heroku)](https://rails-mercari-api-201372.herokuapp.com/)

#### Twitterを模倣したAPIサーバー
[GitHub](https://github.com/necocoa/rails-make-api-for-userpost)

[API ガイド](https://github.com/necocoa/rails-make-api-for-userpost#api-userpost)

[実行環境 (heroku)](https://api-userpost-yn26as.herokuapp.com/)

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
