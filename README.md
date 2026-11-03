# Spatial Apps

MindSoul 团队的空间应用与脑机接口（BCI）开源协作入口，集中管理应用源码、交互实验、BCI 接入示例与开发文档。

## 平台规划

| 平台 | 定位 | 当前状态 |
| --- | --- | --- |
| PICO OS 6 | 首批目标平台 | 待上传项目并验证 |
| Android XR | 首批目标平台 | 待上传项目并验证 |
| visionOS | 首批目标平台 | 待上传项目并验证 |
| Meta Horizon OS | 未来支持 | 规划中 |
| Snap Spectacles（Snap OS） | 未来支持 | 规划中 |

平台列表表示开发方向，具体兼容性以各应用 README 中的设备、系统版本和验证记录为准。

## 项目目录

- `apps/`：每个空间应用一个子目录，可在应用内按平台拆分代码。
- `bci/`：脑机设备适配、信号接口、模拟数据与交互示例。
- `docs/`：团队开发、构建、设备测试和发布文档。

## 上传与协作

1. 在 `apps/<app-name>/` 创建应用目录并提交源码。
2. 应用 README 说明用途、负责人、支持平台、构建步骤、BCI 设备/协议、测试结果及许可证。
3. 通过分支和 Pull Request 提交，注明本次变更及验证方式。
4. 安装包通过 GitHub Releases 发布，记录版本、平台与安装方法。

目前仓库用于初始化协作入口，尚未包含已发布应用。每个上传项目应明确其开源许可证及第三方资产许可。

## 平台官方资料

- [PICO OS 6](https://developer.picoxr.com/document/discover/faqs-for-project-swan-and-pico-os-6/)
- [Android XR](https://developer.android.com/develop/xr)
- [visionOS](https://developer.apple.com/visionos/)
- [Meta Horizon OS](https://developers.meta.com/horizon/)
- [Snap Spectacles](https://developers.snap.com/spectacles/home)
