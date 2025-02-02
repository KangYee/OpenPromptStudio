# 🥣 OPS/OpenPromptStudio

## 提示词工作室 | 可视化编辑提示词

[立即试试 moonvy.com/apps/ops/ ](https://moonvy.com/apps/ops/)

![](./doc%2Fassets%2F%E6%88%AA%E5%B1%8F2023-04-02%2001.31.05.png)

这是一个旨在把 AIGC 提示词（现在支持 Midjourney）可视化并提供编辑功能的工具，有以下特性

-   显示英文提示词的中文翻译
-   翻译输入的中文提示词到英文（因为 Midjourney 仅支持英文提示词）
-   为提示词进行分类（普通、样式、质量、命令）
-   轻松的排序、隐藏提示词
-   把提示词可视化结果导出为图片
-   常用提示词词典
-   通过 Notion 管理提示词词典

## 如何修改提示词词典

1. 在 [./data/src](https://github.com/Moonvy/OpenPromptStudio/tree/master/data/src) 中编辑 `.csv` 文件，你可以用 Excel、Numbers 或者纯文本编辑器编辑。

2. 在 [Notion](https://www.notion.so/) 中编辑（[./data/src/notion/fromNotion.js](https://github.com/Moonvy/OpenPromptStudio/data/src/notion/fromNotion.js) ）

现在我们在 [Notion](https://www.notion.so/) 中管理提示词字典，之后开发让用户连接自己的 [Notion](https://www.notion.so/) 数据库的功能，让用户能更好的管理属于自己的词典。

运行 `npm run fetch` 把 2 个来源的数据整理在一起

## 更好的体验

你可以在 [zeroG 浏览器](https://moonvy.com/zeroG/) 里让 OPS
与 Discord 在一个无限画布中使用，获得更好的体验
![截屏2023-04-06 15.51.23.png](./doc%2Fassets%2F%E6%88%AA%E5%B1%8F2023-04-06%2015.51.23.png)
