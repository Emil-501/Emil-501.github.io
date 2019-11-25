## 本文件夹用于配置学术动态页面信息

> 本页面支持以HTML方式编辑，如果超链接到外网，链接地址务必以`http`或`https`开头

编辑本目录下`dynamic.json`文件，可配置学术动态`年份`与`标题`信息。

`content`对应的数组中，内容中可以是纯文本，也可以写成HTML形式用于超链接。

链接的html文档需要自己编写，*务必* 写到`./动态内容/年份/`目录下。自己写好html后在`dynamic.json`文件中设置`年份`、`显示标题`与`对应的超链接`。

格式如下：


```json
{
    "content":[
        {
            "year":"2017",
            "content":[
                "<a href='./动态内容/2017年/P4 2017中国峰会.html' style='text-decoration:none;'>P4 2017中国峰会</a>",
                "<a href='./动态内容/2017年/江苏省高等职业院校技能大赛 出题、赛题发布、设备部署.html' style='text-decoration:none;'>江苏省高等职业院校技能大赛 出题、赛题发布、设备部署</a>"
            ]
        },
        {
            "year":"2016",
            "content":[
                "<a href='./动态内容/2016年/GNTC全球网络技术大会.html' style='text-decoration:none;'>GNTC全球网络技术大会</a>",
                "<a href='./动态内容/2016年/深圳 P4技术交流会.html' style='text-decoration:none;'>深圳 P4技术交流会</a>"
            ]
        }
    ]
}

```