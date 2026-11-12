# 第三方组件

节点程序包含独立 Python 运行环境、cryptography 及其他运行依赖，相关许可证保存在版本目录的 `licenses/` 以及依赖随附说明中。第三方组件保留各自版权与许可证，本项目不将其视为自有代码。

公开安装包不包含 FFmpeg 或 7-Zip 二进制。安装时由参与者的机器直接下载以下上游文件，校验通过后保存到独立工具目录；这些文件按上游自己的许可使用。

| 工具 | 固定版本 | 上游文件 |
| --- | --- | --- |
| FFmpeg / ffprobe | 9.0.2 essentials | [GyanD/codexffmpeg 发布](https://github.com/GyanD/codexffmpeg/releases/tag/9.0.2) |
| 7zr | 7-Zip 26.06 | [ip7z/7zip 发布](https://github.com/ip7z/7zip/releases/tag/26.06) |

SHA256：

```text
ffmpeg-9.0.2-essentials_build.zip
60f467265b1e312373dbcd92200c2618a74850f98d3d078e94296bb3fa2047ba

7zr.exe (26.06)
e80db2dad715a6c5adabe292d31ed54e11f4e9b99ca349827b50573b175891bc
```

下载的 FFmpeg 包含其许可与构建说明，工具目录保留相应副本。[FFmpeg 许可说明](https://ffmpeg.org/legal.html)、[7-Zip 许可说明](https://www.7-zip.org/license.txt)及上游源码与构建说明以维护者发布内容为准。

模型不包含在程序包中。可选分类模型由 MTG/Essentia 提供，下载时会保存 `CC-BY-NC-SA-4.0` 等模型许可信息；请在使用前查看权重的原始许可与 [Essentia 许可说明](https://essentia.upf.edu/licensing_information.html)。
