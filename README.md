# system-disassembl-solution

仓库用于沉淀与「系统拆解 / 上层方案」相关的可分享交付物。

## 平台登录与导航交互（HTML 方案 v1.0）

- 文件路径：`docs/upper-level-architecture-solution/platform_login_navigation_v1.html`

### 外部可访问 · 浏览器渲染链接

**方式 A — 无需配置（第三方预览，适合临时分享）**

把 Raw 地址交给 [htmlpreview.github.io](https://htmlpreview.github.io/) 渲染（链接较长，请整段复制）：

```text
https://htmlpreview.github.io/?https://raw.githubusercontent.com/beynawoo-code/system-disassembl-solution/main/docs/upper-level-architecture-solution/platform_login_navigation_v1.html
```

固定版本（替换为你的提交 SHA 即可永久固化）：  
`https://htmlpreview.github.io/?https://raw.githubusercontent.com/beynawoo-code/system-disassembl-solution/<SHA>/docs/upper-level-architecture-solution/platform_login_navigation_v1.html`

**方式 B — GitHub Pages（官方托管，推荐长期使用）**

1. 打开仓库 **Settings → Pages**。  
2. **Build and deployment**：Source 选 **Deploy from a branch**。  
3. Branch 选 **`main`**，文件夹选 **`/docs`**，保存。  
4. 等待几分钟后访问（用户名与仓库名以你的为准）：

- 入口（自动跳到方案页）：`https://beynawoo-code.github.io/system-disassembl-solution/`  
- 方案正文：`https://beynawoo-code.github.io/system-disassembl-solution/upper-level-architecture-solution/platform_login_navigation_v1.html`

本仓库已在 `docs/` 下包含 `.nojekyll` 与 `index.html` 跳转，便于 Pages 直接托管静态 HTML。

正式对外引用时，建议按团队 SOP 使用**带 commit SHA 的永久链接**（见主工程 `docs/guides/github-外部链接生成-sop.md`）。

