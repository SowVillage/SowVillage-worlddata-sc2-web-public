# SowVillage-worlddata-sc2-web-public

老母猪村生存服二周目的最终静态地图数据。仅包含可直接调用的三维分区、二维瓦片、压缩索引和配套材质；解析代码、原存档及本地审计资料不上传。

- `world/manifest.json.gz`：地图目录；`world/palette.json.gz`：方块索引。
- `world/{overworld,nether,end}/`：三维 `.svr.gz` 分区、二维 PNG 和概览。
- `world/{overworld,nether,end}/block-entities/`：按三维分区加载的告示牌文字、旗帜图案、床颜色、盆栽、头颅、物品展示框、箱子配对、讲台书本、炼药锅颜色与酿造台瓶子视觉数据；展示框中的地图像素在 `world/maps/`。
- `world/fonts/`：告示牌文字所需的中文像素字体子集及许可。
- `textures/`：材质图集、压缩材质映射及来源许可。

在线查看器：[老母猪村世界地图](https://worldview.bugmc.com/)。公开页面按需读取本仓库文件，不要求同时下载整张地图；源码保存在私有的 `SowVillage-worldview-web` 仓库。

推荐通过 `https://raw.githubusercontent.com/SowVillage/SowVillage-worlddata-sc2-web-public/<commit>/` 读取，并固定完整 commit SHA，让目录、方块索引和材质使用同一版本。

地图保留 398,925 个区块。原存档与本地备份保持完整；受保护中心和已保留建筑范围不变。Mojang 纹理的许可与来源见 `textures/`。

方块实体文件仅保留绘制所需的坐标、方块状态与公开视觉内容，不包含容器库存、玩家标识、归属记录、命令或原始 NBT。
