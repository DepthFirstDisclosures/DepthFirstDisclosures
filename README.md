# depthfirst Disclosures
## Vulnerabilities
A log of vulnerabilities [DepthFirst](https://www.depthfirst.com/) has reported and responsibly disclosed. depthfirst contributes and patches when project's security policys allow.

* CVE-2025-59304 [Swetrix Web Analytics RCE](https://www.depthfirst.com/post/anatomy-of-an-automated-patch-fixing-a-file-upload-rce-cve-2025-59304) | [depthfirst Patch](https://github.com/Swetrix/swetrix/pull/397)
* CVE-2025-59305 [Langfuse Data Corruption and Denial of Service](https://www.depthfirst.com/post/how-an-authorization-flaw-reveals-a-common-security-blind-spot-cve-2025-59305-case-study)
* CVE-2025-59419 [Netty Library Email Authentication Bypass SMTP Injection](https://www.depthfirst.com/post/our-ai-agent-found-a-netty-zero-day-that-bypasses-email-authentication-the-story-of-cve-2025-59419) | [depthfirst Patch](https://github.com/netty/netty/commit/1782e8c2060a244c4d4e6f9d9112d5517ca05120)
* [CVE Pending] [Bludit CMS Authentication Bypass](https://github.com/bludit/bludit/pull/1616) | [depthfirst Patch](https://github.com/bludit/bludit/pull/1616)
* [CVE Pending] [Bludit CMS RCE via Webhook Secret Bypass](https://github.com/bludit/bludit/pull/1617) | [depthfirst Patch](https://github.com/bludit/bludit/pull/1617)
* [CVE Pending] [XORM Database Library (used by Grafana) Arbitrary Data Manipulation](https://gitea.com/xorm/xorm/commit/b21bdb9872f6a9a5a01fef131a1a48d0e5485354) | [depthfirst Patch](https://gitea.com/xorm/xorm/commit/b21bdb9872f6a9a5a01fef131a1a48d0e5485354)
* [CVE Pending] [Expensify Secure Authorization Bypass](https://github.com/Expensify/App/commit/bb4d19c5585b93582013437590fe498efe8866f8)
* CVE-2025-64721 [Sandboxie Sandbox Escape & Privilege Escalation to SYSTEM](https://github.com/sandboxie-plus/Sandboxie/security/advisories/GHSA-w476-j57g-96vp)
* CVE-2025-14986 Temporal Cross-Tenant Data Leak and Policy Bypass
* [CVE Pending] [Walkdir Rust Library Symlink traversal and Defensive Bypass](https://github.com/BurntSushi/walkdir/issues/209)
* [CVE Pending] [OpenClaw/MoltBot/ClawdBot 1-Click RCE](https://github.com/openclaw/openclaw/security/advisories/GHSA-g8p2-7wf7-98mq)
* [CVE Pending] [Fully Redacted (unpatched)]
* [CVE Pending] [Fully Redacted (unpatched)]
* [CVE Pending] [Fully Redacted (unpatched)]

_Unpatched vulnerabilities remain private until vendors have had the opportunity to release fixes._

## Open Source Project Contributions
Security-adjacent bugs found and fixed by depthfirst in OSS
* [Esbuild XSS via foldername on dev server](https://github.com/evanw/esbuild/pull/4316#event-20653677937)

## Disclosure Policy
We follow a [90 day disclosure standard](https://depthfirst.com/post/our-approach-to-coordinated-vulnerability-disclosure)
