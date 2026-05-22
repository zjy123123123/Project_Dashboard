# 📊 综合运营看板

## 部署到 GitHub Pages（免费）

### 步骤

**1. 创建 GitHub 仓库**
- 登录 [github.com](https://github.com)
- 点击右上角 **+** → **New repository**
- 仓库名随意（如 `dashboard`），设为 **Public**
- 勾选 **Add a README file**，点击 **Create repository**

**2. 上传文件**
- 进入刚创建的仓库
- 点击 **Add file** → **Upload files**
- 把 `index.html` 和 `echarts.min.js` 拖进去
- 点击 **Commit changes**

**3. 开启 GitHub Pages**
- 进入仓库 **Settings** → 左侧 **Pages**
- **Source** 选择 **Deploy from a branch**
- **Branch** 选择 `main`，目录选 `/ (root)`
- 点击 **Save**

**4. 访问**
- 等待约 1-2 分钟
- 访问地址：`https://你的用户名.github.io/仓库名/`
- 例如：`https://zjy123123123.github.io/Project_Dashboard/`

---

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 看板主页面 |
| `echarts.min.js` | 图表库（本地依赖，无需网络） |

> 两个文件必须放在同一目录下，HTML 中通过相对路径引用 ECharts。

## 注意事项
- 此看板使用模拟数据，接入真实 Excel 数据后需替换数据源
- 所有依赖已本地化，部署后任何人在任何网络环境下均可正常访问
