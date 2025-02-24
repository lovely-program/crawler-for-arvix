# crawler-for-arvix
这是我在完成LLM assitant for academic work的一个学习项目
主要内容是使用re和requests库爬取开源文献网站arvix materials science两页180篇文献的title，arvix doi，author和html url的信息
主要进步：
1. 学会了使用re的findall()和search()方法
2. 学会了re的正则表达式
3. 学会了使用requests库的get(）和post()方法
4. 将爬取功能封装为单个函数，便于调用和修改
### 下一步的升级方向：
1. 学会应对反爬虫机制，研究如何合法地获得cnki、WOS等网站和jacs、angew等期刊的文献信息
2. 学会设定自动化的爬虫，在固定时间爬取信息
3. 学会通过爬虫下载文献
4. 学习transformer，GNN框架，完成一次模型的微调
5. 将LLM agent引入文献的筛选，对比，阅读和文献核心内容卡片的撰写工作
