## 本文件夹用于配置学术论文页面信息

> 本页面支持以HTML方式编辑，如果超链接到外网，链接地址务必以`http`或`https`开头

编辑本目录下`paper.json`文件，可配置学术论文`年份`与`标题`信息。

格式如下：

```json
{
    "content":[
        {
            "year":"2017",
            "paper":[
                "张栋, 郭俊杰, 吴春明. 层次型多中心的SDN控制器部署[J]. 电子学报, 2017, 45(3):680-686.",
                "张栋, 薛锦. 命名数据移动自组织网络节能转发策略[J]. 福州大学学报, 2017, 45(1):63-68.",
                "郭俊杰, 张栋. 面向OpenFlow的内容分发网络视频流传输策略[J]. 福州大学学报, 2017, 45(1):58-62.",
                "张栋, 陈凯, 颜建英,朱丹红, 叶东毅. 基于隐马尔科夫模型的胎盘植入产前诊断方法[J]. 模式识别与人工智能, 2017, 30(4):353-358."
            ]
        },
        {
            "year":"2016",
            "paper":[
                "Lin, Xin An, and D. Zhang. Kemy: An AQM generator based on machine learning[C]. International Conference on Communications and NETWORKING in China IEEE, 2016:556-561.",
                "Lin,Qingxiang, and D. Zhang. Traffic-aware compatible controller deployment[C]. International Conference on Communications and NETWORKING in China IEEE, 2016:847-852.",
                "张栋, 苏晓强. 开放模式的软件工程实践教学探索[J]. 计算机教育, 2016, No.259(7):149-153."
            ]
        }
    ]
}


```

另外，本页面支持以`html`方式编辑。提供此功能为了将`论文标题`做成超链接的方式，我们对以上举例中的最后一篇论文为例，方式如下：

显示效果：

<a href='https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFD2011&filename=DZYX201106007&uid=WEEvREdxOWJmbC9oM1NjYkZCbDdrNTBLekJqMWVVZDNwNnBVajVteWY3ZW0=$R1yZ0H6jyaa0en3RxVUd8df-oHi7XMMDo7mtKT6mSmEvTuk11l2gFA!!&v=MjczNDVMT2VadVJ0RnkzaFY3ckpJVGZTZHJHNEg5RE1xWTlGWTRSOGVYMUx1eFlTN0RoMVQzcVRyV00xRnJDVVI=' target='_blank'>齐宁, 王保进, 汪斌强, 张栋. 均衡虚拟网构建算法研究[J]. 电子与信息学报. 2011, 33(6), 35-40.</a>

代码实现：
```json
"<a href='https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFD2011&filename=DZYX201106007&uid=WEEvREdxOWJmbC9oM1NjYkZCbDdrNTBLekJqMWVVZDNwNnBVajVteWY3ZW0=$R1yZ0H6jyaa0en3RxVUd8df-oHi7XMMDo7mtKT6mSmEvTuk11l2gFA!!&v=MjczNDVMT2VadVJ0RnkzaFY3ckpJVGZTZHJHNEg5RE1xWTlGWTRSOGVYMUx1eFlTN0RoMVQzcVRyV00xRnJDVVI=' target='_blank'>齐宁, 王保进, 汪斌强, 张栋. 均衡虚拟网构建算法研究[J]. 电子与信息学报. 2011, 33(6), 35-40.</a>"
```
