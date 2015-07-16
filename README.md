# AutoLayout实现多个view等宽等高
#实现过程步骤:
1:先给最左边的view添加一个了leading space约束，然后再给最右边的view添加一个trailing space约束
2:给所有的view分别添加一个top space约束和高度height约束
3:给所有view分别添加等宽约束和horizontal space水平间距约束

#实现过程以及demo效果图
![Image](https://github.com/KBvsMJ/AutoLayoutDemo/blob/master/demogif/1.gif)
