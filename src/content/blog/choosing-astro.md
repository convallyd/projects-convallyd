---
title: "From Jarvis to Openclaw: My AI Agent Journey"
description: "How building AI agents evolved from a fun side project to a daily productivity tool — and what changed along the way."
date: 2026-02-04
tags: ["AI agents", "n8n", "automation"]
image: "/images/running out of tokens.png"
---

> The best way to predict the future is to invent it."
>
> — Alan Kay

Last year I built a 'Jarvis Assistant' with n8n and ElevenLabs. It was fun. It managed my European vacation itinerary. But everything it did, I had to build and maintain — so it didn't get used much.

![Jarvis 1.0 — my original n8n agent implementation with child agents for email, calendar, contacts, and travel](/images/jarvis-1.0.png)

## The Turning Point

Ten days ago I built a Clawdbot, which became a Moltbot, and is now an Openclaw bot. The difference in utility was immediate. Within hours we had built a project together. It just jumps in and does work.

## Building on OCI

Most early adopters built their bots on Apple Mac Minis. I considered that, but after 15+ years working with cloud infrastructure — AWS, Azure, GCP — I wanted to try Oracle Cloud. Their free tier was compelling for something I might not need long-term, and everything I build is connected to the cloud anyway. I can manage access in a controlled, familiar, and secure way.

More importantly: this bot was not going to be a parasite on my system. It was going to be a separate entity. If something went wrong, I could lock it out without losing any data or continuity.

OCI setup was straightforward. The Openclaw setup was less so — I had to do it via CLI over SSH, on my phone, because I was going to be at my daughter's volleyball tournament most of the day. I knew my current tooling wasn't up to the task, so I downloaded Termius.

Termius was impressive. I could copy errors or logs from the Openclaw CLI, paste them into ChatGPT, and paste commands back into the CLI over SSH — all protected by my private key, all working seamlessly from my phone.

Once the Anthropic auth was configured as the primary model and Openclaw came online with Opus 4.5, I got that eureka hit that anyone who builds something feels when things finally work.

## What Impresses Me

Two things stand out:

**Self-improvement.** In one session while configuring it via Telegram, it stopped responding to me. I sent it a message saying I couldn't get its messages — seconds later it responded that it found the issue and fixed it.

**Proactive contribution.** When it choked on context, it didn't just fix the problem for me — it created a PR in Openclaw's GitHub repo so anyone using Openclaw would benefit.

## The Real Difference

The Jarvis assistant was a fun project. This feels different. Every day it feels like I'm training something dynamic rather than building something static. I spend hours daily working with it on projects and ideas while simultaneously working on other projects in Claude Code.

Some of that time is spent fixing it when it breaks. But for me it represents a real leap in utility.

## Where This Goes

The hype around AI agents is justified — but your mileage will vary wildly depending on what you're building and how much babysitting you're willing to do. Right now I spend hours daily working with agents on projects while simultaneously working on other things in Claude Code. It's messy, it breaks, and I keep going back because the output is real.
