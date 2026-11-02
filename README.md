# 朝代时期对比

同样建国 77 年，各朝代在忙什么——从时间轴上理解王朝更替

> 点子来源：Obsidian《人生可视化 / 朝代时期对比》 · 同系列仓库参考 [life-grid](https://github.com/palmyer/life-grid)

## 功能

- 拉链图：各朝代起点对齐，白色游标 = 建国 77 年
- 建国第 77 年各朝对照（唐武周 / 元末世 / 明土木堡前夜…）
- 中外同轴锚点：秦统一 × 罗马布匿战争、唐建 × 阿拉伯前夜…

## 运行

纯静态零依赖，任选其一：

```bash
cd dynasty-timeline
python -m http.server 8740
```

- 网页版：<http://127.0.0.1:8740/>
- 手机壳预览：<http://127.0.0.1:8740/preview.html>（life-grid 同款）

或直接双击 `index.html`。

## 设计

- iOS 暗色风格：纯黑背景、#1C1C1E 分组卡片、SF 系统色板
- 选择一律使用 iOS 风格底部滚轮（`shared/wheel.js`）
- 数据存于浏览器 localStorage（`lv-` 前缀），不上传任何服务器
- 生日 / 预期寿命与同系列工具共享同一份配置
