# 请求表

## **reservoir.asks**

该表包含有关于每个挂单的信息记录.

查询的示例可以在这里找到：

[https://dune.com/queries/1302885/2232229](https://dune.com/queries/1302885/2232229)

[https://dune.com/queries/1302904/2232257](https://dune.com/queries/1302904/2232257)

| **列名称**     | **类型**  | **说明**                              |
|---------------------|-----------|----------------------------------------------|
| id                  | string    | 内部订单ID                            |
| kind                | string    | 协议名称 (例如Seaport)                 |
| status              | string    | 订单状态 (有效的，无效的)              |
| contract            | string    | 合约地址                             |
| token\_id           | string    | 合集中的代币ID            |
| maker               | string    | 卖方的钱包地址                         |
| taker               | string    | 买方的钱包地址                        |
| price               | decimal   | 当前的价格 (原生货币)          |
| start\_price        | bigint    | 挂单的初始价格 (用于荷兰拍卖)     |
| end\_price          | bigint    | 挂单的结束价格 (用于荷兰拍卖)       |
| currency\_address   | string    | 货币地址                             |
| currency\_symbol    | string    | 货币代号                              |
| currency\_price     | decimal   | 货币价格                               |
| dynamic             | boolean   | 是否是荷兰拍卖                            |
| quantity            | bigint    | 已挂单的代币数量              |
| quantity\_filled    | bigint    | 已执行的代币数量             |
| quantity\_remaining | bigint    | 剩余的代币数量                   |
| valid\_from         | bigint    | 挂单开始时间                          |
| valid\_until        | bigint    | 挂单结束时间                             |
| nonce               | string    | 卖方的nonce值                 |
| source              | string    | 挂单的来源 (例如OpenSea)      |
| fee\_bps            | bigint    | 挂单费用                                  |
| expiration          | bigint    | 相关的交易哈希值                  |
| raw\_data           | string    | 原始订单数据（每个来源的格式会有所不同） |
| created\_at         | timestamp | 创建挂单的时间戳            |
| updated\_at         | timestamp | 更新挂单的时间戳            |
