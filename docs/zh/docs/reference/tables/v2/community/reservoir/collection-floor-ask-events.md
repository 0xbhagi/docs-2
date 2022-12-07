# 合集地板价请求事件表

## **reservoir.collection\_floor\_ask\_events**

该表包含有关于每个合集（collection）请求地板价的信息记录。

查询的示例可以在这里找到：

[https://dune.com/queries/1302799/2232083](https://dune.com/queries/1302799/2232083)

[https://dune.com/queries/1302841/2232151](https://dune.com/queries/1302841/2232151)

| **列名称** | **类型**  | **说明**                                                                                                 |
|-----------------|-----------|-----------------------------------------------------------------------------------------------------------------|
| id              | bigint    | 内部事件ID                                                                                              |
| kind            | string    | 事件类型（新订单、到期、出售、取消、余额变化、批准变化、引导、重新验证、重新定价） |
| collection\_id  | string    | 合集ID                                                                                                   |
| contract        | string    | 合约地址                                                                                                |
| token\_id       | string    | 合集中的代币ID                                                                              |
| order\_id       | string    | 相关的请求ID                                                                                              |
| maker           | string    | 相关的卖方钱包地址                                                                            |
| price           | decimal   | 相关的请求价格 (原生货币)                                                                         |
| previous\_price | decimal   | 前一天的请求地板价 (原生货币)                                                                      |
| valid\_until    | bigint    | 相关的有效请求有效期                                                                              |
| source          | string    | 订单来源 (例如OpenSea)                                                                           |
| tx\_hash        | string    | 相关的交易哈希值                                                                                     |
| tx\_timestamp   | bigint    | 相关的交易时间戳                                                                                |
| created\_at     | timestamp | 记录事件的时间戳                                                                                |
