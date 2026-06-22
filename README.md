<h1 align="center">Hi, I'm Ose 👋</h1>

<p align="center">
  <em>20+ years in physical security. Now moving into cybersecurity.</em>
</p>

<p align="center">
  <a href="https://github.com/OseMultaharju/ghostlycasper-os">
    <img src="https://img.shields.io/badge/Project-GhostlyCasper%20OS-1a3a5c?style=for-the-badge&logo=tor" alt="GhostlyCasper OS">
  </a>
  <a href="https://github.com/OseMultaharju/gemini-pentest-pro">
    <img src="https://img.shields.io/badge/Project-Gemini%20Pentest%20Pro-2c5f8a?style=for-the-badge&logo=googlegemini" alt="Gemini Pentest Pro">
  </a>
  <img src="https://img.shields.io/badge/Status-Career%20Transition-2c5f8a?style=for-the-badge" alt="Career Transition">
  <img src="https://img.shields.io/badge/Location-Finland-blue?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Finland">
</p>

---

## About me

I'm a 48-year-old career changer with over **two decades of professional security experience** — structural security, retail loss prevention, and cash-in-transit. After spending most of my working life protecting physical assets and people, I'm now studying **Information Technology** at Metropolia University of Applied Sciences and moving into **cybersecurity**.

Physical security and digital security turn out to share more than I expected. Both require thinking adversarially. Both require defence in depth. Both punish you for assuming users will behave the way you wish they would. The vocabulary is different; the discipline is the same.

The work you see here reflects that transition.

## What I'm working on

### 🛡️ [GhostlyCasper OS](https://github.com/OseMultaharju/ghostlycasper-os)

A privacy-first amnesic live operating system, built from scratch as my final-year project at Metropolia. Boots from a USB stick, routes every byte of traffic through Tor, forgets everything at shutdown.

- **7,700+ lines of Bash**, one maintainable build script
- **50+ iterations** with documented security audits between versions
- **Four threat profiles** for different user contexts
- **Hardware-tested** on real ThinkPad laptops, not just VMs
- **Honest about what it doesn't protect against**

If you're looking for an example of how I approach engineering — the project's [development history](https://github.com/OseMultaharju/ghostlycasper-os/blob/main/docs/development-history.md) walks through every wrong turn I took and what I learned from it.

### 🤖 [Gemini Pentest Pro](https://github.com/OseMultaharju/gemini-pentest-pro)

An LLM-driven, human-in-the-loop penetration-testing assistant for Kali Linux. The Google Gemini API orchestrates dozens of standard security tools; I confirm every command that touches the "gray area" before it runs. My Innovation Project at Metropolia.

- **Brain + Hands architecture** — Gemini reasons over user intent, deterministic Python wrappers execute the actual commands
- **Safety gate is in the code, not the model** — a regex-based validator that classifies every command (hard-block / soft-block / per-tool risk level), layered on top of the LLM's own moderation rather than relying on it
- **Two hardware profiles** — field unit (X270, native Kali, monitor mode + injection) and compute unit (P1 Gen 5, WSL2 + RTX A3000, ~423 kH/s Hashcat against WPA handshakes)
- **Decoupled HTML reporter** — solves the token-window problem on large nmap/Wireshark outputs; ANSI color codes become real HTML so the report looks like a terminal, not an AI summary
- **Verified end-to-end** — full recon chain on real targets, ethical self-restraint on ambiguous ones, and a complete kill-chain on an intentionally-vulnerable IoT smart-home testbed
- **Authorized use only** — designed for labs, CTF, and engagements with written permission; the HITL prompts are not optional

For the full project vision and ethical rationale, see [PROJECT_VISION.md](https://github.com/OseMultaharju/gemini-pentest-pro/blob/main/PROJECT_VISION.md) (in Finnish).

## Background

Twenty years carrying responsibility for people's physical safety teaches you a few things:

- **Threat modelling is not theory.** Either your countermeasures work in the field or they don't.
- **Layered defence is the only defence worth building.** No single mechanism is the whole story.
- **Documentation matters.** When something goes wrong, somebody needs to understand what you set up and why.
- **Honesty about limitations builds trust.** Promising what you can't deliver is worse than promising less.

I'm bringing all of that to cybersecurity.

## Technical skills

These are the tools I've actually used to build something real — not a list of buzzwords:

<table>
<tr>
<td valign="top" width="33%">

**Systems & Linux**
- Debian / Kali Linux
- live-build (custom ISO)
- systemd, AppArmor
- nftables firewall
- LUKS2 disk encryption
- Bash scripting

</td>
<td valign="top" width="33%">

**Offensive Security**
- Penetration testing methodology
- Kali Linux (native and WSL2)
- nmap, Wireshark, tcpdump
- Hashcat (GPU-accelerated WPA cracking, ~423 kH/s on RTX A3000)
- Monitor mode + packet injection (Wi-Fi handshake capture)
- LLM-orchestrated tooling with human-in-the-loop safety gates

</td>
<td valign="top" width="33%">

**Engineering Practice**
- Threat modelling (STRIDE)
- Iterative security audits
- Git, version control discipline
- Hardware testing methodology
- Technical writing

</td>
</tr>
</table>

## Areas I'm interested in

My focus is cybersecurity as a direct continuation of two decades in operational security — not software engineering for its own sake. The projects above are the technical means; the destination is security work.

- **Penetration testing and offensive security** — adversarial testing as a defensive discipline, the area my Gemini Pentest Pro project sits in
- **Security operations** — log analysis, alert triage, incident response, the cybersecurity continuation of an operations-centre career
- **Vulnerability assessment and risk analysis** — translating technical findings into operational risk that decision-makers can act on
- **Physical-to-digital security continuum** — insider threat, social engineering, red-team operations and physical penetration testing, where the operational security I built for a living translates most directly
- **Threat modelling and defensive architecture** — STRIDE, layered defence, fail-closed design as habits rather than checklists

## GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=OseMultaharju&show_icons=true&theme=transparent&hide_border=true&include_all_commits=true" alt="GitHub stats">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=OseMultaharju&layout=compact&theme=transparent&hide_border=true" alt="Top languages">
</p>

## Looking for

I'm specifically interested in these roles, where my operational security background translates most directly:

### 🛡️ SOC Analyst (Tier 1 / Tier 2)
Twenty years of shift work in cash-in-transit means I'm already used to operations-centre rhythms — long focus windows, alert handling under time pressure, clear escalation when something looks off. I'm building the technical layer (log analysis, SIEM concepts, incident triage) on top of that operational discipline.

### 👁️ Insider Threat Analysis
Two decades watching the inside of high-value security operations means I know what abnormal behaviour actually looks like — not from a textbook, but from having walked past it. Behavioural baselines and policy violations were the language I worked in every day.

### 🔓 Physical Penetration Testing
This one is obvious. I know how physical security is supposed to work because I built it for a living. I know where it tends to fail. I know the difference between a control that looks good on paper and one that holds up at three in the morning when nobody's watching.

### 📚 Security Operations & Security Awareness Training
Translating between operational reality and policy is something I did constantly in my previous career. Translating between technical risk and the way employees actually behave is the same skill in different clothes.

---

### What I bring

Career changers from operational security backgrounds aren't common in cybersecurity. The combination of two decades of adversarial thinking with the technical work you can see in this profile is unusual. If your team is hiring at the entry level and that sounds like a useful perspective, I'd be glad to talk.

I'm based in Finland, available for on-site or hybrid roles in the Helsinki region, and open to remote.

## Contact

For project-related discussions, the best place is GitHub directly — issues, discussions, or via the noreply address used in my commits.

<p align="center">
  <a href="mailto:156774193+OseMultaharju@users.noreply.github.com">
    <img src="https://img.shields.io/badge/Email-via%20GitHub-1a3a5c?style=for-the-badge&logo=protonmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/OseMultaharju/ghostlycasper-os">
    <img src="https://img.shields.io/badge/See%20my%20work-GhostlyCasper%20OS-2c5f8a?style=for-the-badge&logo=github" alt="GhostlyCasper OS">
  </a>
  <a href="https://github.com/OseMultaharju/gemini-pentest-pro">
    <img src="https://img.shields.io/badge/and-Gemini%20Pentest%20Pro-1a3a5c?style=for-the-badge&logo=github" alt="Gemini Pentest Pro">
  </a>
</p>

---

<p align="center">
  <sub>
    "Twenty years in physical security taught me that the best defences are layered, quiet, and honest about their limits.<br>
    The same is true in software. I'm building accordingly."
  </sub>
</p>
