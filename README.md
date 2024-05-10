# DNS-Unlock
  DNS服务器方案即将取消，请大家更换DNS地址。
  目前所有dns解析通过 adguard DNS 和 CLoudflare Zero Trust 提供，但是依旧需要代理服务器提供解锁服务。（解决了一部分部署DNS服务器的费用）


[https://dns.afosne.icu/dns-query](https://dns.afosne.icu/dns-query)正常<br/>
[https://cdns.afosne.icu/dns-query](https://cdns.afosne.icu/dns-query)部署中<br/>
[https://adns.afosne.icu/dns-query](https://adns.afosne.icu/dns-query)部署中<br/>

## 测试是否正确连接
  连接后访问网址[afosne.afosne](https://afosne.afosne/)若出现“此站点的连接不安全afosne.afosne 使用不受支持的协议。ERR_SSL_VERSION_OR_CIPHER_MISMATCH”则成功连接。若出现"无法访问此网站afosne.afosne 意外终止了连接。"则请尝试访问[browserleaks](https://browserleaks.com/dns)来测试你的dnsisp。{[dns](https://dns.afosne.icu/dns-query)的isp为Cloudlfare，[cdns](https://cdns.afosne.icu/dns-query)的isp为NetActuate，[adns](https://adns.afosne.icu/dns-query)的isp为Datacamp Limited和Cdn77 LAX。}，若不是则与dns服务器的连接出现故障。

## 使用教程

[不会使用，点击这里](/tutorial.md)


## 目前该服务已经提供的加速服务有
- [x] Netflix 新加坡
- [x] disneyplus.com 新加坡
- [x] 谷歌翻译
- [x] OP.GG
## Other

由于本人时间有限，后续解锁服务有需求请提交Issues

由于本项目部署于香港地区，Dns查询延迟稍微有点高，且有部分地址只能通过ip访问该DNS（域名已被gfw识别且封禁此条请忽略），目前准备通过隧道中转以降低延迟。

目前项目预计增加不同地区的DNS服务器以解锁更多地区的流媒体或其他平台

## 如何赞助

公益不宜，请大家多多支持,如有疑问请联系[7920a9c2@gmail.com](mailto:7920a9c2@gmail.com) 

![爱发电](/img/afd.jpg)

