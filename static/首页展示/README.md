## 首页展示配置说明

本文件夹用于配置首页，编辑 `mainPageConfig.json` 文件可配置四部分内容：

第一部分：实验室名称-libName
```
libName是一个数组，第一个元素是`实验室名英文缩写`，第二个元素为`实验室全称`。
```
第二部分：导航栏内容-navContent

第三部分：轮播图-slider
```
第①步：将图片保存到slider目录：`./slider/`下并做好命名
第②步：将图片地址及名称信息保存到 `mainPageConfig.json` 文件中的slider条目下
```
第四部分：footer信息-footerContent
```
`footerContent`分为两条信息。在电脑端两条信息都可以显示，在移动端只显示第二条。
第一条可以是空字符串，第二条必须有信息。
```

格式如下：

```json
{
    "libName":["SDN","未来网络实验室"],

    "navContent":[
        "首页",
        "学术论文",
        "学术动态",
    ],

    "slider":[
        "./slider/0.jpg",
        "./slider/1.png",
        "./slider/2.png"
    ],
    
    "footerContent":[
        "地址：350116，福建省，福州市，学园路，福州大学数学与计算机科学学院2号楼504-2室",
        "Copyright@福州大学 SDN未来网络实验室 All Rights Reserved"
    ]
}
```
> 本页面 *不支持* 以HTML方式编辑