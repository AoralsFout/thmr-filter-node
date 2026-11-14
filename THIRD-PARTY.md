# 第三方组件

第三方组件保留各自版权与许可。便携程序和离线模型资源分别附带 `licenses/` 及依赖随附说明，使用前请查看对应组件的许可限制。

## 基础便携包

基础便携包包含独立 Python 运行环境、cryptography 等运行依赖，以及 FFmpeg/ffprobe 与 7-Zip。运行时不要求参与者另行下载基础工具。

本次使用 FFmpeg 8.1 essentials Windows 构建，来源为 [Gyan.dev](https://www.gyan.dev/ffmpeg/builds/)，适用 GPL v3。随包 `tools/licenses/FFmpeg-README.txt` 保留构建配置与[对应 FFmpeg 源码版本](https://github.com/FFmpeg/FFmpeg/commit/9047fa1b08)，许可文本位于 `tools/licenses/FFmpeg-LICENSE.txt`。更多信息见 [FFmpeg 许可说明](https://ffmpeg.org/legal.html)。

7-Zip 26.06 的许可、版权和使用说明保存在 `tools/licenses/7-Zip-License.txt` 和 `7-Zip-README.txt`。源码与发布材料见 [7-Zip 上游](https://github.com/ip7z/7zip/releases/tag/26.06)，另见 [7-Zip 许可说明](https://www.7-zip.org/license.txt)。

## CPU/CUDA 模型资源

模型权重和完整模型环境以独立 CPU/CUDA 资源发行，包含受管 CPython、推理依赖及其许可。讲话模型来源与转换校验信息随资源保留；CUDA 讲话使用已经转换并校验的 ONNX 权重，不要求参与者自行转换。

分类权重来自 MTG/Essentia，适用 `CC-BY-NC-SA-4.0` 等独立许可；使用前查看资源内权重来源与许可信息，以及 [Essentia 许可说明](https://essentia.upf.edu/licensing_information.html)。随包提供不改变原许可，也不授予商业使用权限。

CUDA 资源不包含显卡驱动。NVIDIA 运行库保留各自许可，程序不会代替用户安装或升级驱动。
