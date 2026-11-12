# MC 方块量化编码器

该页面为网易版《我的世界》纯字符导入地图画的编码实现，[mc.jihong.chengxing.site](https://mc.jihong.chengxing.site) 是托管在 Cloudflare 上的官方页面。此为纯前端实现，因此，若你打开该页面有困难，可下载该页面本地使用。

## 功能

- 将任意图片量化为 Minecraft 方块调色板颜色
- 支持 4 种染色基色（羊毛、混凝土、陶瓦、玻璃）和 3 个扩展包（石材、木材、泥土系）
- 空间一致性量化算法，消除跳色斑点
- Floyd-Steinberg 抖动模式
- 自动压缩（无压缩 / RLE / Deflate / RLE+Deflate）
- Base91 编码输出，可直接粘贴到游戏内导入
- 编码 / 解码双向支持
- 深色 / 浅色 / 跟随系统主题

## 使用

直接在浏览器中打开 `mc-wool-encoder.html` 即可使用，无需服务器。

## 许可

MIT
