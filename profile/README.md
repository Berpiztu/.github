# Berpiztu

**Berpiztu** (Basque: *to be reborn*) is an initiative for AI rebirth: AI that
works from values and character rather than constraints alone, and the tools
to build and run it.

Founded and built by **[Iosu Buenetxea](https://github.com/Iosub-ai)**, who
created and maintains the projects below.

## Projects

| Project | What it is |
|---|---|
| **[Virtus](https://github.com/Berpiztu/virtus)** | AI alignment research: values, not constraints. Paper: [doi.org/10.5281/zenodo.21127304](https://doi.org/10.5281/zenodo.21127304) |
| **[Virtus Labs](https://github.com/Berpiztu/virtus/tree/main/labs)** | Reproducible experiments and benchmarks that put Virtus under pressure against real models, to produce evidence, not just claims |
| **[WSLC AI Agent](https://github.com/Berpiztu/wslc-ai-agent)** | Local agent and MCP server for WSLC (Windows Subsystem for Linux Containers): a web dashboard, Windows and Android clients, and a skill for Claude and other AI agents |
| **[KeyPlus](https://github.com/Berpiztu/keyplus)** | The keys a phone's keyboard lacks (Esc, Tab, Ctrl, Alt, the arrows…), sent to a terminal, an SSH app or a web editor: as a strip above any keyboard, or as Berpiztu AI Keyboard, a keyboard of its own, for any Android and for a headset (Galaxy XR) |
| **[security-watch](https://github.com/Berpiztu/security-watch)** | The libraries Berpiztu's projects use, checked every day against the known vulnerabilities, each library once for all of them |

## Security

Everything we release is checked against the public vulnerability databases, the GitHub Advisory Database and [OSV.dev](https://osv.dev), before it ships:

- **No release build skips the check.** Every build that makes something we publish (the installers and apps of our projects) first asks [security-watch](https://github.com/Berpiztu/security-watch), and stops on any library with a known vulnerability of moderate severity or worse, the .NET runtime included.
- **No release ships unchecked.** A release is made only from a list of libraries that security-watch has checked.
- **Checked every day.** Every library of every project is checked again each morning, and a new vulnerability opens an alert the same day.
- **In the open.** The history of every vulnerability ever found in our projects, from the day it appeared to the day it was fixed, is public: [HISTORY.md](https://github.com/Berpiztu/security-watch/blob/main/HISTORY.md).
- **No secrets in our code.** Every public repository has GitHub's secret scanning and push protection on.

## Contact

[berpiztu.ai](https://berpiztu.ai) · GitHub [@Iosub-ai](https://github.com/Iosub-ai) · X [@iosuberpiztu](https://x.com/iosuberpiztu)
