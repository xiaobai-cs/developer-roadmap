# 贡献

首先，感谢您考虑做出贡献。请查看以下详细信息：

* [新路线图]（# 新路线图）
* [现有路线图]（# 现有路线图）
* [添加内容]（# 添加内容）
* [指南]（# 指南）

## 新路线图

对于新的路线图，通过提供[类似于此路线图的文本路线图](https://gist.github.com/kamranahmedse/98758d2c73799b3a6ce17385e4c548a5)提交路线图在一个问题上。

## 现有路线图

对于现有的路线图，请按照捐款性质列出的详细信息进行操作：

***修复拼写错误** -- 在[路线图JSON文件]中进行更改(https://github.com/kamranahmedse/developer-roadmap/tree/master/public/project)
***添加或删除节点**-- 请根据您的建议提出问题。

**注：** 请注意，我们的目标不是拥有最大的项目列表。我们的目标是列出今天最相关的项目或技能。

## 添加内容

查找[相关路线图中的内容目录](https://github.com/kamranahmedse/developer-roadmap/tree/master/content/roadmaps).

请注意，标记有特定的格式。请按照此处给出的降价示例格式进行操作。

* 表示节点项的文件的标题。
* 添加描述路线图节点的简短摘要（最好少于200个字符）
* 在资源标题中使用`ResourceGroupTitle`标签

```html
<ResourceGroupTitle>免费内容</ResourceGroupTitle>
```

* 使用`BadgeLink`标签进行资源链接，并遵循以下指南

```html

<!-- 官方网站和文档的蓝色配色方案-->
<BadgeLink colorScheme='blue' badgeText='Official Website' href='https://reactjs.org/'>React 网站</BadgeLink>

<!-- 课程的绿色配色方案-->
<BadgeLink badgeText='Course' colorScheme='green' href='https://example.com'>React 初学者指南</BadgeLink>

<!-- 视频链接没有配色方案-->
<BadgeLink badgeText='Watch' href='https://www.youtube.com/watch?v=i793Qm6kv3U'>了解React的UI渲染过程</BadgeLink>

<!-- 博客文章和可读文本的黄色配色方案-->
<BadgeLink colorScheme='yellow' badgeText='Read' href='https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/'>什么是DNS?</BadgeLink>


```

## 指导方针

- <p><strong>添加所有可用的东西不是目标</strong><br/>路线图代表了当今最有价值的技能，即，如果你今天进入列出的任何领域，你会学到什么？！当然，今天可能会使用一些东西，但要优先考虑今天最需要的东西，例如，同意今天很多人都在使用angular.js，但你不想学习它而不是React、angular或Vue。用你的批判性思维过滤掉不必要的东西。诚实地论证为什么应该包括资源</p
- <p><strong>不要添加你没有亲自评估过的东西</strong><br/>用你的批判性思维过滤掉不必要的东西。诚实地论证为什么应该包括资源。你读过这本书吗？你能写一篇短文吗</p
- <p><strong>为内容添加创建单个PR</strong></p>
如果您计划通过向路线图添加内容来做出贡献，我建议您克隆存储库，将内容添加到[路线图的内容目录]（./content/roadmaps/）中，并创建一个PR，以便我更容易查看和合并PR。
- 写有意义的提交消息
- 在打开新问题之前查看现有问题/拉取请求
