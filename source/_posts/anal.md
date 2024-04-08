---
title: 调研分析
description: 在94份问卷调查与20名同学访谈中，得出以下现象<img src="./img/67b1a2ed3485eeed6802a34c1adaf886.png" />
---
### 探究一：过年的主要方式：

![依然是看电视、吃年夜饭、走亲访友、参与春节习俗
](/img/gnfs.png)

![对过年，00后高中生最期待什么](./img/67b1a2ed3485eeed6802a34c1adaf886.png)

依然是看电视、吃年夜饭、走亲访友、参与春节习俗

### 探究二：00后高中生对年味的感觉

![00后高中生对年味的感觉](/img/feel.png)

![00后高中生对年味的感觉](/img/feel1.png)

![什么样的事情可以带来年味](/img/nw.png)

### 探究三：“年味“变淡了吗？

![alt text](/img/nwbl.png)

![alt text](/img/nwbh.png)

![alt text](/img/bdyy.png)

<script src="https://cdn.staticfile.org/echarts/5.5.0/echarts.min.js"></script>
<div id="02" style="width: 100%;height: 250px"></div>



[原始问卷](https://acmeteam.feishu.cn/share/base/form/shrcn3p3spUWi24O50thmQB1whf)
[原始数据](https://acmeteam.feishu.cn/base/PvkvbtzStap5xusr23HcZOejnBc?from=from_copylink)
[原始问卷分析](https://acmeteam.feishu.cn/share/base/dashboard/shrcnCCYQXqKh15rt9I3gEil4Kf)

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
      value: 94,
      name: "回收量"
    }, {
      value: 6,
      name: "未回收/无效"
    }]
  }]
}
  chart02.setOption(option);
</script>