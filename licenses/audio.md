# 音频来源与授权

逐首核对日期：2026-11-15。以下曲目页均明确链接到 [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)。下载文件只选对应曲目页中的音频附件；记录包含文件 URL、SHA-256 和原始时长，见 `tools/audio/sources/*.json`。

| 原曲 | 作者 | 原始文件 | 本工程文件 |
| --- | --- | --- | --- |
| [Asianoriental1](https://opengameart.org/content/asianoriental1) | Tozan | asianoriental1_0.ogg | music/asianoriental1.ogg |
| [Shangri River](https://opengameart.org/content/shangri-river) | Tozan | Shangririver.ogg | music/shangri-river.ogg |
| [Oriental8](https://opengameart.org/content/oriental8) | Tozan | orient8_0.ogg | music/oriental8.ogg |
| [Orien](https://opengameart.org/content/orien) | Tozan | orien_2.ogg | music/orien.ogg |
| [Oriented](https://opengameart.org/content/oriented) | yd | Oriented_0.ogg | music/oriented.ogg |
| [Swordfight](https://opengameart.org/content/swordfight) | Kistol | Swordfight_0.ogg | music/swordfight.ogg |

加工：裁剪静音、循环接缝交叠、响度统一和 Ogg 重新编码；不改变作者署名或声称这些曲目为本项目原创。没有使用 Pixabay 内容许可曲目。

`sfx/` 与 `ambience/` 中新增文件由本次任务中的确定性合成脚本制作，没有使用第三方录音或付费音源。可复现源文件为 `tools/audio/generate_sfx.py`。这些文件不冒用上述音乐作者的署名，也不将已有工程素材重新声明为 CC0。

以下已有音效沿用项目原文件：`combat/wooden_sword_impact.wav`、`assets/enemies/wolf_bei/roar.wav`、`assets/enemies/wolf_bei/landing.wav`。本次仅增加总线路由与试听入口，不改变其既有来源记录。
