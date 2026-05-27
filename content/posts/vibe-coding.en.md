---
draft: false
title: Vibe Coding on a Phone
slug: "vibe-coding"
tags:
  - ai
  - vibe-coding
categories:
  - Uncategorized
date: '2026-05-27T09:04:50+08:00'
---

After middle age, the time that truly belongs to you gets smaller and smaller.

But since vibe coding became popular, I have started having more ideas instead of fewer. Development can now be handed over to AI. Things I would not have dared to build before can now be shipped at a very low cost. That feeling of creation is addictive.

Time can still be squeezed out. Looking after kids, going out, waiting for a ride. These fragments add up. Vibe coding is mostly about giving instructions, so it fits these moments surprisingly well.

The smoothest setup for me right now is **Remote Control**. Claude Code and Codex both support it now: the computer runs the task, and the phone is used to check progress, approve actions, and add follow-up instructions. It feels natural. It is still the same agent workflow, just on a different screen.

Before Remote Control became available, I mainly used **Tailscale + Termius + tmux**. I would start tmux on my Mac, run Codex CLI there, then SSH from Termius on my phone and attach to the session. It worked, but it had problems: the conversation history was incomplete, typing instructions on a phone was annoying, and the output was not pleasant to read.

I also tried remote desktop, using UU Remote. The everyday experience is average because controlling a computer from a phone is awkward. But there is one case where it is the only real option: when AI finishes coding and I need to verify a web UI. Remote Control and SSH cannot show the actual page, but remote desktop can. So I still use it occasionally.

The new problem is that tokens burn too fast. My small budget cannot keep up.
