---
title: "How I Built a 790 Page Cybersecurity Wiki Using Andrej Karpathy's Idea"
date: 2026-07-20
categories: [learning]
tags: [wiki, andrej-karpathy, ai, cybersecurity, knowledge, learning-in-public]
excerpt: "i was just going through some AI blogs when i found karpathy's gist. read it once and i was like — dude this is exactly what cybersecurity needs."
---

so i was just going through some AI blogs one day and i found this gist by andrej karpathy — [check it out here](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

he talks about compounding knowledge using AI. basically don't let what you learn just disappear. capture it, connect it, build on it over time. same way money compounds, knowledge compounds too if you actually do something with it.

i read that and i was like — dude this is exactly what cybersecurity needs.

because the problem with security is everything is all over the place. CVEs on NVD, threat actors in vendor reports, techniques on MITRE, news across a hundred different feeds. you read something today, next week it's gone. nothing sticks, nothing connects.

so i just took his idea and applied it to cybersecurity.

every CVE i studied — page. every threat actor, technique, incident — documented, sourced, linked to everything related. pulling from CISA KEV, RSS feeds, threat intelligence reports. every session fetch the latest, ingest it, update the actor pages, fix broken links, repeat.

and it just kept growing.

what started as a few pages is now 790 pages. 298 CVEs. 59 threat actors. 47 techniques. 28 defense playbooks. 69 unanswered questions i am still going through. and it is still growing.

you can check it out at [ausmanki.github.io/cybersec-wiki](https://ausmanki.github.io/cybersec-wiki).

the thing karpathy got right — the value is not in any single page. it's in the connections. when you see a threat actor used a technique that maps to a CVE that's in CISA KEV and you already have a defense playbook for it — that's when it clicks. that's when it stops being just reading and starts being actual understanding.

honestly i don't think i would have built this without AI. the grunt work of fetching, summarising, categorising — AI just handles it. i focus on what connects to what and whether the source is legit.

that's the karpathy idea. and it works.

— Manikandan
