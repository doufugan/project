# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

* Red
* Green
* Blue

1 Red
2 Green
3 Blue

> test1
>> test2
>>> test3

```javaScript
console.log('test')
```

# querystring

## 引用：var qs = require("querystring");
## 常用API: qs.parse(str);
> 示例：
``` js
const qs = require("querystring");
var url = "uname=lilei&upwd=123456";
var obj = qs.parse(url);
console.log(obj);
```
> 输出：
``` js
{ uname: 'lilei', upwd: '123456' }
```
