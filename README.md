# Bobby Blanco

**Builder of operating systems, recovery tools, creative platforms, and story worlds.**

I build software under **Bobby’s Workshop** and **Blue Phoenix Studios**, with one rule running through the entire portfolio:

> **Evidence before adjectives.** A product earns words like secure, reliable, compatible, polished, and production-ready through working code, retained tests, and honest limitations.

## Flagship systems

### ARCWYRE Native
A from-scratch x86_64 operating-system program built around the Phoenix Prime Kernel, protected userspace, verifiable recovery, and owner-controlled computing.

**Current verified baseline:** long-mode kernel boot, content-addressed initramfs validation, and a separate ELF64 process executing at CPL3 under QEMU. ARCWYRE remains active systems research, not a public production release.

### [PhoenixCore](https://github.com/Bboy9090/PhoenixCore-)
Device intelligence, diagnostics, repair planning, evidence orchestration, and cross-device coordination for the Bobby’s Workshop ecosystem.

### [Phoenix Key / BootForge](https://github.com/Bboy9090/Bootforge-usb)
Rust-powered USB discovery and the safe desktop foundation for signed boot and recovery media. Read-only detection and explicit safety boundaries come first.

### [Bobby’s Workshop](https://github.com/Bboy9090/Bobbys-Workshop-)
The human-facing repair and recovery workspace that brings diagnostics, guided workflows, case records, evidence, and approved device actions into one professional interface.

## Flagship apps and worlds

### [Soul Codex](https://github.com/Bboy9090/Ultimate-SoulCodex)
A personal insight platform combining astrology, numerology, Human Design, compatibility, daily guidance, web, and mobile delivery.

### [Legends of Kai-Jax: The Memory Hero](https://github.com/Bboy9090/Legends-of-Kai-Jax-The-memory-Hero)
A mythic platform-fighter and story universe centered on memory, identity, transformation, and original beast-hybrid heroes.

### [Phoenix Creator Studio](https://github.com/Bboy9090/SagaArchitect)
A production and canon platform for characters, factions, timelines, scenes, storyboards, lore rules, and franchise-scale creative workflows.

### [Ghost Writer](https://github.com/Bboy9090/GhostWriter-)
An AI-assisted writing, OCR, research, editing, and publishing studio with unit, end-to-end, performance, and desktop workflow foundations.

### [Rainstorms](https://github.com/Bboy9090/Rainstorms)
A story-generation platform for turning ideas into structured children’s-book drafts and creative production assets.

## Cybersecurity & Defensive Engineering

- **Focus Areas:** Endpoint Detection & Response (macOS/Linux), Sigma Detection Engineering, Offline PCAP / Suricata Analysis, Read-Only DFIR Triage & Chain of Custody, STIX 2.1 Threat Intel, and CIS / NIST CSF 2.0 Posture Auditing.
- **Languages:** Python (zero-dependency deterministic pipelines), Rust (native endpoint & USB/boot primitives), Swift/SwiftUI (Universal macOS 11+ apps).
- **Verified Public Security Laboratories:**
  - [Ghostwire Detection Lab](https://github.com/Bboy9090/ghostwire-detection-lab) — Sigma YAML detection engine, versioned `v2.0.0` security event schema, bounded queue telemetry-loss visibility, and deterministic replay (`11/11` unit tests pass)
  - [Ghostwire DFIR Toolkit](https://github.com/Bboy9090/ghostwire-dfir-toolkit) — Read-only file triage, magic-byte identification, SHA-256 chain of custody, and tamper-evident JSON/Markdown case exports (`1/1` unit test passes)
  - [Ghostwire Network Defense Lab](https://github.com/Bboy9090/ghostwire-network-defense-lab) — Bounded offline PCAP parser, Suricata EVE JSON ingestion, Shannon-entropy DNS heuristics, and host process correlation (`4/4` unit tests pass)
  - [Bag of OS X and iOS Security Tools](https://github.com/Bboy9090/Bag-of-osx-and-ios-security--tools) — Curated Apple security & defensive tooling collection

## Tools, games, and laboratories

- [Atlas Verify](https://github.com/Bboy9090/atlas-verify) — case-based verification and research tooling
- [REFORGE OS](https://github.com/Bboy9090/REFORGE-OS) — repair and restoration experience research
- [Super Bobby’s World of Secret Rooms](https://github.com/Bboy9090/Super_Bobbys_World_of_Secret_Rooms) — interactive game and world experimentation
- [Velocity Systems](https://github.com/Bboy9090/VelocitySystems) — performance and systems experiments
- [Put Together](https://github.com/Bboy9090/Puttogether) — early product exploration

Private laboratories include Sonic Codex, Universal Cart, Dad’s Million Miles, patient-care product research, and additional workshop experiments.

## How the ecosystem fits together

```text
Blue Phoenix Studios
└── Bobby’s Workshop
    ├── ARCWYRE Native        from-scratch operating system
    ├── PhoenixCore           diagnostics and recovery intelligence
    ├── Phoenix Key           safe boot and recovery media experience
    ├── BootForge             reusable USB and boot primitives
    ├── Soul Codex            personal insight platform
    ├── Phoenix Creator Studio creative production and canon platform
    ├── Ghost Writer          writing and publishing studio
    └── Original worlds       Kai-Jax, Rainstorms, and future franchises
```

Each flagship remains a separate product and repository. Shared low-level components use versioned contracts instead of being silently copied into whichever repository last declared itself the center of the universe.

## Fan-favorite product standard

Every flagship is being developed toward the same long-term standard:

- a memorable identity and unmistakable purpose
- a fast, accessible, delightful first-run experience
- stable builds and reproducible release evidence
- strong onboarding, screenshots, demos, and documentation
- tests for happy paths, failures, recovery, and data safety
- consistent design language without making every product look identical
- community-ready issue templates, contribution paths, changelogs, and roadmaps
- honest status labels and no fictional completion percentages

See the [Fan-Favorite Product Standard](docs/FAN_FAVORITE_PRODUCT_STANDARD.md) for the portfolio-wide quality gates.

## Current focus

1. ARCWYRE R12 protected userspace and fault containment
2. PhoenixCore and Phoenix Key contract cleanup and hardware-proof lanes
3. Soul Codex mobile release quality
4. Kai-Jax movement, combat feel, continuity, and playable vertical slices
5. Phoenix Creator Studio production-readiness and creator delight
6. Portfolio-wide README, CI, security, release, accessibility, and visual polish

## Philosophy

**Build tools that empower people.**  
**Make complexity understandable.**  
**Design recovery before failure arrives.**  
**Treat polish as engineering, not decoration.**  
**Let the code, tests, users, and evidence decide when something is ready.**
