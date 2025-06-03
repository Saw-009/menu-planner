# 智能菜单计划助手

一款帮助您规划每日菜单的桌面应用程序。

## 功能特点

- 🍳 菜品库管理
- 📅 智能生成菜单计划
- 📝 材料清单生成
- 💾 数据导入导出
- 🏷️ 分类和标签系统

## 下载使用

访问 [Releases](../../releases) 页面下载最新版本：

- Windows: `智能菜单助手-Setup.exe` (安装版) 或 `智能菜单助手.exe` (便携版)
- macOS: `智能菜单助手.dmg`
- Linux: `智能菜单助手.AppImage` 或 `智能菜单助手.deb`

## 开发指南

### 环境要求

- Node.js 18+
- npm 8+

### 本地开发

1. 克隆仓库：
```bash
git clone https://github.com/Saw-009/menu-planner.git
cd menu-planner
```

2. 安装依赖：
```bash
npm install
```

3. 启动开发服务器：
```bash
npm run electron:dev
```

### 构建应用

```bash
# Windows
npm run electron:build:win

# macOS
npm run electron:build:mac

# Linux
npm run electron:build:linux
```

## 许可证

MIT

## 贡献指南

欢迎提交 Issue 和 Pull Request！
