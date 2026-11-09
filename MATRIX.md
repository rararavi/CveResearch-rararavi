# CVE Matrix

| Date | Platform | Category | CVE | Trigger | Public PoC | Status | Folder | Notes |
|---|---|---|---|---|---|---|---|---|
| YYYY-MM-DD | Android | rce | CVE-YYYY-XXXXX | browser/file | yes/no | pass/fail/replaced | `android/rce/CVE-YYYY-XXXXX/` | |
| 2026-11-07 | Linux | rce | CVE-2026-109619 | browser_page | yes | replaced | `linux/rce/CVE-2026-109619/` | Config-driven `serialize_handler` mismatch only; stale-state path NOT reproduced (verified 2026-11-09, PHP 8.2.34/8.2.35 via Docker); replaced |
| 2026-11-09 | Linux | info_leak | CVE-2025-29927 | browser_page | yes | pass | `linux/info_leak/CVE-2025-29927/` | Next.js middleware bypass (`x-middleware-subrequest`) -> protected PII; 14.2.24 vuln / 14.2.25 control blocked; verified via Docker (`run.sh`) + browser screenshot |
