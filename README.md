## 简介
if/else 工程师，个人兴趣=研究协议

## 开发环境

vscode + vim 模式

语言 go为主力，正在学习rust。

## 开源项目

### 协议
#### websocket  
[quickws](https://github.com/antlabs/quickws) 满足高tps场景的websocket协议库，包含客户端，服务端, 5800h cpu tps可以到47-48w/s

[greatws](https://github.com/antlabs/greatws) 针对海量websocket链接特别优化，基于kqueue和epoll， 100w websocket连接，只需400-500MB内存(早期阶段)
#### TODO
。。。

### util包
[gout](https://github.com/guonaihong/gout) restful api和  http benchmark lib

[clop](https://github.com/guonaihong/clop) 命令行解析器，只要会写struct，定义tag，轻松实现gnu 风格命令行

[pcurl](https://github.com/antlabs/pcurl) 解析curl命令库，生成*http.Request，让你的应用瞬间秒懂curl。

[timer](https://github.com/antlabs/timer) 基于5级时间轮实现的定时器，性能可观，fast, fast, fast

[pcopy](https://github.com/antlabs/pcopy) 高性能深度拷贝库。相比上个版本提升4-10倍性能

[brouter](https://github.com/antlabs/brouter) 高性能http router库，API风格类似httprouter，比1.3.0的httprouter快50-60%的样子，比开发版本的httprouter慢一点，大约是 92-95%的性能

[httparser](https://github.com/antlabs/httparser) 高性能http 1.1解析器，为你的异步io库插上http1.1解析的翅膀, 每秒可以处理630.15MB/s流量

