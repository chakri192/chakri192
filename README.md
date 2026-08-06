<div align="center">

<img src="docs/strata.svg" width="860" alt="" />

# V Chakradhar

**Systems and security.** Computer Science undergraduate, Bengaluru.

<p>
  <a href="https://chakradharv.dev"><img alt="Website" src="https://img.shields.io/badge/chakradharv.dev-1c1c1e?style=flat-square&logo=safari&logoColor=white" /></a>
  <a href="https://linkedin.com/in/1chakradhar-v1"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-1c1c1e?style=flat-square&logo=linkedin&logoColor=0A66C2" /></a>
  <a href="mailto:chakradharv08@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-1c1c1e?style=flat-square&logo=gmail&logoColor=EA4335" /></a>
</p>

</div>

---

## About

I build things at the layer below the library — network protocols, data stores, native applications, and embedded firmware — implemented from the specification rather than assembled from packages.

This is a deliberate way to learn. A BitTorrent client that speaks the real wire protocol teaches you what a swarm actually is; a Redis-compatible server that `redis-cli` connects to unmodified teaches you what a wire protocol actually costs. The abstraction has to be gone before the interesting decisions become visible.

Everything below is written, tested, and running. Where I list a test count, it is the number the suite reports.

## Selected work

| Project | Description | Stack | Scale |
|---|---|---|---|
| **[bittorrent-rs](https://github.com/chakri192/bittorrent-rs)** | A complete BitTorrent client built from the specifications — bencode, the BEP 3 peer protocol, trackers over HTTP/HTTPS/UDP, the mainline DHT, PEX, web seeds, rarest-first selection with an endgame, and seeding. Downloads real public torrents to completion and verifies them byte for byte. | Rust | ~10,000 lines · 259 tests |
| **[forge](https://github.com/chakri192/forge)** | A platform for private learning cohorts: task lifecycles, review queues with weighted rubrics, an XP ledger, a voting forum, and cohort analytics with at-risk detection. Built without a frontend framework. | Node · Express · SQLite | ~21,000 lines · 351 tests |
| **[emberkv](https://github.com/chakri192/emberkv)** | A Redis-compatible in-memory data store using only the standard library. RESP2 over real sockets, 59 commands, millisecond TTLs, transactions, pub/sub, and an append-only log that survives a crash mid-write. | Python | ~1,600 lines · 29 tests |
| **[vitrium](https://github.com/chakri192/vitrium)** | A transparent text editor for macOS using compositor-level blur, so the desktop is genuinely visible through the window. Incremental syntax highlighting, atomic saves, per-tab undo. No Electron, no web view. | Swift · AppKit | ~4,200 lines · 53 tests |
| **[ripple](https://github.com/chakri192/ripple)** | A data-incident triage agent for DataHub. Walks downstream lineage across every platform, ranks impact by criticality, resolves owners, and writes the incident back to the catalog as a tag, a runbook, and an Incident entity. | Python · DataHub | ~1,300 lines |
| **[hydra](https://github.com/chakri192/hydra)** | Real-time water level and methane monitoring for sewage chambers, serving its own dashboard from microcontroller flash. The alert threshold lowers automatically when rain is forecast. | ESP8266 · C++ | Firmware + embedded UI |

### Smaller tools, in daily use

[**clipsyncd**](https://github.com/chakri192/clipsyncd) — bidirectional Mac ↔ Android clipboard sync over LAN, with no cloud service in the path.
[**minimal-notifications**](https://github.com/chakri192/minimal-notifications) — clipboard feedback that never needs dismissing, using the native macOS HUD.
[**college-mode**](https://github.com/chakri192/college-mode) — a geofence with hysteresis that manages phone volume by location.
[**m4-sentinel**](https://github.com/chakri192/m4-sentinel) — an Apple Silicon monitor reading thermal and memory pressure through native Mach and notify APIs.
[**dotfile**](https://github.com/chakri192/dotfile) — shell tooling, a modular Neovim configuration, and macOS automation.

## Technical focus

**Languages** — C, Rust, Python, Swift, JavaScript

**Areas** — network protocols and binary formats · concurrency and transactional correctness · macOS and Apple Silicon internals · embedded systems · applied security

**Practice** — implementing against specifications, testing the failure paths rather than the happy ones, and documenting the limits of what I have built as precisely as its capabilities.

## Currently

Studying systems programming in depth — memory, the kernel boundary, and the ways real systems fail. Working primarily in C and Rust.

**Available for internships.** [chakradharv08@gmail.com](mailto:chakradharv08@gmail.com)

<div align="center">
<sub>Full portfolio at <a href="https://chakradharv.dev">chakradharv.dev</a></sub>
</div>
