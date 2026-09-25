# 笔记拾荒者

写作时从 Obsidian vault 的旧笔记中召回相关、反向、案例和金句片段。插件支持语义检索、卡片反馈和基于锚点的 AI 查询细化。

## 插件信息

- 版本：0.3.0
- 最低 Obsidian 版本：1.5.0
- 插件 ID：`biji-huangzhe`
- 默认 embedding 服务：阿里云百炼兼容接口（需自行配置 API key）

## 安装

下载本仓库中的 `main.js`、`manifest.json` 和 `styles.css`，放入 vault 的 `.obsidian/plugins/biji-huangzhe/` 目录，然后在 Obsidian 的“设置 → 第三方插件”中启用插件。详细配置、命令和功能介绍见[安装与使用](./安装与使用.md)。

也可以从 GitHub Releases 下载发布包。发布包内应直接包含上述三个插件文件。

## 配置与隐私

插件需要兼容 OpenAI API 格式的 embedding 服务。默认配置指向阿里云百炼；在 Obsidian 设置中填写自己的 API key。不要将 API key、vault 内容、插件运行产生的 `data.json` 或 `embeddings.bin` 提交到仓库。

插件索引和配置保存在 vault 的 `.obsidian/plugins/biji-huangzhe/` 目录。API 调用会将用于检索的文本发送到你配置的服务商，请根据服务商的隐私政策决定是否使用。

## 仓库内容

- `main.js`：插件代码
- `manifest.json`：Obsidian 插件清单
- `styles.css`：插件样式
- `安装与使用.md`：中文安装和使用说明

## 许可

当前源文件未附带许可证。未经作者明确授权，本仓库不声明可再分发或修改的许可。仓库所有者可在确认授权后添加合适的 LICENSE 文件。
