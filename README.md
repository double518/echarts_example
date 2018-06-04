# echarts_example
This is a line chart drawn with echarts

1. 首先需要下载echarts包，网站为：http://echarts.baidu.com/download.html
2. 在html代码中引入echart.js
```
<!-- 引入 echarts.js -->
<script src="echarts.js"></script>
```
3. 为ECharts准备一个具备大小（宽高）的Dom
```
<div id="main" style="width: 600px;height:400px;"></div>
```
4. 
```
// 基于准备好的dom，初始化echarts实例
 var myChart = echarts.init(document.getElementById('main'));

// 指定图表的配置项和数据
var option = {
}
```
5. 
```
// 使用刚指定的配置项和数据显示图表。
myChart.setOption(option);
```
