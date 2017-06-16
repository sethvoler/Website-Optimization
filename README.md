## 网站性能优化项目

### PART1
1. 取消了web字体链接
2. 将print.css设置了媒体查询属性，以此取消它阻止呈现的影响
3. 将两个script标签放在了页面底下，在页面加载后运行

### PART2
1. 将changePizzaSizes函数中的重复变量集中定义
2. 删除determineDx函数，并将百分比变化放在changePizzaSizes函数内部
