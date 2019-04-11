---
id: gas
title: Gas_rate API
sidebar_label: Bytom.Gas.API
---

## gas-rate

gas消耗率。

#### 参数

none

#### 返回

- `Integer` - *gas_rate*, gas 费率.

##### 例子
```php
$client = BytomClient::gasRate();
console_($client);
```
```js
// Result
{
  "gas_rate": 1000
}
```