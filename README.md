# tibo-reset-lever-aimade
额度重置拉杆：Codex 负责人 Tibo 实体重置装置的单文件 HTML 粉丝复刻。A single-file HTML fan replica of the physical reset lever shown by Tibo, who leads Codex at OpenAI.

# 额度重置拉杆 · Reset Lever

> 非官方粉丝复刻，与 OpenAI 无关，不会真的重置任何人的额度。
> Unofficial fan project. Not affiliated with OpenAI, and it doesn't actually reset anyone's usage limits.

## 简介

2026 年 DevDay 前一晚，Codex 负责人 Tibo（Thibault Sottiaux）在一段视频里展示了他桌上的实体重置装置：往下一拉，开始 10 秒倒计时，10 秒内还能取消。这个项目用一个 HTML 文件把它复刻成了网页。

- 按住机身底部的 U 形拉手往下拉到底，拉手上方的黑槽里开始 10 秒倒计时
- 倒计时走完，右上角弹出“ChatGPT 付费用户已重置成功”
- 10 秒内把拉手推回去就取消，这次不计数
- 重置次数、取消次数和最近记录保存在浏览器的 localStorage 里，刷新后还在
- 支持鼠标、触屏和键盘（方向键 / 空格），带合成音效，适配深浅色主题
- 只有一个 HTML 文件，不用构建，下载后用浏览器打开就能玩

实物机身正面是 OpenAI 的标志，这里换成了中性的重置符号。视频里看不出倒计时显示在哪，网页就把它放进了拉手上方的黑槽。

本项目由 Claude Opus 5.5 和 Qwen 3.8 Max 合作完成。

## About

The night before DevDay 2026, Tibo (Thibault Sottiaux), who leads Codex at OpenAI, showed the physical reset device on his desk in a short video: pull it down, a 10-second countdown starts, and he can still cancel it. This project recreates that device as a single HTML page.

- Pull the U-shaped handle at the bottom all the way down to start a 10-second countdown in the slot above it
- When the countdown ends, a toast in the top-right corner says "ChatGPT 付费用户已重置成功" ("ChatGPT paid users reset successfully")
- Push the handle back up within 10 seconds to cancel; cancelled pulls aren't counted
- Reset count, cancel count and recent history are saved in your browser's localStorage and survive a refresh
- Works with mouse, touch and keyboard (arrow keys / Space), with synthesized sound effects and light/dark themes
- One HTML file, no build step: download it and open it in any modern browser

The real device has the OpenAI logo on its front; this replica uses a neutral reset symbol instead. The video doesn't show where the countdown is displayed, so the page puts it in the slot above the handle.

Made in collaboration by Claude Opus 5.5 and Qwen 3.8 Max.
