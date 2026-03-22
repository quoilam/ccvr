# 算法路径在真实地图上的可视化

Inspired by [A* (A-Star) Pathfinding Algorithm Visualization on a Real Map](https://www.youtube.com/watch?v=CgW0HPHqFE8)

受视频启发, 使用这个项目来可视化算法路径在真实地图上的表现.
荣获 2023年ccvr数据可视化 国赛一等奖

### 简要模块介绍
- algorithm: 包含算法的cpp实现, 当然也可以使用其他语言实现, 只要输出格式与cpp文件相同即可 (参考 [输出文件example](./algorithm/t.txt))
- data: 程序处理的中间数据
- js: 包含可视化的js代码, 包括百度api、echarts、jq等
- scripts: 包含一些数据处理的脚本, 包括地图数据格式的转换

### 运行说明
由于是竞赛代码, 内容较为混乱, 但是核心步骤逻辑还算比较清晰
主要参见 [main.ipynb](./main.ipynb) 中的内容
以及需要从[OpenStreetMap](https://www.openstreetmap.org)下载地图数据, 进行格式转换等步骤, 具体参见 [scripts/](./scripts)