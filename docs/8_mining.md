---
id: mining
title: Mining API
sidebar_label: Bytom.Mining.API
---

## is-mining

返回挖矿状态。

#### 参数

none

#### 返回


- `Boolean` - *is_mining*, 节点是否启动了挖矿.

#### 例子
```php
$client = BytomClient::isMining();
console_($client);
```
```js
// Result
{
  "is_mining": true
}
```

## set-mining

启动节点。

#### 参数

- `Boolean` - *is_mining*, 节点是否启动了挖矿.

#### 例子
```php
$client = BytomClient::setMining();
console_($client);
```
```js
// Result
//none
```