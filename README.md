# Vela 更新通道

这个仓库**只做发布**：macOS App 的 DMG 安装包与 Sparkle 自动更新源（appcast.xml）。

**不含任何源码** —— 源码在私有仓库 yeyebang/Vela。

## 自动更新

Vela App 内置 Sparkle，更新源地址：

```
https://raw.githubusercontent.com/yeyebang/Vela-Updates/main/appcast.xml
```

新版本发布流程（维护者）：源码仓 `vela/scripts/publish-update.sh <DMG 路径>`，
自动完成 EdDSA 签名 → 更新 appcast → 挂 GitHub Release。
