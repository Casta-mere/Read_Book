# Read-Book “智能知识侦查助手”

## Requirement

爬取豆瓣图书Top200的书籍，编写对图书信息侦查的问卷生成程序，如进行已读/未读/没听过等选项的调查。

必备功能：

+ 数据的获取、清洗存储
+ 问卷模板制作（如判断、选择等题型）
+ 自动问卷的生成（如书籍的随机抽取、顺序的随机排布等）
+ 结果数据分析统计等

可选功能：
+ 可视化界面
+ 书籍知识点领域分类
+ 个人认知等级评估（如根据结果进行书籍的个人认知分析）

## Test 方法

+ 全部题库打乱
+ 选择某个类别
+ 选择某个书籍


## Thoughts

+ [x] 选项打乱 -- ascii码 11.06
+ [ ] 多选题
+ [ ] 问题可从书评中摘取


## 文件描述

| 文件名   | 文件描述 |
| :------- | :------- |
| code     | 代码     |
| report   | 报告     |
| record   | 过程记录 |
| resource | 相关材料 |

## Environment Requirement

- flask
- pymysql
- beautifulsoup4
- requests