# Tauri-Gitee Desktop App
[English](readme.md)| [中文](readme_cn.md)

[![GitHub stars](https://img.shields.io/github/stars/litongjava/tauri-gitee)](https://github.com/litongjava/tauri-gitee/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/litongjava/tauri-gitee)](https://github.com/litongjava/tauri-gitee/issues)

Tauri-Gitee 是一个使用 [Tauri](https://tauri.studio/) 和 Rust 语言封装的 http://gitee.com 的桌面应用程序。现在您可以在桌面上直接访问 Gitee，无需打开浏览器。

![1](readme_files/1.png)

## 特点

- 快速、轻量级
- 使用 Rust 语言提供高性能和安全性
- 与桌面环境无缝集成
- 使用 Tauri 提供的安全性和稳定性

## 开始使用

### 下载与安装

**从 Release 下载**：您可以直接访问 [Releases 页面](https://github.com/litongjava/tauri-gitee/releases) 下载最新版本的应用程序。

### 自行构建
1. **自行构建**：
   - 克隆此仓库：
     ```bash
     git clone https://github.com/litongjava/tauri-gitee.git
     ```
   - 进入项目目录：
     ```bash
     cd tauri-gitee
     ```
   - 使用 Cargo 安装依赖并运行：
     ```bash
     # 安装依赖
     cargo build

     # 运行应用程序
     cargo run
     ```

2. **打包应用**

```bash
cargo tauri build
```

## 贡献

我们欢迎任何形式的贡献！无论是提交 bug、提出建议还是请求新功能，我们都非常感谢。

## 许可证

此项目使用 MIT 许可证。详细信息请查看 [LICENSE](./LICENSE) 文件。
