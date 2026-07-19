---
title: "How I Built a 790 Page Cybersecurity Wiki Using Andrej Karpathy's Idea"
date: 2026-07-20
categories: [learning]
tags: [wiki, andrej-karpathy, ai, cybersecurity, knowledge, learning-in-public]
excerpt: "while i was going through AI blogs i came across andrej karpathy's gist on compounding knowledge. i read it and thought — this is exactly what cybersecurity needs."
---

while i was going through blogs related to AI i came across andrej karpathy's gist — [read it here](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

he talked about compounding knowledge using AI. the idea is simple — don't let what you learn disappear. capture it, connect it, let it grow over time. knowledge compounds just like money does, if you let it.

i read that and thought — this is exactly what cybersecurity needs.

the problem with security is knowledge is scattered everywhere. CVEs across NVD, threat actors across vendor reports, techniques across MITRE, news across a hundred feeds. you read something today and forget it next week. nothing connects. nothing sticks.

so i took karpathy's idea and applied it to cybersecurity.

every CVE i studied went into a page. every threat actor, every technique, every incident — documented, sourced, linked to everything related to it. i pulled from CISA KEV, RSS feeds, threat intelligence reports. every session i would fetch the latest news, ingest it into the wiki, update the actor pages, fix the links.

it grew.

what started as a few pages is now 790 pages. 298 CVEs. 59 threat actors. 47 techniques. 28 defense playbooks. 69 unanswered questions i am still working through.

the wiki is at [ausmanki.github.io/cybersec-wiki](https://ausmanki.github.io/cybersec-wiki).

the thing karpathy got right is that the value isn't in any single page — it's in the connections between them. when you see that a threat actor used a technique that maps to a CVE that is in the CISA KEV catalog that you have a defense playbook for — that's when learning clicks. that's when it stops being reading and starts being understanding.

i don't know if i would have built this without AI. probably not. the grunt work of fetching, summarising, categorising — AI handles all of that. i just make the decisions about what connects to what and whether the source is credible.

that's the part that matters. that's the karpathy idea.

— Manikandan
