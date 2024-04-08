---
title: 关于我们在校内所做的调研之分析
description: 关于我们在校内所做的调研之分析
---
<script src="https://cdn.staticfile.org/echarts/5.5.0/echarts.min.js"></script>
<div id="01" style="width: 100%;height: 400px"></div>
<div id="02" style="width: 100%;height: 400px"></div>

[原始问卷](https://acmeteam.feishu.cn/share/base/form/shrcn3p3spUWi24O50thmQB1whf)
[原始数据](https://acmeteam.feishu.cn/base/PvkvbtzStap5xusr23HcZOejnBc?from=from_copylink)
[原始问卷分析](https://acmeteam.feishu.cn/share/base/dashboard/shrcnCCYQXqKh15rt9I3gEil4Kf)

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


<script type="text/javascript">
        var chart02 = echarts.init(document.getElementById('02'));
        var option = {
  legend: {
    orient: "vertical",
    left: "left",
    data: ["Apple", "Grapes", "Pineapples", "Oranges", "Bananas"]
  },
  series: [{
    type: "pie",
    data: [{
      value: 335,
      name: "Apple"
    }, {
      value: 310,
      name: "Grapes"
    }, {
      value: 234,
      name: "Pineapples"
    }, {
      value: 135,
      name: "Oranges"
    }, {
      value: 1548,
      name: "Bananas"
    }]
  }]
}
chart02.setOption(option);
    </script>