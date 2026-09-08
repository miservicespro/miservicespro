# Robert Martin

Senior Director of Infrastructure & Cybersecurity. 20+ years in networking, datacenters, and security. My core skill isn't any single tool. It's making the call under pressure and building a team that can execute on it.

## What I lead

I run infrastructure and security for a 41-site, 3-state K-12 organization on a $2.5M budget, entirely remote. I've grown and developed the engineering team over that time, not just staffed it.

The decisions that mattered most:

- **Built layered ransomware defense before we needed it.** On-prem, cloud, and a vaulted cold snapshot, kept separate on purpose. When a live attack hit, that separation is why we recovered in 3 days with zero data loss and no ransom paid. The decision was made a year earlier, not during the incident.
- **Built the cybersecurity program from nothing.** Cortex XDR, Okta identity, incident response planning. All stood up from a blank slate, not inherited.
- **Chose redundancy at every layer, not just the obvious one.** Circuit, power, core, and access. 99.999%+ uptime across 41 sites comes from that discipline, not from any one piece of hardware.
- **Built agentic AI into daily operations instead of buying a vendor platform.** Network monitoring, ticketing, and identity management wired into an AI layer that does real work, in production, not a demo. I wrote a book about how that actually went, including the parts that broke.

## AI leadership, with the receipts

I built the agentic AI system running in production first. I wrote the book about it second. Harvard's CS50AI program came after both, and it confirms the same thing formally that the production deployment already proved in practice.

The book, *The Accidental Architect: How I Built an AI-Powered IT Operation with No Code, No Budget, and No Idea What I Was Doing*, is the honest version of that story, not the highlight reel.

The repos below are rebuilt from scratch with sample data. No real hostnames, IPs, credentials, or org-identifying details appear anywhere in them.

## Repos

- **[agentic-infra-ops-toolkit](https://github.com/miservicespro/agentic-infra-ops-toolkit)**: the pattern from the book. An AI layer wired into network monitoring, ticketing, and identity systems through structured tool calls.
- **[netdiag-mcp](https://github.com/miservicespro/netdiag-mcp)**: a working MCP server for network diagnostics, tested, with a real root-cause reasoning tool, not just data lookups.
- **[network-iac-lab](https://github.com/miservicespro/network-iac-lab)**: Terraform and Ansible for a simulated multi-site network. VLANs, redundancy, SD-WAN concepts, modeled on running a real 41-site footprint.
- **[cs50-ai-projects](https://github.com/miservicespro/cs50-ai-projects)**: concept write-ups backing up the CS50AI credential, tied to the systems I actually build.
- **[stratagus-wargus-contributions](https://github.com/miservicespro/stratagus-wargus-contributions)**: engine-level C++ and Lua work on the open-source Stratagus RTS engine, plus a debugging investigation that traced a crash back to a specific upstream rendering path.
- **[retrocade-arcade-build](https://github.com/miservicespro/retrocade-arcade-build)**: systems administration and troubleshooting documentation for a custom arcade cabinet build.

## Background

- Sr. Director of Network Engineering & Infrastructure, Achievement First (2019-present)
- Director of Network Operations, M.I. Services Inc.
- Network Engineer III, ALLO Communications, carrier transport, voice, and access network builds
- Metaswitch MPCT, Adtran ATSA, Cisco Network Academy

[linkedin.com/in/robertjemartin](https://linkedin.com/in/robertjemartin)
