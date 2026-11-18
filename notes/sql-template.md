# SQL 笔记

## 五块语法（按周推进）

### 1. SELECT / WHERE / ORDER BY / LIMIT
- 什么时候用：
- 易错点：`NULL` 的比较要用 `IS NULL`；`LIMIT` 在 `ORDER BY` 之后

### 2. 聚合与分组 GROUP BY / HAVING
- `WHERE` 在分组前过滤行，`HAVING` 在分组后过滤组
- 易错点：SELECT 里非聚合列必须出现在 GROUP BY 里

### 3. JOIN
- INNER / LEFT / RIGHT / 自连接
- 画表关系图的习惯：先写「谁和谁通过什么字段连接」

### 4. 子查询 / CTE
- `WITH x AS (...)` 比嵌套子查询可读
- 什么时候必须用子查询：分组后还要再过滤

### 5. 窗口函数
- `ROW_NUMBER` vs `RANK` vs `DENSE_RANK`
- 典型题型：分组 TopN、连续 N 天、同比环比

## 错题本

| 日期 | 题目 | 卡在哪 | 正确思路（一句话） |
|---|---|---|---|
|  |  |  |  |
