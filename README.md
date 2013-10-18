hello_kissy
===========

*S.ready() 指在 DOM 加载完毕之后执行代码. 就像 jQuery 中的 $(document).ready().
*dom, KISSY 的 DOM 模块 , 提供常用 DOM 操作, 如元素选择/遍历, 样式的获取/修改等等.
*event, KISSY 的 Event 模块 , 提供事件处理功能, 如事件添加/删除, mouseenter/mouseleave 事件的支持等.
*dom.get(selector), 根据给出的 selector 获取符合条件的 第一个节点; 另外还有一个类似的方法叫做 dom.*query(selector) , 与前者不同的是, 得到的是 所有 符合条件的元素.
*dom.attr(elem, name, val), 获取/设置元素某个属性, 这里, 在动画开始前给按钮设置不可用状态.
*anim, 提供动画效果, 通过给元素设定参数, 就可以让这个元素动态地从当前参数变化到设定的目标参数.
*dom.get(selector)/dom.query(selector) 也可以直接用 S.get/S.query 来调用, 是一样的.