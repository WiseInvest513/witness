# WiseWitness - 见证开户咨询服务

一站式全球银行账户开户咨询平台。

## 🚀 Vercel 部署指南

### 前置要求
- GitHub 账号
- Vercel 账号（免费注册）
- 高德地图 API Key

### 部署步骤

#### 1️⃣ 初始化 Git 仓库
```bash
cd /Users/balala/Persona/Blog/witness
git init
git add .
git commit -m "Initial commit: WiseWitness deployment"
```

#### 2️⃣ 上传到 GitHub
```bash
# 在 GitHub 创建新仓库 wiseinvest-witness
# 然后运行：

git remote add origin https://github.com/YOUR_USERNAME/wiseinvest-witness.git
git branch -M main
git push -u origin main
```

#### 3️⃣ 在 Vercel 上部署
1. 访问 [vercel.com](https://vercel.com)
2. 使用 GitHub 账号登录
3. 点击 "New Project"
4. 选择你的 `wiseinvest-witness` 仓库
5. 点击 "Import"
6. 在"Environment Variables"中添加：
   - **Key**: `AMAP_KEY`
   - **Value**: `a6f79a420f94bba806d204ff2df46273`
7. 点击 "Deploy"

#### 4️⃣ 域名配置（可选）
在 Vercel 项目设置中的 "Domains" 添加你的自定义域名

### 📋 项目信息

| 项目 | 值 |
|------|-----|
| **名称** | WiseWitness |
| **描述** | 见证开户咨询服务 - 足不出户，开通全球银行账户 |
| **高德 API Key** | `a6f79a420f94bba806d204ff2df46273` |
| **微信号** | `WiseInvest513` |
| **推特** | https://x.com/WiseInvest513 |
| **YouTube** | https://www.youtube.com/@WiseInvest513 |
| **投资主站** | https://www.wise-invest.org/ |

### 🔧 配置文件
- **vercel.json** - Vercel 部署配置
- **.gitignore** - Git 忽略文件列表
- **index.html** - 主入口文件

### ⚙️ 技术栈
- 纯 HTML/CSS/JavaScript（无后端依赖）
- 高德地图 API 2.0（地图展示）
- 响应式设计（支持所有设备）

### 🌐 支持浏览器
- Chrome (最新)
- Firefox (最新)
- Safari (最新)
- Edge (最新)

### 📝 部署后检查清单
- [ ] 页面正常加载
- [ ] 导航栏浮动效果正常
- [ ] 地图能正常显示（Amap API Key 已配置）
- [ ] 微信号可复制
- [ ] 响应式设计在手机上正常显示
- [ ] 所有社交媒体链接有效

### 🚨 故障排除

**地图不显示？**
- 检查 Amap API Key 是否正确配置在环境变量中
- 访问 [高德地图控制台](https://console.amap.com/) 确认 Key 已启用

**样式加载有问题？**
- 清除浏览器缓存（Ctrl+Shift+Delete）
- 强制刷新（Ctrl+Shift+R）

**域名无法访问？**
- 等待 DNS 传播（通常 24 小时）
- 检查域名 DNS 记录是否指向 Vercel

### 📞 支持
- 微信: WiseInvest513
- 推特: @WiseInvest513
- 投资主站: https://www.wise-invest.org/

---

**部署时间**: 2026-03-25
**版本**: 1.0.0
