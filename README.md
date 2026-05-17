# SCFS - project site

Distill-style single-page web companion for the paper *Supply-Chain-Free Skills: A Capability-Based Architecture for Trustworthy Agentic AI Skill Ecosystems*.

**Live**: https://elcronos.github.io/scfs-site/
**Paper status**: in preparation · target venue USENIX Security 2027
**Runtime repo**: https://github.com/elcronos/scfs (private until coordinated-disclosure embargo clears)

## Stack
- Single `index.html`. No build step.
- Tailwind CDN, Mermaid CDN, Google Fonts.
- ~33 KB HTML; ~600 KB total with the hero PNG.

## Run locally
```bash
python3 -m http.server 8088
```
Then open http://localhost:8088

## Embargo policy
The PoC attack section deliberately abstracts away reproduction steps, exfiltration endpoints, and concrete attack code while coordinated disclosure with Anthropic is open. Full attack details land here only after the 90-day embargo expires.

## License
- Site copy: CC-BY 4.0
- Hero figure: generated via Replicate FLUX-schnell
- Mermaid / Tailwind / fonts: original licenses
