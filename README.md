#  「困り感」のある子どもを支援するサービス Tech Teach! 
「困り感のある子ども」×「先生」がマッチングするサービスです！

![top](https://user-images.githubusercontent.com/72676124/149638885-35b91fc9-63a8-4706-940e-49a73960c48e.jpg)

URL: https://www.tech-teach.net

## 作成背景
「困り感」のある子どもに適切な支援を！

私が現役教員として切実に感じている問題です。公教育ではカバーしきれない問題を、ITの力で解決したいと考えました。

公的な教育では、先生をえらぶことができません。「困り感」のある子どもは、相性の合わない先生と勉強することで、不必要な劣等感を抱いたり、自信を無くしたりすることがあります。

それぞれの子どもにマッチする先生を見つけて、素晴らしい個性を伸ばしていきましょう！

*「困り感」→ 不登校や発達障害（ADHD、自閉症、学習障害）などで困っている状態

* ソースコードはGithubで、バックエンドとフロントエンド分けて管理しています。
  * フロントエンド：https://github.com/AGO523/react-app-frontend
  * バックエンド：https://github.com/AGO523/rails-react-app-backend

## ER図
![image](https://user-images.githubusercontent.com/72676124/149405613-7a2efe01-fb78-431e-833f-3a55cbab2edd.png)

## インフラ構成図
![aws構成図](https://user-images.githubusercontent.com/72676124/149649785-5a0c4312-f097-46a7-a524-4fadfd7b6bc7.jpg)

## 使用技術
* フロントエンド
  * HTML/CSS
  * TypeScript
  * React
  * Material-UI

* バックエンド
  * Mysql 8.0
  * Ruby 3.0.2
  * Rails 6.1.4 ( API モード)
  * Rspec
  * Rubocop
  
* インフラ・開発環境
  * フロントエンド
    * AWS ( ACM / Route53 / S3 / CloudFront )
  * バックエンド
    * AWS ( EC2 / RDS / VPC / ALB / ACM / Route53 ) 
  * Docker/Docker-compose
  <!-- * CircleCI  -->
