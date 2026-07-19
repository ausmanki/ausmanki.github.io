---
title: "How I Built a 790 Page Cybersecurity Wiki Using Andrej Karpathy's Idea"
date: 2026-07-20
categories: [learning]
tags: [wiki, andrej-karpathy, ai, cybersecurity, knowledge, learning-in-public]
excerpt: "I was just going through some AI blogs when I found Karpathy's gist. Read it once and I was like — dude, this is exactly what cybersecurity needs."
---

So I was just going through some AI blogs one day and I found this gist by Andrej Karpathy — [check it out here](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

He talks about compounding knowledge using AI. Basically, don't let what you learn just disappear. Capture it, connect it, build on it over time. Same way money compounds, knowledge compounds too — if you actually do something with it.

I read that and I was like — dude, this is exactly what cybersecurity needs.

Because the problem with security is everything is all over the place. CVEs on NVD, threat actors in vendor reports, techniques on MITRE, news across a hundred different feeds. You read something today, next week it's gone. Nothing sticks, nothing connects.

So I just took his idea and applied it to cybersecurity.

Every CVE I studied — page. Every threat actor, technique, incident — documented, sourced, linked to everything related. Pulling from CISA KEV, RSS feeds, threat intelligence reports. Every session I fetch the latest, ingest it, update the actor pages, fix broken links, repeat.

And it just kept growing.

What started as a few pages is now 790 pages. 298 CVEs. 59 threat actors. 47 techniques. 28 defense playbooks. 69 unanswered questions I am still going through. And it is still growing.

You can check it out at [ausmanki.github.io/cybersec-wiki](https://ausmanki.github.io/cybersec-wiki).

The thing Karpathy got right — the value is not in any single page. It's in the connections. When you see a threat actor used a technique that maps to a CVE that's in CISA KEV and you already have a defense playbook for it — that's when it clicks. That's when it stops being just reading and starts being actual understanding.

Honestly I don't think I would have built this without AI. The grunt work of fetching, summarising, categorising — AI just handles it. I focus on what connects to what and whether the source is legit.

That's the Karpathy idea. And it works.

— Manikandan
