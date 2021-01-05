# README
先运行
`mvn install -Dmaven.test.skip=true`
-Dmaven.test.skip=true   

- UserServiceNoI
- Main

````shell script
class com.sun.proxy.$Proxy0
动态代理拦截-before
userService.save保存
动态代理拦截-after:null
动态代理拦截-before
userService.count数量
动态代理拦截-after:3
````

```shell script
2147483647
3.4028235E38
```
