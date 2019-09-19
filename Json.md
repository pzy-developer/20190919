# Json的使用
## Json的定义
JSON 是用于存储和传输数据的格式。  
```
  var jsonStr = "{name:'object',info:'info'}"
```
## 对象与Json之间的转换  
```
  var jsonObj = JSON.parse(jsonStr); // 字符串转对象
  var str = JSON.stingify(jsonObj); // 对象转字符串
```
