---
title: "AI Agent Experiments"
description: "From a voice-activated Jarvis that managed my vacation to autonomous coding agents that fix themselves — what I've learned building with AI."
tags: ["AI Agents", "n8n", "Claude", "Automation"]
featured: true
image: "/images/hero-ai-agents.png"
order: 2
---

> "The best way to predict the future is to invent it."
>
> — Alan Kay

## Where It Started

I built a "Jarvis Assistant" with n8n and ElevenLabs — voice-activated, managed my European vacation itinerary, ran custom workflows. Fun to build. But everything it did, I had to build and maintain. So it didn't get used much.

## Where It Got Interesting

Ten days later I built a Clawdbot, which became a Moltbot, and is now an Openclaw bot. Within hours of setup, the agent was building projects collaboratively. The difference in utility was immediate.

Two things stand out. First, self-improvement: during one session configuring it via Telegram, it stopped responding. I sent a message saying I couldn't get its messages — seconds later it responded that it found the issue and fixed it. Second, proactive contribution: when it choked on context, it didn't just fix the problem for me — it created a PR in Openclaw's GitHub repo so anyone using the framework would benefit.

Every day it feels more like training something that grows than building something static. Some of that time is spent fixing it when it breaks. But it represents a real leap in what's possible.

## What I'm Working On Now

Multi-agent collaboration, context management across long sessions, and figuring out where the right boundaries are between human direction and agent autonomy. That last one is a UX problem — and it's exactly the kind I've spent my career on.
