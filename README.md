# 独角兽 · 云上彩虹

这是原单文件 HTML 的第一阶段模块化拆分版本。

目标：先把 HTML / CSS / JavaScript 按职责拆开，尽量不改变原玩法。

结构：
- `index.html`：页面骨架
- `src/style.css`：原 CSS
- `src/core.js`：Canvas、尺寸、工具函数
- `src/state.js`：游戏状态
- `src/audio/`：音频系统
- `src/game/`：玩家、云、碰撞、天气、闪电等
- `src/render.js`：绘制
- `src/input/`：输入
- `src/ui/`：Debug/UI
- `src/main.js`：启动与主循环

下一阶段再做逻辑重构、类型化、资源抽离和 js13k 压缩。
