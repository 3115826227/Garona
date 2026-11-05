# Garona — 企业综合管理平台前端

Garona 是企业综合管理平台的 Web 管理端，与 Anduin 后端配套使用。当前仅完成前端基础工程，尚未接入业务 API。

## 技术栈

- Vue 3 + TypeScript
- Vite — 开发与构建
- Element Plus — UI 组件
- Pinia — 状态管理
- Vue Router — 前端路由
- Axios — HTTP 请求

## 快速开始

建议使用满足当前 Vite 版本要求的 Node.js 环境。

```bash
git clone https://github.com/3115826227/Garona.git
cd Garona
git switch feature_init_project_20261105
npm install
npm run dev
```

## 常用命令

```bash
npm run dev
npm run typecheck
npm run build
npm run preview
```

## 目录说明

```text
src/
├── main.ts            # 应用入口
├── App.vue            # 根组件
├── router/            # 路由
├── stores/            # Pinia 状态
├── services/          # HTTP 请求封装
└── views/             # 页面
```

## 仓库与协作

- 后端：[Anduin](https://github.com/3115826227/Anduin)
- 文档：[Illidan](https://github.com/3115826227/Illidan)
- `master`：生产稳定分支；`develop`：开发主线
- `feature_<description>_<YYYYMMDD>`：需求开发；`hotfix_<description>_<YYYYMMDD>`：紧急修复
- 功能从 `develop` 拉分支，通过 Pull Request 合并回 `develop`。
- Commit 和 PR 标题使用中英文双语，例如：`docs(readme): add project overview | 补充项目介绍`。

## 当前状态

前端基础工程建设中，暂无正式业务页面及后端 API 集成。
