# Angela Sun: Four Projects, One Question

A single page that introduces four projects in the order they were made:

1. Leave1% (July 2026): https://leave1-percent.vercel.app/
2. Where Should AI Stop? (August 2026): https://where-should-ai-stop.vercel.app/
3. Into the Stars (September 2026, in development): https://angelasun-forward.vercel.app/into-the-stars
4. MoodOwn (November 2026): https://moodown.vercel.app/

Plain HTML, CSS and JavaScript, with an English and Chinese switch. No build step. Vercel deploys each push to this repository.

## Files

- `index.html`: the main page with all four projects
- `into-the-stars/index.html`: the info page for Into the Stars
- `into-the-stars/img/`: art, screenshots and game assets for that page
- `favicon.svg`, `vercel.json`: site icon and Vercel settings

## Into the Stars page

I am independently designing Into the Stars, and all of its core gameplay mechanics are my own. I first built it in Godot 4.7.2, with AI-assisted coding throughout. The current Ten Dreams private alpha is implemented in HTML and JavaScript for browser-based playtesting, and the full game is aiming for a public release in 2027.

- Ten Dreams private alpha: https://into-the-stars-game-alpha.vercel.app/
- The alpha link lives in one place: `ALPHA_URL` near the end of `into-the-stars/index.html`. Leave it empty and both cloud buttons read "Ten Dreams alpha opening soon".
- Images are the game's own art and assets. Screenshots come in an English and a Chinese version, and the page swaps them with the language switch.
- The star lines and floating assets turn still for visitors who set their device to reduce motion.

## 入梦星空页面

《入梦星空》由我独立设计，所有核心玩法与游戏机制均为原创。游戏最初在 Godot 4.7.2 中开发，全程借助 AI 辅助编程。目前开放的「十梦」邀请制内测是用 HTML/JavaScript 实现的浏览器试玩版，完整版目标是 2027 年正式上线。

- 十梦邀请制内测：https://into-the-stars-game-alpha.vercel.app/
- 内测链接只写在一处：`into-the-stars/index.html` 末尾的 `ALPHA_URL`。留空时，两个云朵按钮会显示“十梦内测即将开放”。
