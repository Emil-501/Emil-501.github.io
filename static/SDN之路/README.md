## 本文件夹用于配置SDN之路页面信息

编辑`theRoadofSDN.json`可配置SDN之路条目，在最小单元的数组中有两个参数，第一个参数为`标题`，第二个参数为`超链接地址`，如果不想配置超链接，第二个参数可为空字符串。

>注：超链接地址必须以`http`或`https`开头

格式如下：


```json

{
    "content":[
        ["P4 Github: p4lang","https://github.com/p4lang"],
        ["入门论文:《The Road to SDN》",""],
        ["入门论文:《OpenFlow: Enabling Innovation in Campus Networks》",""],
        ["入门论文:《Software-Defined Networking: A Comprehensive Survey》",""],
        ["SDNLAB 实验平台","https://www.sdnlab.com/1749.html"],
        ["SDNLAB SDN Guide","https://www.sdnlab.com/sdn-guide/"]
    ]

}

```

> 本页面 *不支持* 以HTML方式编辑