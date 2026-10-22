# 人物海报 / 双墨书法
CONCEPT: 以人物照片和书法笑点构成一张可滑动的中文人物海报。
AUDIENCE: 浏览、分享梁文锋网络梗的中文用户。
DIRECTION: Neo-Vintage / Print Revival，中文双墨海报分支。
BASELINE: 原页面人物占据中心，调侃仅 12px，灰底和灰字对比低。
KEEP: 五张原图、年龄映射、滑杆、投票及历史回看逻辑。
NEVER: 霓虹、渐变文字、粒子、持续晃动、额外营销卡片。
TYPE: Ma Shan Zheng 400，Google Fonts，随站点托管的 TTF 字符子集。
TEXT: Microsoft YaHei / PingFang SC / sans-serif；数字使用 Consolas。
DISPLAY: 铺垫 26–40px，笑点 44–76px，正文 14px；手机笑点 34–42px。
TRACKING: 书法 0em，正文 0em，英文标签 0.08em。
LEADING: 书法 1.2，正文 1.6；CJK 断行按标点，text-wrap: balance。
PAPER: #eee9df；INK: #26221d；SECONDARY: #675d53。
ACCENT: #ae3027，来自附图红领巾和原页面朱红，作字色与滑杆。
DARK: #20211f；DARK-INK: #f4eee2；DARK-SECONDARY: #bdb4a5。
DARK-ACCENT: #f0bc78，来自原页面高阶段的金色，保留其阶段辨识。
CONTRAST: 每个阶段的正文 >=4.5:1，书法大字 >=3:1。
GEOMETRY: 直角照片框、2px 刻线、圆形滑杆；文字仅 2px 实色套印阴影。
SPACE: 8 / 16 / 24 / 40 / 64；桌面列比例 0.9:1.3，列间距 64px。
GRID: 桌面人物在左、书法在右，控制区横跨两列；900px 以下单列。
PHOTO: 桌面最大 420px；手机 min(52vw,27svh,240px)，正方形。
FOCAL: 笑点是最大、最醒目的文字；页面标题退为 30–40px。
TENSION: 笑点偏转 -1.5deg，底部印痕越出文字基线。
SIGNATURE: 朱红墨迹重复于标题下划线、笑点下印痕、滑杆。
EXCEPTION: 最后两阶段整体反色，其余几何不变。
MOTION: 180ms ease-out，只有用户交互触发；reduced-motion 下关闭。
STATES: 保留加载、禁用、键盘焦点、历史、投票失败与冷却行为。
MATERIAL: 低对比度纸纹、实色套印，照片不做生成式修改。
COPY: 原创调侃，铺垫和笑点分层；保留完整可读文本。
RUBRIC: 先看见笑点；五阶段不重叠；手机不横溢；滑杆无需寻找。
REFERENCE: https://design.google/library/choosing-web-fonts-beginners-guide
REFERENCE: https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow
REFERENCE: https://developer.mozilla.org/en-US/docs/Web/CSS/clamp

QA: 1440×1000 / 1280×720 / 390×844 实际浏览器截图复核；五阶段无横溢，照片、笑点、滑杆无重叠。
CRITIQUE: 首轮放大时间线触控范围后发现手机右侧溢出 5px；第二轮将时间线向内移 14px，28 项交互检查全部通过。
CONTRAST-VERIFIED: 浅色正文 13.06、次要文字 5.31、书法 5.34；深色正文 13.99、次要文字 7.88、书法 9.37（以脚本实测值为准）。
FONT-QA: 本地字体加载通过，121KB，字体许可随静态构建分发。
