# AinaSnow FFXIV Dalamud Plugin Repository

[中文](#中文) | [English](#english)

## 中文

这是 AinaSnow 的 Dalamud 自定义插件仓库清单，后续可以在同一个 `pluginmaster.json` 中集中发布多个插件。

### 添加仓库

把下面的地址复制到 Dalamud 设置中的“自定义插件仓库”：

```text
https://raw.githubusercontent.com/AinaSnow/FFXIV-Dalamud-Plugins/main/pluginmaster.json
```

刷新仓库后，即可在插件安装器中找到并安装 `Party Marker Party List`。

源码仓库：[AinaSnow/PartyMarkerPartyList](https://github.com/AinaSnow/PartyMarkerPartyList)

### 说明

- `pluginmaster.json` 遵循 Dalamud 自定义插件仓库格式。
- 当前条目指向 `PartyMarkerPartyList` 的 `v0.1.1` GitHub Release 压缩包。
- 后续发布新版本时，需要同步更新 `AssemblyVersion`、`Changelog` 和下载地址。
- 第三方插件仓库不会经过 Dalamud 官方插件仓库审核，请确认你信任该仓库后再添加。

## English

This repository contains AinaSnow's Dalamud custom plugin repository manifest.
Multiple plugins can be distributed from the same `pluginmaster.json` in the future.

### Add the repository

Copy the following URL into the “Custom Plugin Repositories” section of Dalamud settings:

```text
https://raw.githubusercontent.com/AinaSnow/FFXIV-Dalamud-Plugins/main/pluginmaster.json
```

After refreshing the repository list, `Party Marker Party List` will be available in the plugin installer.

Source repository: [AinaSnow/PartyMarkerPartyList](https://github.com/AinaSnow/PartyMarkerPartyList)

### Notes

- `pluginmaster.json` follows the Dalamud custom plugin repository format.
- The current entry points to the `v0.1.1` GitHub Release archive of `PartyMarkerPartyList`.
- Future releases must update `AssemblyVersion`, `Changelog`, and the download URLs.
- Third-party repositories are not reviewed by the official Dalamud plugin repository. Add this repository only if you trust it.
