---
title: "Why AI Gets Me 80% There But Fails at the Last 20%"
date: 2026-07-20
categories: [bug-bounty]
tags: [bug bounty, ai, learning-in-public, ai-assisted-security, recon]
excerpt: "AI is genuinely good at recon. The problem is recon is not the hard part. The hard part is what comes after."
---

Let me be honest about something.

AI is genuinely good at bug bounty recon. Give it a target, it maps the surface, finds the endpoints, identifies the tech stack, spots interesting parameters. Stuff that used to take me days of Googling and bookmarking — done in minutes.

That part works. I am not exaggerating.

The problem is recon is not the hard part.

The hard part is what comes after. Taking that interesting endpoint, that suspicious parameter, that weird behaviour — and turning it into something that a triage team will actually pay for. That's where AI keeps letting me down. And honestly, that's where I keep letting myself down too.

Here's what the rejections look like:

**Duplicate.** Someone already found it. AI found something real, it just wasn't first.

**Informational.** The finding is technically correct but there's no real impact. AI doesn't know the difference between a vulnerability that looks scary and one that actually matters.

**Out of scope.** AI doesn't always read the program rules carefully enough. It finds something on a subdomain that the program doesn't cover.

**Silent fix.** The worst one. The program doesn't respond, doesn't triage, doesn't pay — and six months later the issue is quietly patched. You never know if you were right.

The pattern across all of these is the same. AI is great at finding things. It's not great at knowing which things matter.

That gap — between finding something and finding something that pays — is about judgment. Does this finding have real impact? Has this been reported before? Is this actually exploitable or just interesting? Can I prove it?

Those are not questions AI can answer well yet. They need context, intuition, and experience. The kind that comes from reading hundreds of disclosed reports, understanding what programs actually care about, knowing how triage teams think.

I am still building that. Every rejection teaches me something. Every duplicate tells me I was on the right track but not fast enough. Every informational tells me I need to think harder about impact.

The 80% AI gives me is real and I wouldn't trade it. But the last 20% is still mine to figure out.

And I am working on it.

— Manikandan
