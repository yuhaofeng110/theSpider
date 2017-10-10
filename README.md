# theSpider
scrapy学习根据某教程爬取了伯乐在线 拉勾网 知乎 等几个网站数据
学习总结:
0. 明白大概scrapy运行机制 yield request 以后的流程
1. 页面数据提取工具 xpath css
2. 数据处理方法 item item_loader
3. 数据入库持久化方法  item_pipline
4. 中间件使用 提供不同代理 和 user-agent 提供 phantomjs 无头浏览器解析动态页面
5. 广度/深度优先搜索在知乎页面的实践
6. scrapy 的 消息通知机制 类似scrapy关闭时触发的钩子函数

