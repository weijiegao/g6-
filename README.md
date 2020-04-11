# g6-TreeGraph
实现点击节点时高亮节点的父节点及边、默认展开的控制、只展开一个兄弟节点（收缩其他兄弟节点）
# 默认展开节点的控制
在data中新增节点字段collapse: true,可以控制该节点收缩/折叠 
# data来源
使用官方的data格式，必须包含id、children字段
