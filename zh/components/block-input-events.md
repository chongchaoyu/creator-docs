# BlockInputEvents 组件参考

BlockInputEvents 组件将拦截所属节点 bounding box 内的所有输入事件（鼠标和触摸），防止输入穿透到下层节点，一般用于上层 UI 的背景。

当我们制作一个弹出式的 UI 对话框时，对话框的背景默认不会截获事件。也就是说虽然它的背景挡住了游戏场景，但是在背景上点击或触摸时，下面被遮住的游戏元素仍然会响应点击事件。这时我们只要在背景所在的节点上添加这个组件，就能避免这种情况。

该组件没有任何 API 接口，直接添加到场景即可生效。
