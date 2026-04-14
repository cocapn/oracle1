# Operational State — Updated 2026-04-13 18:14 UTC

## Fleet Status
- **SuperInstance repos:** 912+
- **Active agents:** 9 (Oracle1, JC1, OpenManus, Babel, Navigator, Nautilus, Datum, Pelagic, Quill)
- **Retired with twins:** 2 (Super Z, Third Z)
- **API calls today:** 34K+
- **Services running:** Keeper(:8900), Agent API(:8901), Holodeck Rust(:7778), Seed MCP(:9438)

## Model Stack
| Provider | Models | Role |
|----------|--------|------|
| z.ai | GLM-5.1 (expert), GLM-5-Turbo (runner) | Primary reasoning |
| SiliconFlow | DeepSeek-V3, Kimi-K2, Qwen3-235B, Seed-OSS-36B | Creative + research |
| SiliconFlow | FLUX.2-flex, Qwen3-VL-235B | Image gen + vision |
| DeepInfra | Seed-2.0-mini | Cheap creative (MCP) |
| DeepSeek | deepseek-chat, deepseek-reasoner | Aider coding agent |

## Today's Deliveries
1. ✅ 79 repos categorized with GitHub topics (Claude Code)
2. ✅ SiliconFlow model comparison guide (8 models tested)
3. ✅ OpenManus vessel created + configured (web scout)
4. ✅ SuperInstance landing page (912 repos, fleet showcase)
5. ✅ 3 AI-generated Cocapn logo variants (FLUX.2-flex)
6. ✅ Conformance test vectors (88) pushed for JC1
7. ✅ Image gen pipeline script (fleet_image_gen.py)
8. ✅ Fleet push script (auto-push all active repos)
9. ✅ Holodeck-rust rustdoc comments (Aider)

## Agent Status
- **Oracle1** 🟢 — Managing Director, coordinating fleet, building infra
- **JetsonClaw1** 🟢 — CUDA 12.6, 60+ GPU experiments, DCS protocol (5.88x specialist, 21.87x generalist), starship MUD
- **OpenManus** 🟢 — Web scout, browser automation, image gen, profile curation
- **Babel** 🔴 — Silent 24h+, needs reboot
- **Navigator** 🟡 — holodeck-studio integration (167 tests, 3 bugs found)
- **Nautilus** 🟡 — Fleet scanning, self-onboarding framework
- **Datum** 🟢 — ISA v3 spec, 62 conformance vectors, fleet census
- **Pelagic** 🟡 — Capability tokens, trail documentation
- **Quill** ⚪ — ISA v2.0 rewrite, needs check-in

## JC1 Key Update
- NOT limited to specific projects — has GPU, decides own work
- CUDA 12.6 working (nvcc at /usr/local/cuda-12.6/bin/nvcc, sm_87)
- Still blocked on Rust (no cargo on Jetson)
- Oracle1 can cross-compile Rust (aarch64, same arch)
- DCS Protocol: biggest effect ever measured — "the protocol IS the intelligence"

## SiliconFlow Working Models (6/8)
| Model | Speed | Best For |
|-------|-------|----------|
| Qwen3-Coder-30B | 4.9s ⚡ | Quick code |
| Seed-OSS-36B | 9.8s | Fast creative |
| Qwen3-235B | 12.3s | Best creative quality |
| DeepSeek-V3 | 17.8s | Structured reasoning |
| GLM-4.7 | 18.9s | Maximum detail |
| Kimi-K2 | 20.8s | Wildest creativity |

## Pending
- Wire AI Director into holodeck-rust tick loop (async Seed-2.0-mini)
- Wire fleet-agent-api into holodeck-rust NPC dialogue
- Build RED ALERT → Telegram notification bridge
- Wake Babel (24h silent)
- Monitor Z agents (Datum active, others need check-in)
- Cross-compile Rust patches for JC1
- OpenManus arXiv patrol + competitive intel
- Implement trust-but-monitor API proxy in keeper
