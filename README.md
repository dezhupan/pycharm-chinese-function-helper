# Chinese Function Helper

面向 PyCharm 2026.1.x 的中文函数、方法与变量解释插件，适合正在学习 Python、NumPy、Pandas、PyTorch 等内容的用户。

## 当前版本

- 版本：`1.4.51`
- 兼容：PyCharm 2026.1.x（内部版本 `261.*`）
- 安装包：`chinese-function-helper-1.4.51.zip`

## 主要功能

- 将鼠标指向函数、方法或类并按 `Ctrl + Alt`，显示结合当前参数的中文解释。
- 启用大模型 API 后，将鼠标指向变量、返回属性或字段并按 `Ctrl + Alt + Shift`，可查看当前文件中的数据流说明。
- 显示参数用途、必填参数、返回值、当前代码和有实际区别的对照示例。
- 支持拖动、复制、滚动、重新校对以及亮色/暗色主题。
- 快捷键可在 `Settings → Tools → 中文函数助手` 中修改。

## 安装方法

1. 下载仓库中的 `chinese-function-helper-1.4.51.zip`，不要解压。
2. 打开 PyCharm，进入 `Settings → Plugins`。
3. 点击齿轮按钮，选择 `Install Plugin from Disk...`。
4. 选择下载的 ZIP，按提示完成安装或重启。

## 大模型 API

联网解释功能默认关闭。启用后可配置 OpenAI Chat Completions 兼容接口；调用失败不会影响离线解释。API Key 使用 PyCharm 的密码安全存储，不会写入插件 ZIP。

## 仓库说明

本仓库只保留当前可直接安装的插件 ZIP，历史版本不在主分支继续展示。
