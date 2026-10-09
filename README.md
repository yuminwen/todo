# H5 Todo 待办清单

一个轻量级 H5 待办清单网页应用，使用原生 HTML、CSS 和 JavaScript 实现，无需构建工具或后端服务。

## 功能

- 新增待办事项
- 标记完成或取消完成
- 编辑待办内容
- 删除单条待办
- 按「全部 / 待办 / 完成」筛选
- 一键清除已完成事项
- 使用浏览器 `localStorage` 自动保存数据
- 适配移动端和桌面端浏览器

## 快速开始

直接用浏览器打开 `index.html` 即可使用。

```bash
open index.html
```

也可以在文件管理器中双击打开：

```text
/Users/bytedance/Documents/projects/git-study/index.html
```

## 项目结构

```text
.
├── README.md
└── index.html
```

## 技术说明

- 页面结构、样式和交互逻辑均内置在 `index.html` 中。
- 数据保存在当前浏览器的 `localStorage`，刷新页面后仍会保留。
- 不依赖 npm、Node.js、数据库或远程接口。

## 使用说明

- 在输入框中输入待办内容，点击添加按钮或按回车创建事项。
- 点击圆形勾选按钮切换完成状态。
- 点击编辑按钮可修改事项内容。
- 点击删除按钮可移除事项。
- 使用筛选按钮查看不同状态的事项。
