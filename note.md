mysql -uepusdt -pPJA2rheBfSmN4MsL -h127.0.0.1 epusdt < v0.0.1.sql 

go build -o /www/wwwroot/usdt.pimeyesbot.com/epusdt/src/appstart
go build -o /www/wwwroot/usdt.pimeyesbot.com/epusdt/src/appstart -buildvcs=false

cd /www/wwwroot/usdt.pimeyesbot.com/epusdt/src
appstart http start 

ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY 'PJA2rheBfSmN4MsL';
mysql -uroot -pPJA2rheBfSmN4MsL -h198.74.117.171
mysql -uroot -pPJA2rheBfSmN4MsL -h74.48.86.124

redis-cli -h 198.74.112.31 -p 6379 -a P9tb6Bw2ocYQpR
redis-cli -h 148.135.90.111 -p 6379 -a P9tb6Bw2ocYQpR

https://usdt.pimeyesbot.com/pay/checkout-counter/202307301690741490800663

https://usdt.pimeyesbot.com/pay/check-status/202307301690741490800663




 task_service.go 2024-08-06 10:57:37 ---------------------- 
  resp : {"contractMap":{},"tokenInfo":{"tokenId":"TR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t","tokenAbbr":"USDT","tokenName":"Tether USD","tokenDecimal":6,"tokenCanShow":1,"tokenType":"trc20","tokenLogo":"https://static.tronscan.org/production/logo/usdtlogo.png","tokenLevel":"2","issuerAddr":"THPvaUhoh2Qn2y9THCZML3H815hhFhn5YC","vip":true},"page_size":0,"code":200,"data":[]}
