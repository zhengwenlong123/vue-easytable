2017-11-23
1、优化 table 组件固定列时，固定列与非固定列之间有裂痕的问题

2017-11-22
1、修复 table 组件footer 汇总功能没有横向滚动条的bug
2、修复 table 组件自适应无滚动条的情况切换到小屏幕，有滚动条时，列没有自适应的bug



2017-11-21
1、新增 table 组件设置背景色功能
2、优化 table 组件行点击变色功能由状态管理形式改为状态管理与dom操作结合的形式（解决上万条数据行浮动卡顿、内存飙升的问题）
3、优化 table 组件行浮动变色功能由状态管理形式改为状态管理与dom操作结合的形式（解决上万条数据行浮动卡顿、内存飙升的问题）
4、优化 table 组件当没有checkbox 多选功能时关闭相关检查

2017-11-13
1、table 组件修复表格表框有缝隙的问题
2、table 组件高度未设置或者设置的高度大于实际表格高度时，表格高度自适应

2017-11-10
1、table 组件支持通过设置样式 `v-scrollbar-wrap` 订制滚动条样式

2017-11-9
1、table 组件天假属性`column-width-drag`控制是否打开列宽拖动功能
2、修复 table 组件列拖动结束后，页面元素无法选中的bug

2017-11-8
1、table 组件添加事件`on-custom-comp`实现子组件与父组件通讯的目的

2017-10-31
1、添加 [UMD](https://github.com/umdjs/umd) 版本，html 中可以直接通过 `<script>` 标签方式引入 #29 #22

2017-10-30

1、table组件支持 footer 汇总功能
2、修复table组件高度自适应会遮住最后一行内容的问题

2017-10-24
1、修复table组件单元格编辑后分页单元格内容不变化的问题 #24
2、废除单元格编辑格式化回调函数 `cell-edit-formatter`（破坏了响应式）
3、列宽拖动在IE9下失效的问题 #20
