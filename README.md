# BFG 电量校准

这是 BFG 电量校准的 Android 工程，主要用于读取车辆信息和进行电量参数校准。它是第三方工具，与九号官方没有关系，请只在自己的车辆或获得授权的车辆上使用。

- 应用名称：BFG电量校准
- 应用 ID：`com.bfgtools.calibration.imported`
- 最低 Android：12（API 31）
- 目标 Android：17（API 37）
- 
## 目录说明

- `app/`：应用代码、界面、蓝牙通信和测试。
- `app/src/main/assets/bfg-calibration-flow.html`：主要界面文件。
- `Bcore/`、`black-reflection/`、`compiler/`、`blackbox-gallery-stub/`：虚拟环境相关模块。
- `NOTICE.md`：来源和署名说明。
- `docs/`：上游归属和发布步骤。

## 用 Android Studio 构建

1. 用 Android Studio 打开本目录。
2. 安装 Android SDK、NDK 和 JDK 21。
