
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


## Mail & Calender

[Google Apps](https://www.google.com/a/cpanel/standard/new3) 提供 10 個使用者的免費 quota。在公司還小時，適合使用這個現成的方案讓所有成員迅速擁有專屬信箱。

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

