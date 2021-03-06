## 中国36个主要城市的生活压力对比分析

### 1. pythonanywhere部署链接  
[36个主要城市的生活压力对比分析](http://leetong.pythonanywhere.com/)

### 2. 数据故事的选题  
即将毕业的我，面对的最严峻的问题就是就业问题，我该选择去哪座城市就业和发展？在发展迅速的今天，工作机会多、薪资待遇高、个人进步快等是不仅是大多数毕业生选择某城市就业的主要原因也是大多数非毕业生的劳动力人口选择某城市的主要原因，但这些城市通常给他们带来了无限的压力。近几年，买房压力大、就业压力大、开销压力大等成为了大多数人的抱怨之词，那么究竟我们生活的城市的生活压力到底有多大？在哪座城市生活压力会更低？

### 3. 数据的收集和清洗  
从“人口密度”、“平均工资”、“人均消费支出”、“住宅商品房平均房价”和“失业率”5个维度进行了数据的收集和清洗。
- “平均工资”和“住宅商品房平均房价”数据来源于[国家统计局](http://data.stats.gov.cn/easyquery.htm?cn=E0105)
- 其余数据均来源于各地方的统计局数据和统计年鉴

### 4. 相关界面和内容介绍  

|    界面    | 内容介绍 | 
| ------ | ---- |
| [首页](http://leetong.pythonanywhere.com/) | 36个主要城市的生活压力排名  |   
| [人口密度](http://leetong.pythonanywhere.com/density) | 了解2018年36个主要城市的人口密度情况，反映各城市的就业竞争情况  |   
| [人均消费支出与平均薪资](http://leetong.pythonanywhere.com/consumption) | 分析36个主要城市的人均消费支出和平均薪资的关系，了解人均的基本储蓄  |   
| [住宅商品房平均房价](http://leetong.pythonanywhere.com/house_prices) | 36个主要城市近10年各城市的住宅商品房的平均房价，了解各城市的购房压力  |   
| [失业率](http://leetong.pythonanywhere.com/unemployment) | 36个主要城市近5年的失业率，通过失业率了解各城市的就业环境  |   

### 5. 交互实现
- 数据可视化交互图制作-代码档：https://github.com/ViTaSoyi/interactive_visualization/blob/master/36%E4%B8%AA%E4%B8%BB%E8%A6%81%E5%9F%8E%E5%B8%82%E7%9A%84%E7%94%9F%E6%B4%BB%E5%8E%8B%E5%8A%9B.ipynb
- flask搭建与数据交互-Python代码档：https://github.com/ViTaSoyi/interactive_visualization/blob/master/app.py
- 数据交互-HTML代码档：https://github.com/ViTaSoyi/interactive_visualization/tree/master/templates
