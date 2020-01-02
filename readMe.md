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

### 配置修改
- 目前用到抽离的配置均放在根目录`config.toml`，参照修改即可。

### 导航菜单配置

- 编辑共目录`config.toml`（修改常用配置），参照现有配置menu配置项即可


### 运行server
- 开发运行
```
hugo server --theme=westar --buildDrafts
```
- 后台运行
```
hugo server -D
```




### 编辑发布
- 项目根目录执行`hugo`即可编译静态文件，编译后在根目录生成`public`文件夹，将public部署至指定地点即可直接访问。
- 注：编译前修改`config.toml`中baseURL参数对应当前环境域名。





