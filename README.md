# USB-Master-Pro

更新发布通道：更新清单 + Windows x64 下载包（USB-Master-Pro）。

- 当前版本：**1.0.0.2**（build 2）
- 最近更新：修复USB设备打开失败时误显示连接成功的问题；Release版本错误提示可见；传输可取消且重试有上限；设置重启后保持；新增自动更新检查与一键升级。

## 下载

| 用途 | 文件 |
|---|---|
| 便携版 / 自动更新载荷 | [USB-Master-Pro-1.0.0.2-win-x64.zip](https://github.com/xmuhl-tools/USB-Master-Pro-updates/releases/download/v1.0.0.2/USB-Master-Pro-1.0.0.2-win-x64.zip) |

## 校验（sha256）

```text
USB-Master-Pro-1.0.0.2-win-x64.zip
  5a4d0faf56e862a2318c8afd5ae568312353591b59b34262fdd40b4d476ee4ad
```

## 自动更新

程序启动时会读取本仓库的更新清单 [`update.json`](update.json)（镜像通道见清单内 `mirrors`），
按 build 号比较；发现新版本时提示下载，校验 sha256 后自动替换并重启。手动检查入口在程序主界面。

---
本文件由发布流程自动生成/更新（portable-app-release 技能，2026-09-18），请勿手工改动。
