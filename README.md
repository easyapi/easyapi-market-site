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
| 工程名称             | 描述                      | 
| ------------------- | -------------------------  |
| easyapi-ad          |  EasyAPI广告管家           |
| easyapi-clockin     |  EasyAPI签到打卡           |
| easyapi-convert     |  EasyAPI文档转换           |
| easyapi-feedback    |  EasyAPI意见反馈           |
| easyapi-invoice     |  EasyAPI发票查验           |
| easyapi-ip          |  EasyAPI IP服务            |
| easyapi-jiayouka    |  EasyAPI加油卡充值         |
| easyapi-lottery     |  EasyAPI抽奖活动           |
| easyapi-mobile      |  EasyAPI手机话费流量       |
| easyapi-news        |  EasyAPI新闻资讯           |
| easyapi-parse       |  EasyAPI网页解析           |
| easyapi-poster      |  EasyAPI二维码海报         |
| easyapi-preview     |  EasyAPI文档预览           |
| easyapi-qrcode      |  EasyAPI二维码服务         |
| easyapi-shop        |  EasyAPI微商城             |
| easyapi-sms         |  EasyAPI短信服务           |
| easyapi-update      |  EasyAPI应用检查更新       |
| easyapi-weather     |  EasyAPI天气预报           |
| easyapi-withdraw    |  EasyAPI快速提现           |
| easyapi-yuyin       |  EasyAPI语音服务           |

    
## 常见问题
	
**1. 样式图片等无法访问，访问本地静态资源**

    请单独运行easyapi-static项目(https://code.aliyun.com/easyapi/easyapi-static)，端口使用80，访问地址http://localhost。
    使用SwitchHosts，设置127.0.0.1 static.easyapi.com。
