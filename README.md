# 寸照

<p align="center">
  <img src="images/logo.png" width="128" alt="寸照" />
</p>

<p align="center"><b>离线证件照制作，发丝都清楚。照片不出本机。</b></p>

选规格、导入照片（支持多选与拖入），本机即可完成抠图、单脸校验、裁切与换底，导出 PNG / JPEG。  
不联网、不上传、不依赖 Python 或独立显卡。

## 能做什么

- **201 种规格**：一寸二寸、四六级、教资、社保卡、各国签证等，支持按名称 / 尺寸搜索
- **两种模式**：导入证件照（检测人脸并按证件框裁切）或一键换底
- **批量制作**：可多选、可继续添加；单张失败不影响其余
- **底色自由**：规格预设色 + 自定义颜色，换色不用重跑
- **完全离线**：启动后不访问网络，照片始终留在你的电脑上

## 软件截图

首页浏览热门规格，搜索名称或尺寸后导入照片；制作页可预览标准照、换底并导出。

<p align="center">
  <img src="images/index-1.png" width="860" alt="首页：浏览热门证件照规格" />
</p>
<p align="center"><em>首页：浏览热门规格，导入证件照或一键换底</em></p>

<p align="center">
  <img src="images/index-2.png" width="860" alt="制作页：预览标准照并更换底色" />
</p>
<p align="center"><em>制作页：预览标准照 / 高清照 / 透明底，更换底色后导出</em></p>

<p align="center">
  <img src="images/index-3.png" width="860" alt="搜索规格：按名称查找教师资格证等" />
</p>
<p align="center"><em>搜索规格：输入「教师」即可筛出教资相关尺寸</em></p>

## 下载

当前版本 **[0.1.0](https://github.com/yuanmomoya/cun-zhao-package/releases/tag/v0.1.0)**，请到 [Releases](https://github.com/yuanmomoya/cun-zhao-package/releases) 下载对应平台安装包。

| 平台 | 安装包 | 状态 |
|---|---|---|
| macOS 12+（Apple Silicon） | [`cun-zhao_0.1.0_aarch64.dmg`](https://github.com/yuanmomoya/cun-zhao-package/releases/download/v0.1.0/cun-zhao_0.1.0_aarch64.dmg) | 已发布 · 未签名：首次请右键 →「打开」 |
| Windows 10/11 x64 | [`cun-zhao_0.1.0_x64-setup.exe`](https://github.com/yuanmomoya/cun-zhao-package/releases/download/v0.1.0/cun-zhao_0.1.0_x64-setup.exe) | 已发布 · 未签名：SmartScreen 选「仍要运行」；需 WebView2（Win11 自带） |

建议 64 位系统、内存 8GB 以上、预留约 300MB 磁盘空间。macOS 需 Apple Silicon；Windows 为 x64。

## 0.1.0 更新说明

首个对外版本，面向日常办证、考试报名、签证材料。

- 本机完成抠图、单脸校验、裁切与换底，照片不出本机
- 内置 201 种证件照规格，支持搜索与批量制作
- 导出 PNG / JPEG；JPEG 会按规格体积上限自动压缩
- 本次同时提供 macOS（Apple Silicon）与 Windows 10/11 x64 安装包

## 安装注意

1. 从 [Releases](https://github.com/yuanmomoya/cun-zhao-package/releases) 下载，按系统选择文件。
2. **macOS**：若提示无法打开，在访达中右键安装包 →「打开」。
3. **Windows**：若 SmartScreen 拦截，选「更多信息」→「仍要运行」；Win10 需已安装 [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/)。
4. 安装到当前用户即可，一般不需要管理员权限。

部分考试报名明确要求「不得修图」，请以报考机构为准。

## 关注作者

<p align="center">
  <img src="images/wx-logo.png" width="280" alt="程序员小袁 微信公众号：扫码关注" />
</p>

<p align="center">微信扫描上方二维码，关注公众号 <b>程序员小袁</b><br/>编程干货 · 开发笔记 · AI 工具</p>
