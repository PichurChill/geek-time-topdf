# geek-time-topdf

print your geek time course to pdf. If you have already bought it

need phone, password, course name.

Do not record any information...

```sh
npm install geek-time-topdf -g  # in china use cnpm 推荐使用 cnpm，加快安装速度

gkpdf init
```

将你**已经购买**的极客时间的课程，打印为 pdf。

需要手机号码和密码。课程名称

**不记录任何信息**

操作说明：

![instructions](./instructions.png)

changeLogs:

- 3.1.0: 调整了滚动等待时常为 2s ，增加成功率
- 3.0.0: 处理极客时间登陆改版，导致登陆不了的问题，并且加了一个重复打印的选项
- 2.0.2: 修改页面滚动的等待时间，提高成功率
- 2.0.1: 修复 windows 系统下 特殊中文字符 pdf 生成报错的问题
- 2.0.0: 更新代码来支持极客时间的最新版页面（**必须更新，旧的包已不可使用**）
- 1.1.4: 修复自定义目录时，未正确创建目录的 bug
- 1.1.2: 版本添加 png 输出选项
