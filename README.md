# JarRunner
Acquire necessary JVM options and transfer start parameters to the core jar file. Help output text correctly in console.

## 开发原因

很多时候大多数用户不能正确按照教程配置java路径，或添加file.encoding=utf-8等jvm参数。因此采用牵引启动的方式解决该问题，同时保证输出内容不乱码。
