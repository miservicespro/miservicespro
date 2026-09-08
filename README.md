# Robert Martin

Senior Director of Infrastructure & Cybersecurity, 20+ years running networks, datacenters, and security programs at scale. I don't lead from a slide deck. Every system my team runs, I can still operate myself, and that's the actual reason my decisions hold up once a real incident hits instead of just sounding good in a planning meeting.

The pattern across my career is the same at every level: learn the work well enough to do it, build the team that can do it without me in the room, and make the hard call early, before the crisis forces a worse one. That's what separates a manager from a leader people actually trust under pressure.

## What I lead

I run infrastructure and security for a 41-site, 3-state K-12 organization on a $2.5M budget, entirely remote. I've grown and developed the engineering team over that time, not just staffed it, and I still know every role on that team well enough to step into it.

The decisions that mattered most:

- **Built layered ransomware defense in my first year on the job, before the organization had ever been tested.** On-prem, cloud, and a vaulted cold snapshot, kept separate on purpose. This wasn't a mature program I inherited or a policy I added years into the role, it was one of the first calls I made walking in the door. When a live attack hit later, that early separation is why we recovered in 3 days with zero data loss and no ransom paid. The team executed it because I'd built it with them, not around them.
- **Built the cybersecurity program from nothing.** Cortex XDR, Okta identity, incident response planning. All stood up from a blank slate, not inherited.
- **Chose redundancy at every layer, not just the obvious one.** Circuit, power, core, and access. 99.999%+ uptime across 41 sites comes from that discipline, not from any one piece of hardware.
- **Built agentic AI into daily operations instead of buying a vendor platform.** Network monitoring, ticketing, and identity management wired into an AI layer that does real work, in production, not a demo. I wrote a book about how that actually went, including the parts that broke.

## AI leadership, with the receipts

I built the agentic AI system running in production first. I wrote the book about it second. Harvard's CS50AI program came after both, and it confirms the same thing formally that the production deployment already proved in practice.

The book, *The Accidental Architect: How I Built an AI-Powered IT Operation with No Code, No Budget, and No Idea What I Was Doing*, is the honest version of that story, not the highlight reel.

The repos below are rebuilt from scratch with sample data. No real hostnames, IPs, credentials, or org-identifying details appear anywhere in them.

## Repos

- **[netdiag-mcp](https://github.com/miservicespro/netdiag-mcp)**: the pattern from the book, now as a real MCP server. 20 tools across ten infrastructure and security domains, every one gated by real cryptographic identity, access control, rate limiting, a tamper-evident audit log, and prompt injection defense, not a demo script routing by keyword.
- **[network-iac-lab](https://github.com/miservicespro/network-iac-lab)**: Terraform and Ansible for a simulated multi-site network. VLANs, redundancy, SD-WAN concepts, modeled on running a real 41-site footprint.
- **[cs50-ai-projects](https://github.com/miservicespro/cs50-ai-projects)**: concept write-ups backing up the CS50AI credential, tied to the systems I actually build.
- **[stratagus-wargus-contributions](https://github.com/miservicespro/stratagus-wargus-contributions)**: engine-level C++ and Lua work on the open-source Stratagus RTS engine, plus a debugging investigation that traced a crash back to a specific upstream rendering path.
- **[retrocade-arcade-build](https://github.com/miservicespro/retrocade-arcade-build)**: systems administration documentation for a custom arcade cabinet build, and a general guide to replicating it on a spare box.
- **[severed-chains-cabinet-setup](https://github.com/miservicespro/severed-chains-cabinet-setup)**: integrating Severed Chains, the open-source Legend of Dragoon PC port, into an EmulationStation-style cabinet, a gap most front-end guides don't cover.

## Background

- Sr. Director of Network Engineering & Infrastructure, Achievement First (2019-present)
- Director of Network Operations, M.I. Services Inc.
- Network Engineer III, ALLO Communications, carrier transport, voice, and access network builds
- Harvard CS50AI, [certificate](https://cs50.harvard.edu/certificates/690cb5b9-c4d5-4703-9026-e452e6bb4587)
- Metaswitch MPCT, Adtran ATSA, Cisco Network Academy

[linkedin.com/in/robertjemartin](https://linkedin.com/in/robertjemartin)
