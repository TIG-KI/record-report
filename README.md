

# GIT 出现的错误



![1578033447654](https://github.com/TIG-KI/record-report/blob/master/screenShot/1578033440326.png?raw=true)
## 解决办法
```shell
git pull origin master
```
但是还是产生了一个新的问题（refusing to merge unrelated histories）：

![1578033739479](C:\Users\17635\AppData\Roaming\Typora\typora-user-images\1578033739479.png)

### 解决办法
```shell
git pull origin master  --allow-unrelated-histories
```
