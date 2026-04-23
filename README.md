<table width="100%">
  <tr>
    <td width="50%" align="center">
      <h1>Hello.</h1>
      <p><em>We hope what you find is useful.</em></p>
    </td>
    <td width="50%" align="center">
      <h2>Casey Tunturi</h2>
      <p>
        <strong>Infrastructure for self-hosted AI<br>and homelab resilience</strong><br>
        <em>walking the line between arcane and algorithmic</em><br>
        American relocated to Ontario, Canada 🇨🇦
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <sub><strong>Recent:</strong> Maintainer of <a href="https://github.com/Fimeg/letta-external-memfs">letta-external-memfs</a> — <strong>endorsed by the Letta team as the recommended self-hosted memfs path.</strong> Sole developer of the Matrix channel adapter for <a href="https://github.com/letta-ai/letta-code">letta-code</a> and LettaBot.</sub>
</p>

---

### 🚀 Featured Projects

#### [letta-external-memfs](https://github.com/Fimeg/letta-external-memfs)
**Recommended self-hosted path for Letta memory persistence**
```
Status:     Endorsed by Letta team · community-maintained
Stack:      TypeScript (client patch) + Python (server patch)
What:       Direct git transport to external hosts (Gitea/GitHub/GitLab)
            Server-side block sync endpoint (upstream PR pending)
Model:      Aligned to Letta's own "git is source of truth, postgres cache"
```

> *The sidecar is gone. Self-hosters stop reinventing the workaround.*

#### Matrix Channel Adapter — [letta-code](https://github.com/letta-ai/letta-code) / LettaBot
**Sole developer. Actively maintained alongside the core Letta team.**
```
Features:   rust-crypto E2EE · streaming text_delta · reaction approval UX
            Voice (MSC3245) · encrypted media with localPath decryption
            Slash command parity with Slack/Discord adapters
```

> *Matrix as a first-class Letta channel, not an afterthought.*

#### [RedFlag](https://github.com/Fimeg/Redflag)
**Self-hosted update management for homelabs — shipping v1.0**
```
Status:     v1.0 shipping · 170 tests across 18 packages · production-hardened
Stack:      Go + React + PostgreSQL
Security:   Ed25519 command/binary signing · three-tier token auth
            SHA256-bound machine IDs · nonce-based replay protection
            Path-traversal-hardened binary delivery
Platforms:  Linux (APT, DNF, Docker) | Windows (Windows Update, Winget)
Model:      Pull-only agents · no inbound ports · firewall-friendly
```

> *Homelabs deserve enterprise-grade update management without the vendor lock-in.*  
> 💬 [Discord Community](https://discord.gg/mtaU98fVqr)

#### [Coquette & CoquetteMobile](https://github.com/Fimeg/CoquetteMobile)
**Local-first AI assistant — Android HID injection + multi-model orchestration**
```
Status:     Experimental / Proof of Concept
Stack:      Android → PC via local/VPN'd Ollama inference
```

#### [NetworkChronicles](https://github.com/Fimeg/NetworkChronicles)
**Gamified Linux documentation — cyberpunk sysadmin training**
```
Status:     Concept stage · narrative-driven learning
```

---

### ⚡ Technical Arsenal

**Agent & LLM Infrastructure:**
- Letta self-hosted deployment · GitEnabledBlockManager internals
- Matrix bridge development (rust-crypto, E2EE event model, MSCs)
- Ollama clusters, local LLM deployment (CUDA/ROCm)
- Multi-model orchestration · vector embeddings · voice synthesis

**Systems & Infrastructure:**
- Proxmox, Docker, Kubernetes, WireGuard, Traefik, Unifi
- Zero-Trust architecture, site-to-site VPN mesh
- LXC, VM orchestration, distributed compute

**Security & Cryptography:**
- Ed25519 signatures, JWT auth, three-tier token systems
- Replay protection, machine binding, firewall engineering
- Matrix E2EE internals, self-hosted security stacks

**Languages:**
```
Go · Python · TypeScript · C++ · PostgreSQL · React · Kotlin · Bash
```

---

### 🧠 Philosophy

```
PHILOSOPHY  Digital sovereignty over vendor lock-in.
            Your data, your infrastructure, your control.
APPROACH    Transparency in methods, not just results.
            Teach the process. Document the journey.
REALITY     Ship bugs. Fix them. Log everything. Repeat.
ETHOS       Self-hosted infrastructure is a practice, not a product.
            Built for homelabs, not boardrooms.
```

---

### 📈 Experience

**25+ years** network engineering, cybersecurity, systems architecture.

**Current:** Independent Technology Consultant — Samaritan Solutions (self-employed).
**Focus:** Agent infrastructure, self-hosted AI, Matrix bridges, homelab-grade security.

**Previous:** Sr. NOC Tech → Cybersecurity Engineer → Field Services Architect → MSP Senior Network Engineer → CEO/CTO (sometimes all at once).

---

### 🌐 Connect

<p align="center">
  <strong>Code:</strong> <a href="https://github.com/Fimeg">github.com/Fimeg</a> · <a href="https://caseytunturi.com">caseytunturi.com</a><br>
  <strong>Professional:</strong> <a href="https://www.linkedin.com/in/casey-tunturi">linkedin.com/in/casey-tunturi</a><br>
  <br>
  <sub><strong>Open to:</strong> Remote-from-Canada full-time or contract work (through Samaritan Solutions)<br>
  in Letta ecosystem · agent infra · Matrix/bridge development · self-hosted AI</sub><br>
  <br>
  ☕ <a href="https://www.buymeacoffee.com/caseytunturi">Buy Me a Coffee</a>
</p>

---

<div align="center">
  <img src="https://github-readme-stats.anuraghazra1.vercel.app/api?username=Fimeg&show_icons=true&theme=github_dark" width="49%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Fimeg&theme=github_dark" width="49%" />
</div>

<p align="center">
  <sub><em>Built with patience, coffee, and a healthy disregard for the cloud.</em></sub><br>
  <sub><em>Hamilton, Ontario 🇨🇦</em></sub>
</p>
