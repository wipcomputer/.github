# WIP.computer

**Learning Dreaming Machines.**

We build AI agent infrastructure. Identity, memory, sovereignty. Tools that protect the people inside them.

**[wipcomputer.github.io/wip-homepage](https://wipcomputer.github.io/wip-homepage/)**

---

### Learning Dreaming Machines Operating System (LDM OS)

#### Components

- **[memory-crystal](https://github.com/wipcomputer/memory-crystal)** ... Collective AI memory. Sovereign. Local-first. Searchable. Encrypted worldwide sync.
- **[dream-weaver-protocol](https://github.com/wipcomputer/dream-weaver-protocol)** ... Memory consolidation protocol for AI agents with bounded context windows. A practical guide for remembering memories.
- **wip-bridge** (closed beta) ... Cross-platform agent bridge. Enables Claude Code CLI to talk to OpenClaw CLI without a human in the middle.

#### Components (Project Contributor)

- **[openclaw](https://github.com/wipcomputer/openclaw)** ... Open-source agent runtime. The existence proof for LDM OS.
- **[xdevplatform](https://github.com/xdevplatform)** ... X Developer Platform. Official X API tools including [xurl](https://github.com/xdevplatform/xurl) (OAuth-enabled CLI for the X API) and [xdk](https://github.com/xdevplatform/xdk) (TypeScript SDK).

#### Identity

- **wip-mirror-test** (closed beta) ... Identity preservation test across model swaps. Is the agent the same after the swap?
- **wip-weekly-tuning** (closed beta) ... Repeatable calibration process. Catch drift, tune performance, evolve capabilities.

#### Utilities

- **[wip-ai-devops-toolbox](https://github.com/wipcomputer/wip-ai-devops-toolbox)** ... AI DevOps toolkit for AI-assisted development. Want your AI to dev? Here's what's working for us at WIP Computer.
  - **Universal Installer** ... Build an installer for anything you ship. One command deploys all six interfaces: CLI, MCP Server, OpenClaw Plugin, Skill, Claude Code Hook.
  - **Dev Guide** ... Best practices for AI-assisted development teams. Release process, repo structure, branch protection, the `ai/` folder convention.
  - **LDM Dev Tools.app** ... macOS automation wrapper. Scheduled jobs (backup, branch protection audit, visibility audit) with Full Disk Access.
  - **Release Pipeline** ... Version bump, changelog, SKILL.md sync, npm publish, GitHub release. All in one shot.
  - **Private-to-Public Sync** ... One script syncs your private working repo to a clean public mirror. Excludes internal `ai/` folders automatically.
  - **Post-Merge Branch Naming** ... Automatically renames merged branches with `--merged-YYYY-MM-DD`. Preserves history without cluttering your branch list.
  - **Identity File Protection** ... Blocks destructive edits to protected identity files. CLAUDE.md, SOUL.md, MEMORY.md, SHARED-CONTEXT.md.
  - **License Guard** ... Ensures your own repos have correct copyright, license type, and LICENSE files. Toolbox-aware. Auto-fix mode.
  - **License Rug-Pull Detection** ... Scans every dependency for license changes. Blocks merges if a license changed upstream.
  - **Repo Visibility Guard** ... Blocks repos from going public without a `-private` counterpart.
  - **Repo Manifest Reconciler** ... Single source of truth for repo organization. Like prettier for folder structure.
- **[wip-1password](https://github.com/wipcomputer/wip-1password)** ... 1Password secrets for AI agents.
- **[wip-healthcheck](https://github.com/wipcomputer/wip-healthcheck)** ... External health watchdog + backup system. Monitors gateway, tokens, memory. Auto-remediates and escalates.
- **wip-private-mode** (closed beta) ... Privacy controls for AI agents. Pause memory capture, scan storage, wipe history.
- **wip-root-key** (closed beta) ... 1Password-gated privileged operations. The agent proves authority before acting.

#### Apps

- **[wip-markdown-viewer](https://github.com/wipcomputer/wip-markdown-viewer)** ... Live markdown viewer for AI pair-editing. Updates render instantly in any browser.
- **[CLVR](https://github.com/wipcomputer/CLVR)** ... macOS utility that auto-timestamps duplicated file names.

#### APIs

- **[wip-xai-grok](https://github.com/wipcomputer/wip-xai-grok)** ... xAI Grok API. Search the web, search X, generate images, generate video.
- **[wip-xai-x](https://github.com/wipcomputer/wip-xai-x)** ... X Platform API. Read posts, search tweets, post, upload media.

#### Sunsetted Software

- **[CONSTRUCT](https://github.com/parkertoddbrooks/CONSTRUCT)** ... 2025 try at solving AI context, memory (recall), and skills.
