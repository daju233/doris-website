---
{
    "title": "ISNULL",
    "language": "zh-CN"
}

---

<!-- 
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

## 描述

返回表达式是否为空的`bool`值。

:::info 备注
从 Apache Doris 2.1.10 开始支持该函数
:::

## 语法

```sql
ISNULL(<expr>)
```

## 参数

| 参数     | 描述                             |
| -------- | -------------------------------- |
| `<expr>` | 需要判断是否为 `NULL` 的表达式。 |
|          |                                  |

## 返回值

- 返回表达式是否为空的`bool`值。 

## 举例

```sql
SELECT ISNULL(NULL);
```

```text
+--------------+
| ISNULL(NULL) |
+--------------+
|            1 |
+--------------+
```
