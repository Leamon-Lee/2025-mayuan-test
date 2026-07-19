# 2025 思政课题库答题卡

一个用于 2025 秋季思政课学生自测的静态答题卡页面，支持背题模式、刷题模式、进度保存、清空进度和交卷评分。项目使用纯 HTML/CSS/JavaScript 编写，可直接通过 GitHub Pages 托管。

## 在线访问

GitHub Pages 地址：

https://leamon-lee.github.io/2025-mayuan-test/

## 本地预览

直接打开根目录下的 `index.html` 即可使用：

```text
index.html
```

页面数据保存在浏览器 `localStorage` 中，只在本机生效，不会上传到服务器。

## 目录结构

```text
.
+-- index.html              # GitHub Pages 入口页面
+-- docs/
|   +-- answers.md          # 题目答案与解析
|   +-- notes.md            # 项目备注
|   +-- question-bank.pdf   # 原始题库 PDF
+-- archive/
    +-- index.html.bak      # 旧版页面备份
```

## 功能

- 背题模式：直接高亮正确答案，方便快速记忆。
- 刷题模式：隐藏答案，可选择后交卷评分。
- 本地保存：保存当前作答进度到浏览器。
- 清空进度：一键清除本地作答记录。
- 混合题型：支持单选、多选和判断题。

## 部署说明

该项目是静态页面项目，GitHub Pages 推荐设置为：

- Source: `Deploy from a branch`
- Branch: `master`
- Folder: `/ (root)`

保持 `index.html` 在仓库根目录即可正常托管。
