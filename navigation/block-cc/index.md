# 蜜蜂查



![](2c9ef8189de243fd290c8bec257942d.jpg)

蜜蜂查mifengcha.com是区块链产业信息服务平台,提供数字货币行情,数据,项目库,资讯等一站式服务,追求更及时、更准确的行情数据,致力为区块链爱好者和数字货币投资者提供最权威最流畅的产品和服务

蜜蜂查提供了丰富的API接口供开发者使用，接入简单，使用方便。第三方应用开发者可以借助该服务，快速构建稳定高效的数字货币行情系统，为实时业务和产品运营提供技术支持。

如需使用蜜蜂查API，请先登录账号，完成API Key的申请，再根据本文档详情进行开发。 如果您还没有API密钥，请[点击注册](https://data.mifengcha.com/register)。

您可以通过以下方式在REST API调用中提供API密钥：

1. 首选方法：通过名为`X-API-KEY`的自定义请求头
2. 便捷方法：通过名为`api_key` 的查询字符串参数

在Websocket API中只能通过名为api_key 的查询字符串参数提供API密钥

蜜蜂查API为用户提供两种接口，您可根据自己的使用场景和偏好来选择适合的方式进行行情查询。

##### REST API

REST，即Representational State Transfer的缩写，是目前较为流行的基于HTTP的一种通信机制，每一个URL代表一种资源。

##### WebSocket API

WebSocket是HTML5一种新的协议（Protocol）。它实现了客户端与服务器全双工通信，通过一次简单的握手就可以建立客户端和服务器连接，服务器可以根据业务规则主动推送信息给客户端。

您可以自行比较使用data.block.cc和data.mifengcha.com两个域名的延迟情况，选择延迟低的进行使用。其中，data.mifengcha.com域名对中国大陆的用户做了一定的链路延迟优化。
