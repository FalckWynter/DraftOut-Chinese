# Draftout 简体中文汉化

这里是 Minecraft Mod Draftout 的简体中文汉化文件，包含任务目标、菜单和提示文本。

2026/11/12 更新：新增 **Draftout 1.18.0 / Minecraft 26.3** 汉化，共 823 条。

## 版本下载

| Draftout 版本 | 汉化 JSON | 说明 |
| --- | --- | --- |
| 1.18.0 | [zh_cn.json](1.18.0/zh_cn.json) | Minecraft 26.3，当前默认资源包版本 |
| 1.11.1 | [zh_cn.json](1.11.1/zh_cn.json) | 保留旧版本适配 |
| 1.10.3 | [zh_cn.json](1.10.3/zh_cn.json) | 保留旧版本适配 |

不同版本的翻译 key 和内容存在变化，请选择与 Draftout 版本匹配的文件。下载单独的 JSON 时，在 GitHub 文件页面点击下载原始文件，不要保存网页。

本仓库只包含翻译文件，不包含 Draftout MOD 本体、代码、贴图或其他原始资源。Draftout 归原作者所有。

## 推荐安装方式：资源包

以下步骤适用于 Draftout 1.18.0 / Minecraft 26.3，无需修改 MOD JAR：

1. 在本仓库点击 **Code → Download ZIP**，解压下载文件。
2. 找到同时包含 `pack.mcmeta` 和 `assets` 的文件夹，通常为 `DraftOut-Chinese-main`。
3. 将该文件夹整体放入游戏实例的 `minecraft/resourcepacks` 中。不要直接放入 GitHub 下载的外层 ZIP，因为其中还有一层目录。
4. 进入游戏的“选项 → 资源包”，启用该汉化包；若有其他包修改 Draftout 文本，将本汉化包放在更高优先级。
5. 将游戏语言设为“简体中文”。游戏已启动时，启用资源包并等待资源重载即可。

正确的文件层级如下：

```text
resourcepacks/
  DraftOut-Chinese-main/
    pack.mcmeta
    assets/draftout/lang/zh_cn.json
```

仅下载 JSON 的用户，可将对应版本文件放入自己资源包的 `assets/draftout/lang/zh_cn.json`。资源包的 `pack.mcmeta` 必须匹配实际 Minecraft 版本；仓库根目录提供的元数据仅面向 26.3。

也可手动将对应版本的 JSON 加入 MOD JAR 的相同路径，但请先备份 JAR，且更新 MOD 后需要重新安装汉化。

## 文件说明

- `1.10.3/`、`1.11.1/`、`1.18.0/`：各版本独立的汉化 JSON。
- `assets/draftout/lang/zh_cn.json`：当前 1.18.0 汉化，与版本目录中的文件一致。
- `pack.mcmeta`：Minecraft 26.3 资源包元数据。
- `使用方法.txt`：离线安装说明。

## 1.18.0 更新说明

以 1.18.0 JAR 内的 `en_us.json` 为基准，相较 1.11.1 新增 397 个 key、修改 11 条英文原文、移除 11 个 key。沿用仍适用的旧译文，补齐新目标、回放、大厅设置和界面内容，并核对 Minecraft 26.3 的中文物品、生物及进度名称。

已校验 JSON 格式、823 个 key 的完整性、占位符及换行；尚未完成游戏内界面显示验证。

## 署名

好多好多鱼制作，ChatGPT 协助翻译。转发请注明作者。

