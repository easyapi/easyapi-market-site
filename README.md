EasyAPI服务站点
--------

EasyAPI服务站点，是一个纯静态项目工程。

## 开发建议
- 公共样式表、脚步、图片放到easyapi-static项目中
- 每个站点，根据需要独立建立静态文件，css，images，js（命名参照jhipster框架，Bootstrap等）
- 样式表使用less语法编写

## 命名规范

- 使用kebab-case（短横线）命名方式
- 图片资源采用的命名规范
- CSS命名规范
- 常规名称命名方案，参见EasyAPI中英文翻译

##  站点介绍：
| 工程名称             | 描述                      |  URL                      | 
| ------------------  | ------------------------ |  ------------------------    |
| easyapi-ad          |  EasyAPI广告管家           |  https://ad.easyapi.com    |
| easyapi-clockin     |  EasyAPI签到打卡           |  https://clockin.easyapi.com    | 
| easyapi-convert     |  EasyAPI文档转换           |  https://convert.easyapi.com    |
| easyapi-feedback    |  EasyAPI意见反馈           |  https://feedback.easyapi.com    |
| easyapi-invoice     |  EasyAPI发票查验           |  https://invoice.easyapi.com    |
| easyapi-ip          |  EasyAPI IP服务            | https://ip.easyapi.com    |
| easyapi-jiayouka    |  EasyAPI加油卡充值         |  https://jiayouka.easyapi.com    |
| easyapi-lottery     |  EasyAPI抽奖活动           |  https://lottery.easyapi.com    |
| easyapi-mobile      |  EasyAPI手机话费流量       |  https://mobile.easyapi.com    |
| easyapi-news        |  EasyAPI新闻资讯           |  https://news.easyapi.com    |
| easyapi-parse       |  EasyAPI网页解析           |  https://parse.easyapi.com    |
| easyapi-poster      |  EasyAPI二维码海报         |  https://poster.easyapi.com    |
| easyapi-preview     |  EasyAPI文档预览           |  https://preview.easyapi.com    |
| easyapi-qrcode      |  EasyAPI二维码服务         |  https://qrcode.easyapi.com    |
| easyapi-shop        |  EasyAPI微商城             | https://shop.easyapi.com    |
| easyapi-sms         |  EasyAPI短信服务           | https://sms.easyapi.com    |
| easyapi-update      |  EasyAPI应用检查更新       |  https://update.easyapi.com    |
| easyapi-weather     |  EasyAPI天气预报           |  https://weather.easyapi.com    |
| easyapi-withdraw    |  EasyAPI快速提现           |  https://withdraw.easyapi.com    |
| easyapi-yuyin       |  EasyAPI语音服务           |  https://yuyin.easyapi.com    |

    
## 常见问题
	
**1. 样式图片等无法访问，访问本地静态资源**

    请单独运行easyapi-static项目(https://github.com/easyapi/easyapi-static)，端口使用80，访问地址http://localhost。
    使用SwitchHosts，设置127.0.0.1 static.easyapi.com。
