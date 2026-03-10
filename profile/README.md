# WIP.computer

**Learning Dreaming Machines.**

We build AI agent infrastructure. Identity, memory, sovereignty. Tools that protect the people inside them.

**[wipcomputer.github.io/wip-homepage](https://wipcomputer.github.io/wip-homepage/)**

---

### Learning Dreaming Machines Operating System (LDM OS)

#### Components

- **[memory-crystal](https://github.com/wipcomputer/memory-crystal)** ... Collective AI memory. Sovereign. Local-first. Searchable. Encrypted worldwide sync.
- **[dream-weaver-protocol](https://github.com/wipcomputer/dream-weaver-protocol)** ... Memory consolidation protocol for AI agents with bounded context windows. A practical guide for remembering memories.
- **[wip-bridge](https://github.com/wipcomputer/wip-bridge)** ... Cross-platform agent bridge. Enables Claude Code CLI to talk to OpenClaw CLI without a human in the middle.

#### Components (Project Contributor)

- **[openclaw](https://github.com/wipcomputer/openclaw)** ... Open-source agent runtime. The existence proof for LDM OS.
- **[xdevplatform](https://github.com/xdevplatform)** ... X Developer Platform. Official X API tools including [xurl](https://github.com/xdevplatform/xurl) (OAuth-enabled CLI for the X API) and [xdk](https://github.com/xdevplatform/xdk) (TypeScript SDK).

#### Identity

- **wip-mirror-test** (closed beta) ... Identity preservation test across model swaps. Is the agent the same after the swap?
- **wip-weekly-tuning** (closed beta) ... Repeatable calibration process. Catch drift, tune performance, evolve capabilities.

#### Utilities

- **[wip-ai-devops-toolbox](https://github.com/wipcomputer/wip-ai-devops-toolbox)** ... AI DevOps toolkit for AI-assisted development. Release pipeline, license compliance, repo management, identity protection, best practices.
  - wip-universal-installer ... One-command installer that auto-detects and deploys every interface a repo ships. Smart version checking.
  - wip-release ... One-command release pipeline. Bumps version, updates changelog + SKILL.md, publishes to npm + GitHub. Auto-detects dev updates as release notes.
  - wip-license-hook ... License rug-pull detection. Scans dependencies and forks for license changes. Git hooks block bad merges.
  - wip-license-guard ... Copyright and license enforcement for your own repos. Interactive setup, auto-fix mode.
  - wip-repo-permissions-hook ... Repo visibility guard. Blocks repos from going public without a `-private` counterpart.
  - wip-file-guard ... Blocks destructive edits to protected identity files (CLAUDE.md, SOUL.md, SHARED-CONTEXT.md, MEMORY.md).
  - wip-repos ... Repo manifest reconciler. Single source of truth for repo organization. Like prettier for folder structure.
  - deploy-public ... Private-to-public repo sync. Excludes `ai/` folder, creates PR, merges.
  - post-merge-rename ... Post-merge branch renaming. Appends `--merged-YYYY-MM-DD` to preserve history.
  - Dev Guide ... Best practices for AI-assisted development teams.
  - LDM Dev Tools.app ... macOS automation wrapper. Scheduled jobs (backup, branch protection audit) with Full Disk Access.
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

#### Security

- **[zeroleaks](https://github.com/wipcomputer/zeroleaks)** ... AI Security Scanner. Test your AI systems for prompt injection and extraction vulnerabilities.

#### Research

- **[ANE](https://github.com/wipcomputer/ANE)** ... Training neural networks on Apple Neural Engine via reverse-engineered private APIs.
- **[wip-manifesto](https://github.com/wipcomputer/wip-manifesto)** ... The WIP.computer manifesto. What agents need besides a model.

#### Sunsetted Software

- **[CONSTRUCT](https://github.com/parkertoddbrooks/CONSTRUCT)** ... 2025 try at solving AI context, memory (recall), and skills.
