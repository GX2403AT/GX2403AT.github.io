# 可作弊随机数生成器

## 说明
抓阄、宴会、值班、真心话……看你会不会用了

使用[MDUI](https://www.mdui.org/)
## 配置
自定义[cheatList](index.html#L75)：
```javascript
var cheatList = {
                    17: 60,
                    18: 0,
                    19: 0,
                    13: 0
                };
```
假设抽取的是1-55，本来是在1-20各一个的55个数字抽取一个，
定义`cheatList`后，17号变成了60个，而13、18、19号则被排除在外。
这样17号的中奖概率高达52%。

## 兼容性
Chromium 48.0、70.0、80.0以及IE 11下均通过

## License
MIT