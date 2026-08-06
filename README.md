<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=460&lines=hey%2C+i'm+chakri;systems+%26+security;from+scratch%2C+mostly" alt="hey, I'm chakri — systems and security" />

**First-year CSE undergrad in Bengaluru.** I like the layer below the library.

<p>
  <a href="https://chakradharv.dev"><img alt="Website" src="https://img.shields.io/badge/chakradharv.dev-1c1c1e?style=flat-square&logo=safari&logoColor=white" /></a>
  <a href="https://linkedin.com/in/1chakradhar-v1"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-1c1c1e?style=flat-square&logo=linkedin&logoColor=0A66C2" /></a>
  <a href="mailto:chakradharv08@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-1c1c1e?style=flat-square&logo=gmail&logoColor=EA4335" /></a>
</p>

<p>
  <img alt="C" src="https://img.shields.io/badge/C-1c1c1e?style=flat-square&logo=c&logoColor=A8B9CC" />
  <img alt="Rust" src="https://img.shields.io/badge/Rust-1c1c1e?style=flat-square&logo=rust&logoColor=DEA584" />
  <img alt="Python" src="https://img.shields.io/badge/Python-1c1c1e?style=flat-square&logo=python&logoColor=3776AB" />
  <img alt="Swift" src="https://img.shields.io/badge/Swift-1c1c1e?style=flat-square&logo=swift&logoColor=F05138" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-1c1c1e?style=flat-square&logo=javascript&logoColor=F7DF1E" />

</p>

<br />

<img src="docs/strata.svg" width="860" alt="" />

</div>

<br />

---

### What I'm actually interested in

Writing the thing instead of importing it. Not out of principle — because the layer underneath is where the interesting decisions are, and you don't find them until the abstraction is gone.

Some of what that turned into:

**[bittorrent-rs](https://github.com/chakri192/bittorrent-rs)** — a complete BitTorrent client in Rust. Bencode parser, the BEP 3 peer protocol, trackers over HTTP/HTTPS/UDP, the mainline DHT, PEX, web seeds, rarest-first with an endgame, and seeding. It pulls real public torrents to completion — a 21 GB file, verified byte for byte — then serves them back. ~10k lines, 256 tests, no crate doing the actual work.

**[emberkv](https://github.com/chakri192/emberkv)** — a Redis-compatible data store in pure Python, standard library only. Real RESP2 over a real socket, 59 commands, TTLs, transactions, pub/sub, and an append-only log that survives a crash mid-write. `redis-cli` and `redis-py` can't tell the difference.

**[vitrium](https://github.com/chakri192/vitrium)** — a genuinely transparent text editor for macOS. `NSVisualEffectView` in `.behindWindow` mode, so the compositor samples what is actually behind the window; drag it across your wallpaper and the glass changes with it. Native AppKit, zero dependencies, and no Electron anywhere near it.

**[forge](https://github.com/chakri192/forge)** — an operating system for a private learning cohort. Tasks and review queues, XP and badges, a voting forum, duels with escrowed stakes, teacher analytics. Express over SQLite with a vanilla ES-module client — no frontend framework at all. 351 tests.

**[hydra](https://github.com/chakri192/hydra)** — an ESP8266 watching water level and methane in a sewage chamber, serving its own multi-node dashboard out of `PROGMEM`. The alert threshold drops on its own when rain is in the forecast.

And the small ones that get used daily: [minimal-notifications](https://github.com/chakri192/minimal-notifications) for clipboard feedback that never needs dismissing, [clipsyncd](https://github.com/chakri192/clipsyncd) for Mac↔Android clipboard sync with no cloud in the path, [dotfile](https://github.com/chakri192/dotfile) for the machine itself, and [college-mode](https://github.com/chakri192/college-mode), which turns my phone down when I walk into college.

---

### Currently

Learning systems programming properly — memory, the kernel boundary, and how things actually fail. Reading more C and Rust than anything else.

**Open to internships.** [chakradharv08@gmail.com](mailto:chakradharv08@gmail.com)

<div align="center">
<br />
<sub>Everything above is at <a href="https://chakradharv.dev">chakradharv.dev</a> — or as a shell you can type into.</sub>
</div>
