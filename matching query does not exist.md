## 错误提示 ##

matching query does not exist.

代码

> auth = Author.objects.get(id=3, name='陈羽凡')
  

### 错误原因 ###

一般是由于get引起的,get找不到东西，所以报错

### 解决方案 ###

修改括号里的条件


