---
title: 关于我们在校内所做的调研之分析
---
<script src="https://cdn.staticfile.org/echarts/5.5.0/echarts.min.js"></script>
<div id="01" style="width: 100%"; height: auto></div>
    <script type="text/javascript">
        var chart01 = echarts.init(document.getElementById('01'));
        var option = {
            title: {
                text: '第一个 ECharts 实例'
            },
            tooltip: {},
            legend: {
                data:['销量']
            },
            xAxis: {
                data: ["衬衫","羊毛衫","雪纺衫","裤子","高跟鞋","袜子"]
            },
            yAxis: {},
            series: [{
                name: '销量',
                type: 'bar',
                data: [5, 20, 36, 10, 10, 20]
            }]
        };
        chart01.setOption(option);
    </script>
