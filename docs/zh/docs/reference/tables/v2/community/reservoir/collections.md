# 合集表

## **reservoir.collections**

该表包含有关于每个NFT合集（collection）的信息记录。

查询的示例可以在这里找到：

[https://dune.com/queries/1302781/2232054](https://dune.com/queries/1302781/2232054)

[https://dune.com/queries/1302788/2232065](https://dune.com/queries/1302788/2232065)

| **列名称**            | **类型**  | **说明**                             |
|----------------------------|-----------|---------------------------------------------|
| id                         | string    | 内部合集ID                      |
| slug                       | string    | 合集简称                             |
| name                       | string    | 合集名称                             |
| description                | string    | 合集说明                      |
| token\_count               | bigint    | 合集中的代币ID           |
| contract                   | string    | 合约地址                            |
| day1\_rank                 | bigint    | 前1日的排名                 |
| day7\_rank                 | bigint    | 前7日的排名              |
| day30\_rank                | bigint    | 前30日的排名             |
| all\_time\_rank            | bigint    | 全时段排名                            |
| day1\_volume               | decimal   | 前1日的交易量            |
| day7\_volume               | decimal   | 前7日的交易量         |
| day30\_volume              | decimal   | 前30日的交易量        |
| all\_time\_volume          | decimal   | 全时段交易量                       |
| day1\_volume\_change       | double    | 前1日的交易量变化     |
| day7\_volume\_change       | double    | 前7日的交易量变化  |
| day30\_volume\_change      | double    | 前30日的交易量变化 |
| floor\ask\_value           | decimal   | 全时段地板价 (原生货币)  |
| day1\_floor\_sale\_value   | decimal   | 前1日的地板价       |
| day7\_floor\_sale\_value   | decimal   | 前7日的地板价                |
| day30\_floor\_sale\_value  | decimal   | 前30日的地板价                |
| day1\_floor\_sale\_change  | double    | 前1日的地板价变化   |
| day7\_floor\_sale\_change  | double    | 前7日的地板价变化     |
| day30\_floor\_sale\_change | double    | 前30日的地板价变化    |
| created\_at                | timestamp | 创建合集的时间戳        |
| updated\_at                | timestamp | 更新合集的时间戳        |                                                               |
