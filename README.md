# 🎯 数字炸弹游戏 - 部署说明

## 🌐 当前访问地址

**临时公网 URL**: https://major-eyes-peel.loca.lt

> ⚠️ 注意：这是临时地址，服务重启后会变化。如需永久地址，请参考下方永久部署方案。

---

## 📁 游戏文件位置

```
/root/.openclaw/workspace/number-bomb-game/index.html
```

---

## 🚀 永久部署方案

### 方案一：GitHub Pages（推荐，免费永久）

1. 创建 GitHub 仓库（如 `number-bomb-game`）
2. 将 `index.html` 上传到仓库
3. 进入仓库 Settings → Pages
4. 选择 `main` 分支，保存
5. 获得永久地址：`https://你的用户名.github.io/number-bomb-game/`

### 方案二：Vercel（免费永久）

1. 访问 https://vercel.com
2. 登录 GitHub 账号
3. Import 你的项目
4. 自动部署，获得 `https://xxx.vercel.app` 地址

### 方案三：Netlify（免费永久）

1. 访问 https://netlify.com
2. 拖拽 `index.html` 到部署区域
3. 获得 `https://xxx.netlify.app` 地址

---

## 🎮 游戏规则

1. 系统随机生成 1-100 之间的数字作为"炸弹"
2. 输入你的猜测，系统会提示大了还是小了
3. 每次猜测后，范围会缩小
4. 猜中炸弹数字即获胜！
5. 记录你的猜浏次数，挑战最佳成绩

---

## 📊 功能特点

- ✅ 响应式设计，手机电脑都能玩
- ✅ 实时范围提示
- ✅ 游戏统计（次数、最佳记录、平均次数）
- ✅ 精美 UI 界面
- ✅ 回车键快速提交

---

## 🛠️ 本地运行

```bash
cd /root/.openclaw/workspace/number-bomb-game
serve -p 3000
# 访问 http://localhost:3000
```

---

*游戏由 AI 助手生成 · 祝你玩得开心！*
