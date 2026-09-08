## Hi, I'm Carry

Infra engineer · Open source contributor · [www.ranisa.cn](https://www.ranisa.cn)

---

### Open Source Contributions

**Merged**

| Project | Contribution | Landed |
|---|---|---|
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [fix(terminal): scope environment cache by session key to prevent cross-profile SSH leakage](https://github.com/NousResearch/hermes-agent/pull/30861) — commands typed in one profile silently executed on another profile's SSH host<br><sub>landed via salvage PR [#92156](https://github.com/NousResearch/hermes-agent/pull/92156), authorship preserved</sub> | [`a270c4a`](https://github.com/NousResearch/hermes-agent/commit/a270c4adea) · [`8a963e8`](https://github.com/NousResearch/hermes-agent/commit/8a963e85123e5e2ac3fb7df399c4c35603d1e1c3) |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [fix(doctor): SSH connectivity check ignores TERMINAL_SSH_USER / PORT / KEY](https://github.com/NousResearch/hermes-agent/pull/26851) — `hermes doctor` reported SSH unreachable on any host using a non-default user, port or key<br><sub>landed via batch salvage PR [#27382](https://github.com/NousResearch/hermes-agent/pull/27382); credited in `scripts/release.py` AUTHOR_MAP</sub> | [`c9298bb`](https://github.com/NousResearch/hermes-agent/commit/c9298bba06) |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [fix(skills): stop syncing bookkeeping dirs (.hub, .archive, backups) to sandboxes](https://github.com/NousResearch/hermes-agent/pull/96474) — 85% smaller sandbox sync payload; oversized uploads were blowing the SSH backend's 120s deadline<br><sub>landed via salvage PR [#101571](https://github.com/NousResearch/hermes-agent/pull/101571) ([rebase-merge, cherry-picked with authorship preserved](https://github.com/NousResearch/hermes-agent/pull/96474#issuecomment-5515642554))</sub> | [`602c9d9`](https://github.com/NousResearch/hermes-agent/commit/602c9d91b11c942ff944e2197b227f939b54da99) |
| [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) | [fix: prevent state.db messages being silently dropped during sidecar merge](https://github.com/nesquena/hermes-webui/pull/2788) | v0.51.121 |
| [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) | [fix(agent_health): detect profile-scoped gateway.pid to fix false "Gateway not configured"](https://github.com/nesquena/hermes-webui/pull/2927) | v0.51.135 |
| [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) | [fix(reasoning): expose effort levels for bare/dot-separated model names on custom providers](https://github.com/nesquena/hermes-webui/pull/3202) | v0.51.179 |
| [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) | [fix(reasoning): normalize custom-provider model ids for fallback detection](https://github.com/nesquena/hermes-webui/pull/3327) | v0.51.198 |
| [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) | [fix: don't stash clarify draft while submission is in progress](https://github.com/nesquena/hermes-webui/pull/3651) | v0.51.268 |
| [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) | [feat(config): expand `${VAR}` references in config.yaml at load time](https://github.com/nesquena/hermes-webui/pull/3736) | v0.51.303 |

**In review**

| Project | Contribution | Status |
|---|---|---|
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [fix(agent): stop treating TERMINAL_CWD as a local path on remote backends](https://github.com/NousResearch/hermes-agent/pull/100189) | 🟡 open |

---

### Skills

`Linux` `Python` `Shell` `SSH` `Docker` `CasaOS` `Ansible`
