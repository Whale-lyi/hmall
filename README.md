# 黑马商城

笔记链接: https://b11et3un53m.feishu.cn/wiki/R4Sdwvo8Si4kilkSKfscgQX0niB

为了学习微服务，采用 Spring Cloud 微服务架构，拆分为以下几个模块

- cart-service
  - 购物车服务
- item-service
  - 商品服务
- pay-service
  - 付款服务
- trade-service
  - 订单服务
- user-service
  - 用户服务
- hm-api
  - OpenFeign调用接口
- hm-gateway
  - API网关
- hm-common
  - 通用模块

采用的微服务组件包括

- NACOS
  - 服务的发现与注册
  - 配置管理
- OpenFeign
  - 服务间调用
- Spring Cloud LoadBalancer
  - 负载均衡
- Spring Cloud Gateway
  - 网关
