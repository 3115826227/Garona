# Garona

Garona 是企业管理平台的前端服务，对应 Go 后端仓库 [Anduin](https://github.com/3115826227/Anduin)。

## 技术栈

Vue 3 + TypeScript + Vite + Element Plus + Pinia + Vue Router + Axios。

## 本地开发

建议使用 Node.js 20 LTS。

```bash
npm install
npm run dev
```

默认访问 http://localhost:5173。

```bash
npm run typecheck
npm run build
```

API 基础地址通过 `VITE_API_BASE_URL` 配置，参见 `.env.example`。当前尚未接入业务 API。

## Git 分支规范

- `master`：线上稳定分支
- `develop`：开发主线
- `feature_<需求内容>_<YYYYMMDD>`：需求开发分支
- `hotfix_<修复内容>_<YYYYMMDD>`：线上紧急修复分支

Commit 和 PR 标题使用中英文双语，例如：
`feat(init): initialize Vue project | 初始化 Vue 前端项目`。
