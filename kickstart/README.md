# KickStart Guides

## Domain Registration

首先為你的網路生意或公司，挑個好名字。

以下是幾個比較知名的網域註冊商。

* [eNom](http://enomcentral.com)
* [GoDaddy](http://godaddy.com)
* [NameCheap](http://namecheap.com)

### 網域挑選原則

雖然你可能是台灣的公司，我還是建議在 domain 的選擇上，能夠儘量使用或者

* 第一順位：.com
* 第二順位：.tw

作為公司的 domain name。使用 **.com.tw** 可能不是個好主意。尤其是你的生意日後擴大時，再買回 **.com** 的使用權通常可能會花上一大筆錢。我建議你第一天就這麼作。

### 花費

* .com 約 8 - 15 USD
* .tw 約 800 - 1200 NTD
* .io 約 50 - 100 USD

## Mail & Calender

[Google Apps](https://www.google.com/a/cpanel/standard/new3) 提供 10 個使用者的免費 quota。在公司還小時，適合使用這個現成的方案讓所有成員迅速擁有專屬信箱。

### 花費

超過 10 人以上，每位使用者每年 $50 美元。

## Amazon Web Services

[Amazon Web Services](http://aws.amazon.com) 提供了不少實用服務，可以省下不少自建成本。

* [EC2](http://aws.amazon.com/ec2) 機器租賃
* [S3](http://aws.amazon.com/s3) 檔案空間
* [CloudFront](http://aws.amazon.com/cloudfront) CDN 服務
* [Route53](http://aws.amazon.com/route53) DNS Server
* [RDS](http://aws.amazon.com/rds) MySQL Server
* [SES](http://aws.amazon.com/ses) 寄信服務

### 把 DNS 換成 Route53

通常在 Google Apps 的 mail 設定完畢，確定可以寄信之後。我就會直接使用 tech@mycompany.com 的 mail 註冊 amazon web services，開通部分服務。例如把 DNS server 從網域註冊商直接搬到 Route53 上。

### 花費

DNS 花費每月應該會在 2USD 以下。其餘可以參照服務的 Pricing

## VPS / Colocation

台灣的 VPS 品質都不是很好。所以現在常見的 solution 是使用以下兩家提供東京伺服器的廠商：

* [Linode](http://linode.com)
* [EC2](http://aws.amazon.com/ec2)

### 花費

我通常會推薦下列規格起步 ：

* [Linode](http://linode.com) Linode 1536 : 59.95 USD/month
* [EC2](http://aws.amazon.com/ec2) Small : ~72 USD/month

## Sourcecode Hosting

非 [Github](http://github.com) 莫屬，沒有第二句話的選擇。公司建議使用 [Organization](https://github.com/account/organizations/new) 方式註冊。

### 花費

[Organization Bronze Plan ](https://github.com/account/organizations/new?plan=bronze) 是 25 USD/month

## Issue Tracking

使用專案管理工具，管理公司的大小事。

公司內部所有要做的事，不應該以口頭命令形式存在，而且必須有紀錄、可以被討論、有開始以及截止日期。並要能夠寄信通知與留存備份。

我個人是偏好使用 Redmine。但是架設需要花上一點時間。若你偏好現成的話，也可以使用商業的 JIRA 與 Basecamp。

Trello 是免費的工具，適合相當小型的專案內部實作。

* [Redmine](http://www.redmine.org/)
* [JIRA](http://www.atlassian.com/software/jira/overview/)
* [Basecamp](http://basecamp.com/)
* [Trello](https://trello.com/)

### 花費

* [Redmine](http://www.redmine.org/) 0 USD/month
* [JIRA](http://www.atlassian.com/software/jira/overview/) 10USD/month
* [Basecamp](http://basecamp.com/) 20USD/month
* [Trello](https://trello.com/) 0 USD/month

## File Sharing

推薦使用 Dropbox 作為團隊檔案分享工具。

參照 Dropbox bonus 可以拿的免費空間拿一拿

* <https://www.dropbox.com/account/bonus>

或者參照文章操作拿更多的免費空間

* 2011 Quest 解題攻略 <http://www.techbang.com/posts/4681>
* 2012 Quest 解題攻略 <http://www.techbang.com/posts/9370>

### 花費

* [Dropbox Upgrade](https://www.dropbox.com/upgrade) 100GB $9.99 USD/month
* [Dropbox Team](https://www.dropbox.com/teams/pricing) $750 USD/year for Team (5 user, 1000 GB per user )


## Other Tool

* [Airbrake](http://airbrakeapp.com) 監視程式碼錯誤 (for Rails)
* [Newreclic RPM](http://newrelic.com/) 監視網站效能
* [Pingdom](http://tools.pingdom.com/fpt/) 監視網站是否倒站，發簡訊通知
* [Google Analytics](http://www.google.com.tw/intl/zh-TW/analytics/) 網站流量監視
* [Passback](http://www.passpack.com/en/home/) 團隊密碼管理分享

### 花費

(TODO)

