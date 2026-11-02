# Command Prompt (CMD) Quick Reference

Open Command Prompt from Start. Use a standard, non-elevated session unless an approved procedure explicitly requires otherwise.

| Command | Use |
|---|---|
| `hostname` | Displays the computer name. Treat it as internal information; do not publish it without permission. |
| `whoami` | Displays the current signed-in account context. Do not share account identifiers publicly. |
| `systeminfo` | Displays operating-system and system configuration details. Review output before sharing. |
| `ipconfig` | Displays IP configuration. |
| `ipconfig /all` | Displays detailed network adapter configuration; sanitize output. |
| `ping <host>` | Tests ICMP reachability; ICMP may be blocked. |
| `nslookup <name>` | Queries DNS. |
| `tracert <host>` | Displays route hops toward a destination. |
| `tasklist` | Lists running processes. |
| `chkdsk` | Checks file system/volume status; repair options may require downtime and authorization. Do not run repair switches casually. |

## Practice safely
Use `hostname`, `systeminfo` and `ipconfig` on your own lab device. Review output locally and do not upload serial numbers, usernames, IP addresses, MAC addresses or other sensitive values.
