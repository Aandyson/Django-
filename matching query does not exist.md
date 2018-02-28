## 错误提示 ##

matching query does not exist.

代码

> auth = Author.objects.get(id=3, name='陈羽凡')
  

### 错误原因 ###

使用get方法时，当找不到匹配的query时，就会报DoesNotExist exception.

### 解决方案 ###

修改括号里的条件


