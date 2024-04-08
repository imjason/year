---
title: 关于我们在校内所做的调研之分析
description: 关于我们在校内所做的调研之分析
---
<script src="https://cdn.staticfile.org/echarts/5.5.0/echarts.min.js"></script>
<div id="02" style="width: 100%;height: 400px"></div>

![alt text](d85039ef5062bda882fd94af5344025e.png)
![alt text](684ae7e16cf7cc30e2bf7beb4d95d50c.png)
![alt text](6c194a37d9c77d3c9f67ee4860cd9a01.png)
![alt text](d000c4f4348c8cd57eaf7442bf5821af.png)
![alt text](2f51cfe1ea0048e3f5924dfa40f1424c.png)
![alt text](a751353aa3beb392e630377ec6beb0f9.png)
![alt text](9ff5953f48bac363fe863bbedc4103b0.png)
![alt text](947ef53e904da37db91db05bfd60fe66.png)
![alt text](89f2baa6ff189ce01a42c21b0e227d10.png)
![alt text](f35ecef1cc09142b3532360e760d368d.png)

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