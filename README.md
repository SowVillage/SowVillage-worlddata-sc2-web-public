# SowVillage-worlddata-sc2-web-public

老母猪村生存服二周目的最终静态地图数据。仅包含可直接调用的三维分区、二维瓦片、压缩索引和配套材质；解析代码、原存档及本地审计资料不上传。

- `world/manifest.json.gz`：地图目录；`world/palette.json.gz`：方块索引。
- `world/{overworld,nether,end}/`：三维 `.svr.gz` 分区、二维 PNG 和概览。
- `textures/`：材质图集、压缩材质映射及来源许可。

查看器：[SowVillage-worldview-web](https://github.com/SowVillage/SowVillage-worldview-web)。它按需读取本仓库文件，不要求同时下载整张地图。

推荐通过 `https://raw.githubusercontent.com/SowVillage/SowVillage-worlddata-sc2-web-public/<commit>/` 读取，并固定完整 commit SHA，让目录、方块索引和材质使用同一版本。

地图保留 398,925 个区块。原存档与本地备份保持完整；受保护中心和已保留建筑范围不变。Mojang 纹理的许可与来源见 `textures/`。
