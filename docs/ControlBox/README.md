# ControlBox 盒子

盒子通常用于容纳一组不同的控件但由整个盒子统一响应用户触发的事件。
不同于普通的容器或普通的控件，它们具有容器的基本布局功能，也具备控件的事件响应机制。

一般用于列表中显示一个子项，或者树形列表中显示一个节点，但这些子项和节点可能包含丰富的图标和文字描述并要求可以响应用户触发的事件。
在这种场景下就会使用到这些盒子了，以下为支持的盒子模型：

 - `ListContainerElement` 常用于列表中显示一个子项
 - `TreeNode` 常用于树形列表中显示一个子节点
 - `Other` 一些其他的盒子模型，参考 [Other](Other.md)