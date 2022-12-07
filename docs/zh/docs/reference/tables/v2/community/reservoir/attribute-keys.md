# 属性键值

## **reservoir.attribute_keys**

该表包含有每个属性键值的记录。

查询的示例可以在这里找到：

[https://dune.com/queries/1302930/2232305](https://dune.com/queries/1302930/2232305)

| **列名称** | **类型**  | **说明**                          |
|-----------------|-----------|------------------------------------------|
| id              | string    | 内部属性键值ID                |
| collection\_id  | string    | 相关合集ID                 |
| key             | string    | 键值名称                |
| kind            | string    | 值类型 (字符串, 数字, 日期, 范围) |
| rank            | string    | 排序顺序                               |
| created\_at     | timestamp | 创建属性键的时间戳  |
| updated\_at     | timestamp | 更新属性键的时间戳  |
