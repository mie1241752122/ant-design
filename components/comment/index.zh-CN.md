---
category: Components
type: Data Display
title: Comment
subtitle: 分割线
cols: 1
---

 单一评论组件。

 ## When To Use

 评论可用于启用对实体的讨论，例如页面，博客文章，问题或其他。

 ## API

| Property | Description | Type | Default |
| -------- | ----------- | ---- | ------- |
| actions | 在评论内容下面呈现的操作项列表 | Array<ReactNode> | - |
| author | 要显示为注释作者的元素 | ReactNode | - |
| avatar | 要显示为评论头像的元素 - 通常是antd `Avatar` | ReactNode | - |
| children | 嵌套注释应作为注释的子项提供 | ReactNode | - |
| className | 网格容器类名 | string | - |
| content | 评论的主要内容 | ReactNode | - |
| contentStyle | 要应用于评论内容的内联样式 | object | - |
| headStyle | 内联样式应用于评论头像 | object | - |
| id | 评论的可选ID | string | - |
| innerStyle | 内容的附加风格 | object | - |
| prefixCls | 注释前缀className默认为`.ant-comment` | string | .ant-comment |
| style | 评论的其他风格 | object | - |
| time | 包含要显示的时间的时间元素 | ReactNode | - |