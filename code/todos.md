# OpenCoin Todos

## OpenCoin Adapter

所需技术栈：

- 前端开发
- 后端开发（PHP）
- 移动端开发

OpenCoin Adapter 主要用于对接不同的业务平台与 Router 的对接，需要针对业务需求，开发不同平台的对接。

### ToDo

- WeChat Bot
- QQ Bot
- Github WebHook
- Gitlab WebHook

## OpenCoin Token Router

所需技术栈：

- 前端开发
- 后端开发（PHP）

Open Coin Token Router 主要负责接收各适配器的分发请求，并通过 API 完成分发

### ToDo

- 转账相关功能
- 交易记录查询
- 贡献者证书生成
- 个人信息更新

## OpenCoin Shop

所需技术栈: **PHP** 

OpenCoin Shop 使用开源的 WordPress  + WooCommerce 方案构建，搭配上自主研发的 Token 支付插件，完成商户的支付功能

### 支付网关 woocommerce-erc20-payment-gateway

项目地址：https://github.com/opencoindev/woocommerce-erc20-payment-gateway

Gateway 用于在 Woocomerce 中接入 ERC20 的支付方式

#### Todo

- 交易状态查询

### 货币支持 woocommerce-custom-erc20-currencies

项目地址：https://github.com/opencoindev/woocommerce-custom-erc20-currencies

custom erc20 用于在 Woocomerce 中加入 ERC20 token 作为货币，用于社区的结算。

#### Todo

- 从 ImToken 的 Profile 中读取图标等数据

  