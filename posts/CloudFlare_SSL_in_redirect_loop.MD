---
title: "CloudFlare SSL in redirect loop"
date: 2022-09-01T17:01:39+08:00
draft: true
---

最近在godaddy上面購買網域，然後使用cloudflare來申請ssl並弄成https的連線。結果今天上來看blog卻發現進不去，錯誤訊息是太多的redirect了。
打開F12重整看看，還真的是持續進行著
{{<figure src="/posts/img/repeat301.jpg" title="重複redirect到首頁的情況">}}
