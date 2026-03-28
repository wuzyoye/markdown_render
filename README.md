# Markdown Reader

一个基于单文件 `render.html` 的轻量级 Markdown 阅读与编辑器。

## 主要功能

- 支持打开并渲染 Markdown 文件：`.md`, `.mdx`, `.markdown`, `.txt`
- 实时预览：编辑区与预览区可切换“编辑 / 分屏 / 预览”模式
- 目录侧边栏：自动生成 Markdown 标题目录，支持快速跳转
- 文件管理面板：可打开多个文件、切换、重命名、关闭
- 拖放支持：可将 Markdown 文件拖入窗口直接打开
- 粘贴内容：通过内置弹窗粘贴 Markdown 文本并打开
- 语法高亮：使用 `highlight.js` 对代码块进行高亮显示
- 代码复制：代码块内提供“一键复制”按钮
- 搜索查找：编辑区内查找并跳转匹配项
- 夜间模式：支持浅色 / 深色主题切换
- 键盘快捷键：Ctrl+N、Ctrl+O、Ctrl+S、Ctrl+F、Alt+T、Alt+F 等

## 使用说明

1. 直接在浏览器中打开 `render.html`
2. 通过“打开”按钮或拖放文件加载 Markdown
3. 在编辑区编写或修改 Markdown 内容
4. 预览区会自动实时渲染
5. 点击“保存”可将当前文件导出为 Markdown 文件

## 支持格式

- `.md`
- `.mdx`
- `.markdown`
- `.txt`

## 键盘快捷键

- `Ctrl+N`：新建文件
- `Ctrl+O`：打开文件
- `Ctrl+S`：保存当前文件
- `Ctrl+F`：查找
- `Alt+T`：切换目录面板
- `Alt+F`：切换文件面板
- `Ctrl+Tab`：切换打开文件
- `Esc`：关闭查找 / 粘贴弹窗

## 技术栈

- `marked`：Markdown 渲染
- `highlight.js`：代码高亮
- 纯原生 HTML/CSS/JavaScript，无额外构建依赖

## 说明

该项目是一个纯前端 Markdown 阅读器，适合作为本地 Markdown 预览器或轻量编辑器。直接打开 `render.html` 即可运行，无需服务器环境。