# problem-collect
问题总汇

####### 1、小程序中自定义tabbar会被webview覆盖掉，如果想要在tabbar中嵌入webview只能用原生tabbar，不能使用custom属性；
####### 2、当使用flex布局时候，flex：1属性的组件需要配合width：0来实现自动计算宽度，否则会被组件会被撑开；
####### 3、在小程序中使用多行文本超出后省略号代码时，需要-webkit-box-orient: vertical; 这个属性后面加上这个注释 /* autoprefixer: off */ ，否则小程序中只能使用行内样式来实现，class形式或者封装全局样式都不生效；
####### 4、多组件重叠布局，保证点击方法不穿透，css添加样式pointer-events: none;
