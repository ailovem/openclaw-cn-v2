# OpenClaw 中国社区 v2

## 新项目，完全独立 ✅

**位置**: `01_Projects/openclaw-cn-v2`

---

## 部署步骤

### 1. GitHub 创建新仓库

1. 打开: https://github.com/new
2. 仓库名: `openclaw-cn-v2`
3. 设为 **Private** (或 Public)
4. **不要**勾选 "Add a README file"
5. 点击 "Create repository"

### 2. 本地推送到新仓库

```bash
cd C:\Users\dongd\Desktop\01_Projects\openclaw-cn-v2
git init
git add .
git commit -m "OpenClaw v2 - SPA version"
git remote add origin https://github.com/ailovem/openclaw-cn-v2.git
git push -u origin master
```

### 3. 启用 GitHub Pages

1. 打开: https://github.com/ailovem/openclaw-cn-v2/settings/pages
2. Source: 选择 **main** 分支
3. 保存

### 4. 配置新域名

在域名服务商后台添加:
- 新域名: 例如 `v2.openclaw.ailovem.com`
- 类型: CNAME
- 值: `ailovem.github.io`

然后在 GitHub Pages 设置中填写自定义域名。

---

## 项目特点

- ✅ SPA 单页应用
- ✅ 角色切换系统
- ✅ 无刷新跳转
- ✅ 统一导航

---

## 对比

| 项目 | 仓库 | 域名 |
|------|------|------|
| 旧版 | openclaw-cn | openclaw.ailovem.com |
| 新版 | openclaw-cn-v2 | **新域名** |
