# Gitlawb Opengateway — 自动配置工具

一键配置 OpenClaude CLI 网关的工具。

## 使用方法

### Windows
双击 `fix-opengateway-auth.exe` 或在终端中运行：
```
fix-opengateway-auth.exe
```

### macOS
```bash
chmod +x fix-opengateway-auth-macos
./fix-opengateway-auth-macos
```

## 功能说明
1. 创建包含 API 密钥的配置文件
2. 在 OpenClaude 配置中注册提供商
3. 修复 CLI 的认证头以兼容网关

## 系统要求
- 全局安装 [OpenClaude](https://www.npmjs.com/package/@gitlawb/openclaude)
