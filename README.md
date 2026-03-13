# m0rs3c0d3

Engineer, full-stack developer, creator. 20+ years writing code across the full stack, from product interfaces down to the systems layer where most people stop looking.

I specialize in security engineering and AI tooling, but the through-line is the same regardless of the domain: understand how things actually work, then build something worth using. The projects here reflect that. Not tutorials repackaged as repos, but tools built to solve real problems at the layer where the interesting ones live.

---

## Security Tooling

### [Glasswally](https://github.com/m0rs3c0d3/glasswally)
**Real-time LLM distillation attack detection via eBPF kernel uprobes.**  
Hooks into inference processes at the kernel boundary. Fingerprints query patterns. Alerts before a model theft completes. MITRE ATT&CK mapped.  
`Rust` · `eBPF` · `Detection Engineering` · `AI Security`

---

### [Milly](https://github.com/m0rs3c0d3/milly)
**The first local LLM with a built-in security layer.**  
HMAC-signed memory. TF-IDF RAG. Air-gapped by design. Zero egress. 136 passing tests covering memory integrity, injection resistance, and audit logging.  
`Python` · `Ollama` · `AI Security`

---

### [ghostwire](https://github.com/m0rs3c0d3/ghostwire)
**Passive USB device fingerprinting and anomaly detection daemon.**  
Detects BadUSB implants, HID injection devices, and hardware anomalies at the enumeration layer — before the OS finishes booting the driver. Silent. Rust. No kernel module required.  
`Rust` · `Linux` · `Endpoint Security` · `Hardware Fingerprinting`

---

### [EverythingOS](https://github.com/m0rs3c0d3/everythingos)
**Security-first multi-agent framework for autonomous systems.**  
ModelGuard input/output validation. DecisionLedger audit trail. NIST AI RMF aligned. 81/81 tests passing, zero TypeScript errors. Built under the Robots For Peace framework.  
`TypeScript` · `Autonomous Agents` · `AI Governance`

---

## Other Work

| Project | Description |
|--------|-------------|
| [Durpie](https://github.com/m0rs3c0d3/durpie) | Modular web security testing toolkit built on mitmproxy |
| [UAP-51](https://github.com/m0rs3c0d3/uap-51) | Autonomous flight simulator in React / Three.js |
| [retro-os](https://github.com/m0rs3c0d3/retro-os) | Working retro OS with games, runs in the browser |
| [prism-video-synth](https://github.com/m0rs3c0d3/prism-video-synth) | Mobile-optimized video synthesizer in React |
| [pulse-drum-machine](https://github.com/m0rs3c0d3/pulse-drum-machine) | MIDI-capable drum machine for desktop and mobile |

---

## Stack

`Rust` · `Python` · `TypeScript` · `JavaScript` · `React` · `Three.js` · `eBPF` · `mitmproxy` · `Ollama`

Kernel-level tooling · Detection engineering · AI security · Autonomous systems · Creative coding

---
> *The purpose is not just to build tools — but to fully understand how they work and why. Running them is not enough.*
