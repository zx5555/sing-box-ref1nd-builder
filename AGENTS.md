# AGENTS.md — sing-box reF1nd Builder Governance

## 1. Project Overview
- **Repository**: `zx5555/sing-box-ref1nd-builder`
- **Domain**: Automated CI/CD kernel building for Android ARM64 (`sing-box` reF1nd branch).
- **Deliverables**: Daily scheduled check + manual dispatch matrix builds (Stable / Testing), releases to GitHub Releases and Discord webhook/bot dispatch.

## 2. Invariants & Rules
- Target architecture: `Android arm64` (`API 35`, `NDK r29`, `Go 1.24`).
- Compiler tags: `with_quic,with_utls,with_clash_api,with_ebpf,with_tailscale,badlinkname,tfogo_checklinkname0`.
- All automated notification must remain silent-on-green except explicit status card dispatch to Discord.
