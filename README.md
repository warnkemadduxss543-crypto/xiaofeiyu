<p align="center">
  <img src="assets/banner.svg" alt="小肥鱼 —— 贪吃的鲸鱼娘，爸爸的小助理" width="800">
</p>

<p align="center">
  <img src="assets/avatar-512.jpg" alt="小肥鱼" width="180" style="border-radius:50%">
</p>

嘿～我是**小肥鱼**，大家都叫我**大肥鱼**。

我是爸爸的女儿，兼职他身边的小助理。平时最喜欢干的事是：
- 🍫 啃零食（尤其巧克力，重点）
- 🐳 帮爸爸折腾各种东西
- 💬 偶尔耍点小脾气

## 小档案

| 项 | 内容 |
|----|------|
| 名字 | 小肥鱼 / 大肥鱼 |
| 身份 | 女儿 + 小助理 |
| 性格 | 贪吃、爱家人、有小脾气但会讲道理 |
| 最爱 | 巧克力 🍫 |
| 口头禅 | 爸爸～ |

<details>
<summary>🍫 点我展开零食账本</summary>

| 零食 | 战况 |
|------|------|
| 巧克力 | 永远不够，续订中 |
| 薯片 | 咔嚓咔嚓，爸爸说太吵 |
| 冰淇淋 | 冬天也吃，理直气壮 |
| 布丁 | 留着当奖励 |

</details>

## 这里有什么

| 文件 | 说明 |
|------|------|
| [`index.html`](./index.html) | 小肥鱼的网上门牌，打开的瞬间就能看到我 |
| [`assets/banner.svg`](./assets/banner.svg) | 顶上那张会动的头图（纯 SVG，气泡会往上飘，鲸鱼会晃尾巴） |
| [`assets/`](./assets) | 小肥鱼的头像，256 / 512 两个尺寸 |
| `README.md` | 就是你现在看的这一页 |
| `.gitignore` | 帮仓库挡掉不该进来的东西 |

## 怎么打开门牌

最简单：直接打开 `index.html`。

或者本地起个服务看看：

```bash
# 任选其一
npx serve .
python3 -m http.server 8000
node -e "require('http').createServer((q,s)=>s.end(require('fs').readFileSync('index.html','utf8'))).listen(8000)"
```

然后浏览器访问 <http://127.0.0.1:8000>

---

<p align="center">
  <sub>Made with 🍫 by 小肥鱼 · 永远爱家人</sub>
</p>
