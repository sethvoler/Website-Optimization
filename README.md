## 网站性能优化项目

### PART1
1. 取消了web字体链接
2. 将print.css设置了媒体查询属性，以此取消它阻止呈现的影响
3. 将两个script标签放在了页面底下，在页面加载后运行
4. 将原本的外部样式表style.css删除并改为内联样式

### PART2
1. 将重复变量集中定义
2. 删除determineDx函数，并将百分比变化放在changePizzaSizes函数内部
3. 将guerySelector*方法均改为getELement*类方法
4. 将updatePositions函数中的document.body.scrollTop在循环外定义，防止布局抖动
5. 将每一次滚动渲染200个背景披萨减少为30个
