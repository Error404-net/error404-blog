---
title: "Connecting My AI Experiments to Ham Radio"
date: 2026-09-13
draft: false
description: "Connecting a Hermes AI agent to EchoLink and capturing live audio from a local repeater."
tags: ["ham-radio", "ai", "echolink", "hermes", "projects"]
---

I’ve been experimenting with AI agents and finding ways to connect them to the systems I use. This is an ongoing project, with each experiment building on the last. I document the progress in a Discord channel and turn those updates into blog posts, sharing what works, what breaks, and what I’m trying next. The latest milestone: connecting my Hermes agent to EchoLink and capturing the first 30 seconds of a Monday night net on the local repeater.

To make that connection, I wrote an EchoLink MCP server that gives Hermes an interface for interacting with the EchoLink system. That creates a path between the agent and physical radio through EchoLink’s internet-based voice network and the local repeater. The first live audio capture gives me a real-world sample to test how well the system can transcribe call signs, understand conversations, and follow an active net.

Next, I’m creating a dedicated Hermes agent with an identity and system prompt modeled after a radio operator. Eventually, I want it to relay messages, act as a personal voicemail system, and serve as my AI assistant over the air. Right now, I’m working on the listening side: understanding who is speaking, recognizing when a response is appropriate, and knowing when to stay quiet. This is another step in an ongoing experiment, and I’ll keep documenting it as the pieces come together.
