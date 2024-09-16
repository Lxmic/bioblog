---
title: XCMS online tool
author: lxmic
date: '2024-09-11'
slug: xcms-online-tool
categories:
  - Online Tools
tags:
  - LC/MS
  - XCMS
thumbnail: https://cdn.jsdelivr.net/gh/lxmic/Picture-bed@master/uPic/2024-09-11featured.png
---

## 注册XCMS网站
网址：[https://xcmsonline.scripps.edu/landing_page.php?pgcontent=mainPage](https://xcmsonline.scripps.edu/landing_page.php?pgcontent=mainPage)
{{% callout note %}}
最好使用edu的邮箱，否则不好注册。
{{% /callout %}}
![sign-up](image.png)
![email](image-1.png)

## 新建任务
![newjob](image-2.png)
- 查看可之间上传的文件格式
![file format](image-4.png)

## 可上传的数据格式
若不满足以下数据格式，可使用[ProteoWizard](http://proteowizard.sourceforge.net/downloads.shtml)进行转换。
![vendor](image-3.png)
Ailgent的数据格式`.d`需要进行转换，通常可以将其转换为`.mzxml`。否则是无法整个上传，会将文件夹中的所有文件分开上传。转换后数据如下：
![mzxml](image-6.png)
{{% callout note %}}
转换方法详情见文章[MSconvert](https://lxmic.netlify.app/post/msconvert/)
{{% /callout %}}

## 上传需要比较的文件
### <font color=orange>先上传对照组，生物学重复一起上传</font>

![Alt text](image1.png)

![Alt text](image2.png)
上传了数据集1共4个文件,点击next
![Alt text](image-5.png)

### <font color=orange>上传处理组</font>
![Alt text](image-7.png)

### <font color=orange>选择参数</font>
![Alt text](image-10.png)

### <font color=orange>修改项目名，点击submit</font>
![Alt text](image-11.png)

## 查看进展
提交完会直接跳转到改进展页面，也可以在`View Results`中看处理结果。
![Alt text](image-12.png)
过一段时间刷新后，可看到已经处理45%
![Alt text](image-13.png)

## View分析之后的结果
点击view
![Alt text](image-14.png)
可以看到这些结果
![Alt text](image-15.png)
## 点击metabolic cloud plot
图中绿色的代表含量显著升高；红色代表显著下降。
![Alt text](image-16.png)
可以将云图下载为png，jpeg，或者svg矢量图。
![Alt text](image-19.png)
## table view
点击箭头处的按钮，进入列表模式，看到左右显著变化的物质。
![Alt text](image-17.png)

列表信息显示很多参数，fold，up or down, RT and so on.可以点击下载表格，进行进一步分析。
![Alt text](image-18.png)

点击表格上的行可以再表格右边显示feature详细信息，包括EIC和MS spectrum，以及最右下角可能物质的展示。
![Alt text](image-20.png)

![Alt text](image-20.png)
{{% callout note %}}
对某些物质进一步分析，用MassHunter工具分析，根据二级质谱推测可能的物质结果。
{{% /callout %}}