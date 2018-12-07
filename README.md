# react-native-echarts-cus
[echarts4.2](http://echarts.baidu.com/option-gl.html#globe)的图表,实现echarts的各种图表,
本组件使用百度的[echarts4.2](http://echarts.baidu.com/option-gl.html#globe)
使用方法遵循[native-echarts](https://github.com/somonus/react-native-echarts)

###  安装组件：
npm i --save react-native-echarts-cus

### 使用（查看[native-echarts](https://github.com/somonus/react-native-echarts)）
本组件是基于[native-echarts](https://github.com/somonus/react-native-echarts)
的一次升级改造，主要解决图表每次刷洗状态（图表绘制数据未变化）图表就会重启
将echarts库替换为最新的；<br>
若使用者想替换echarts库，则进入node_modules\react-native-echarts4-2\src\components\Echarts
将tpl.html打开，把script标签里的echarts库的代码替换成你想要的echarts库就行；<br>
若你愿意就把echarts.min.js中echarts库代码替换掉,就替换，因为echarts.min.js换不换没有影响；<br>
若替换，注意echarts.min.js中的export default '这是echarts库代码'


### [我的博客](http://blog.sina.com.cn/s/articlelist_6078695441_0_1.html)
