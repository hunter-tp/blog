---
draft: false
title: 手机 vibe coding 实践
slug: "vibe-coding"
tags:
  - ai
  - vibe-coding
categories:
  - 未分类
date: '2026-05-27T09:04:50+08:00'
---

人到中年，属于自己的时间越来越少。

但 vibe coding 流行之后，想法反而越来越多了。开发可以完全交给 AI，以前不敢想的东西，现在每个都能低成本落地。这种创造的快感让人上头，根本停不下来。

时间嘛，挤挤总是有的。带娃、外出、等个车，这些碎片时间加起来其实不少。vibe coding 本来就只需要下达指令，正好适合这种场景。

目前用得最顺手的是 **Remote Control**。Claude Code 和 Codex 现在都支持这个功能，电脑端跑任务，手机端看进度、批准操作、补充指令。体验非常自然，就是正常用 agent，只是换了个屏幕。

在 Remote Control 还没普及之前，我主要用的是 **Tailscale + Termius + tmux** 这套组合。Mac 上开好 tmux 跑着 Codex CLI，手机用 Termius SSH 进去 attach 上去就能继续。能用，但问题不少：历史会话看不全，手机上打指令很麻烦，输出也不够美观。

还试过**远程桌面**，用的 UU 远程。平时操作体验一般，手机控制电脑本来就别扭。但有一个场景它是唯一解：AI 写完代码需要验证 web 界面的时候，Remote Control 和 SSH 都做不到，只有远程桌面能看到实际页面。所以还是会偶尔用到。

不过新问题又来了，token 烧得太猛，小金库扛不住了 (T_T)
