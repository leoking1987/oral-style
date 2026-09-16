# 口语化skill

将 Marie、Kevin 写作技能产出的中文稿件进一步改成自然口播，同时优化观众追问、内容结构和叙事。

显示名为 **口语化skill**；兼容调用名为 **`$oral-style`**。

## 使用

公开仓库：[leoking1987/oral-style](https://github.com/leoking1987/oral-style)。[下载完整技能包](https://github.com/leoking1987/oral-style/archive/refs/heads/main.zip)。

下载并解压后，将 `oral-style-main` 文件夹重命名为 `oral-style`，放到下列位置：

- Windows：`%USERPROFILE%\.codex\skills\oral-style\`
- macOS / Linux：`~/.codex/skills/oral-style/`

确认 `SKILL.md` 直接位于 `oral-style` 文件夹内，保留 `agents` 子目录。安装后新建 Codex 会话，使用 `$oral-style` 调用。

将本仓库文件放入 `~/.codex/skills/oral-style/`，保留目录结构。

```text
用 $oral-style 改写下面这篇 Kevin 稿，保留作者身份、事实、标题与首句一致，长度接近原稿。
```

也可先用 `$marie-writer` 或 `$kevin-writer` 产稿，再用本技能做第二轮改写。

## 文件

- [SKILL.md](SKILL.md)：技能入口与工作流。
- [methods.md](methods.md)：十种可执行的话术与结构改法。
- [examples.md](examples.md)：原创改写前后对照。
- [evidence.md](evidence.md)：2026年9月16日研究口径、近一个月Top5、方法来源及证据边界。
- [agents/openai.yaml](agents/openai.yaml)：中文显示名和默认调用提示。

基于公开完整视频的内部分析提炼，不包含源视频或逐字稿；保留原作者人物与事实边界，不承诺播放、留存或成交提升。
