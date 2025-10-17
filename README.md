# solitude.github.io
# Solitude Daily

一个极简的「日常分享」静态页面——  
写几句话、贴一张图，数据保存在浏览器本地，刷新不丢失。

---

## 一键体验
1. 克隆或下载本仓库
2. 双击 `index.html` 即可本地运行  
   （或访问 [https://solitude669.github.io](https://solitude669.github.io) 在线查看）

---

## 功能清单
✅ 纯前端，零依赖  
✅ 响应式布局，手机/电脑自适应  
✅ 发文字 + 本地图片预览（base64）  
✅ 删除单条动态  
✅ 数据持久化：localStorage（仅当前设备可见）

---

## 目录结构
solitude.github.io
├── index.html   ← 单页源码（含 HTML/CSS/JS）
└── README.md    ← 本项目说明

---

## 二次开发提示
| 想做的事 | 快速入口 |
|---|---|
| 改颜色/字体 | 编辑 `<style>` 里的 `:root` 变量 |
| 加“点赞” | 给对象再加 `likes` 字段，渲染 ♥ 图标 |
| 加“时间排序” | 已在 `render()` 默认 `unshift` 倒序 |
| 改成共享版 | 把 `publish()` 换成 POST 到后端 API 即可 |

---

## 浏览器支持
Chrome / Edge / Firefox / Safari  
IE11 需额外补 `localStorage` polyfill（未测）

---

## License
MIT — 随便改、随便用，保留原作者信息即可。
