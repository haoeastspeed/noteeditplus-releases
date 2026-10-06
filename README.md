# NoteEditPlus

Windows 原生、轻量、快速的代码/文本编辑器。Rust + wgpu 构建，兼顾 Notepad++ 的轻量与现代编辑器的体验。

- **产品主页**：<https://haoeastspeed.github.io/noteeditplus-releases/>
- **下载**：见 [Releases](https://github.com/haoeastspeed/noteeditplus-releases/releases/latest)
- **自动更新清单**：[`stable.json`](stable.json)

## 下载安装

- **安装版**：下载 `NoteEditPlus-Setup.exe`，每用户安装（无需管理员），开始菜单与卸载入口齐全。
- **便携版**：下载 `NoteEditPlus-<version>-windows-x64-portable.zip`，解压即用，配置随程序目录。
- 所有文件均提供 `.sha256` 校验值；软件更新会自动校验 SHA256。

## 主要特性

- 多标签编辑、会话恢复、定时快照与崩溃恢复
- Tree-sitter 12 种语言语法高亮与代码折叠
- 查找替换（正则/整词/大小写）、多文件后台搜索
- 多编码（UTF-8/GBK/UTF-16 等）与多种行尾（CRLF/LF/CR）
- WASM 插件（sidecar 运行时，按需启动）、Scintilla 兼容宿主
- LSP：诊断、补全、转到定义、悬浮提示
- 多主题、设计系统、AI 辅助面板
- 托管自动更新（后台下载 + SHA256 校验 + 提示安装）

## 许可证

GPL-2.0（与 Notepad++ 一致），详见 [LICENSE](LICENSE)。源码托管于私有仓库。
