# GoBypass

**GoBypass** 是一款基于 Go 语言开发的免杀测试工具。

> ⚠️ 本项目仅用于学习、研究及合法授权的测试场景，请勿用于任何非法用途。

---

## 🛠️ 安装与准备

1. **环境要求**：
   - Windows 操作系统。
   - 安装 Go 语言环境。
2. **下载编译版本**： 从 Releases 页面获取最新的 `GoBypass.exe`

## 📖 使用指南

### 快速开始

将生成的测试载荷（`.bin` 文件）与 `GoBypass.exe` 置于同一目录下，打开终端运行：

```text
默认模式（默认针对 360 环境进行行为模拟）
.\GoBypass.exe -p test.bin

指定特定防护环境
.\GoBypass.exe -p test.bin -t hr
```
