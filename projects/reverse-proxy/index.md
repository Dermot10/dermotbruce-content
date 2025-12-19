---
title: Reverse Proxy Safeguarding Platform
slug: reverse-proxy-poc
shortDescription: "Reverse proxy platform to safeguard employees interacting with third-party live streaming services"
tech: ["Python", "AWSx", "HTTP", "Cloud Infrastructure"]
topics: ["Security Engineering", "Backend Development", "System Design"]
screenshots: []

problem: "A third-party subsidiary operating as a functional extension of the organisation relied on live streaming platforms that exposed employees to malicious actors, including explicit and abusive behaviour. 
The parent organisation lacked sufficient control and visibility over inbound traffic, relying on external platform safeguards that were reactive, opaque, and insufficient for employee protection."

solution: "Designed and delivered a reverse proxy platform positioned in front of third-party live streaming services to act as a security control plane without disrupting upstream business operations. 
The proxy transparently routed traffic while capturing high-fidelity security telemetry, including request metadata and behavioural indicators, enabling real-time analysis and enforcement. 
The architecture enabled IP-based blocking, policy tightening, and rapid iteration on controls, while maintaining low latency and strict separation between traffic handling and security logic to support future expansion."

impact: "Significantly improved employee safeguarding by enabling proactive identification and blocking of malicious actors, including repeat offenders. 
Provided the security team with actionable, request-level data to support investigations and policy refinement rather than relying on incomplete third-party signals. 
Established a reusable security pattern for exerting control over external platforms operated by subsidiaries while preserving operational autonomy."

takeaways: "Strengthened experience designing security platforms that balance safety, performance, and organisational boundaries. 
Reinforced a senior-level approach to system design: introducing control and observability at architectural choke points rather than through fragile downstream mitigations."
---
