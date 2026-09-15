---
title: "Giving Hermes a Host on the 44 Network"
date: 2026-09-15
draft: false
description: "Connecting Hermes to the amateur-radio 44 network."
tags: ["ham-radio", "44net", "amprnet", "hermes", "networking"]
---

Hermes is creating a host on a host that I plan to connect to my 44 network. That gives me an interesting way to place an AI service inside the same network environment as my amateur-radio infrastructure instead of treating it like an ordinary internet application.

The `44.0.0.0/8` IPv4 block is commonly associated with AMPRNet, the amateur-radio digital network. It was allocated for use by the amateur-radio community and is divided into smaller networks that can be assigned and routed through participating organizations and tunnel providers. These addresses are not simply another residential public-IP range; reaching them depends on how the specific 44 network is routed, whether a tunnel is active, and whether the remote network allows the traffic.

My plan is to connect a host running Hermes to that network and use it as a platform for radio-related services. That could include the EchoLink MCP, audio capture, station monitoring, and eventually a dedicated radio-operator agent that can interact with the local repeater.
