
## ⚡ 简介

Ohmyweb是基于Ohmydns的工具对应的前端展示界面的封装，主要用于IPv6 DNS测绘结果的展示，基于 Vue3、TypeScript、Element Plus、Pinia 和 Vite 等主流技术

- Vue Cli 5.x 版: [v3-admin](https://github.com/un-pany/v3-admin)
- Electron 桌面版: [v3-electron-vite](https://github.com/un-pany/v3-electron-vite)

## 📚 文档

- 中文文档：[链接](https://juejin.cn/post/7089377403717287972)
- 手摸手教程：[链接](https://juejin.cn/column/7207659644487139387)



## 🚀 开发

```bash
# 配置
1. 一键安装 .vscode 目录中推荐的插件
2. node 版本 18.x 或 20+
3. pnpm 版本 8.x 或最新版

# 克隆项目
git clone https://github.com/un-pany/v3-admin-vite.git

# 进入项目目录
cd v3-admin-vite

# 安装依赖
pnpm i

# 启动服务
pnpm dev
```

## ✔️ 预览

```bash
# 预览预发布环境
pnpm preview:stage

# 预览正式环境
pnpm preview:prod
```

## 📦️ 多环境打包

```bash
# 构建预发布环境
pnpm build:stage

# 构建正式环境
pnpm build:prod
```

## 🔧 代码检查

```bash
# 代码格式化
pnpm lint

# 单元测试
pnpm test
```