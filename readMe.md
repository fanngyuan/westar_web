# ReadMe

### 发布内容
- 发布新闻
```
# 新建新闻文稿文件
hugo new news/FileName.md # news目录创建文件
hugo new faq/FileName.md  # faq目录创建文件

# 编辑文件 ./content/news/FileName.md 添加内容

```

- 发布文件头参数说明示例
```
---
title: "标题"
date: 2017-11-17T12:41:44+08:00
draft: false # 草稿状态否
description: "文章描述，相关应用地方调用该字段"
cover: http://cn.bing.com/az/hprichv/LondonTrainStation_GettyRR_139321755_ZH-CN742316019.jpg" # 文章引用缩略图处使用，没有使用系统默认1-4张图随机
---
```

### 运行server
- 开发运行
```
hugo server --theme=westar --buildDrafts
```
- 后台运行
```
hugo server -D
```
