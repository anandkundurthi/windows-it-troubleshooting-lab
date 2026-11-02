# PowerShell Quick Reference

Open Windows PowerShell or PowerShell from Start. These examples are primarily for inspection.

| Command | Use |
|---|---|
| `Get-ComputerInfo` | Displays computer and OS information. Output can contain identifying details. |
| `Get-Process` | Lists running processes. |
| `Get-Service` | Lists Windows services and their status. |
| `Get-NetIPConfiguration` | Displays network interface IP configuration. |
| `Test-Connection example.com -Count 4` | Performs a ping-like connectivity test; ICMP may be blocked. |
| `Resolve-DnsName example.com` | Queries DNS for a name. |
| `Get-EventLog -LogName System -Newest 20` | Reads recent entries from the classic System event log where available. |

## Safety
Do not use `Stop-Process`, `Stop-Service`, `Set-*`, `Remove-*`, execution-policy changes or administrator elevation as routine first-line troubleshooting. State-changing commands require a clear reason, authorization and an approved rollback/escalation path.

## Practice record
- Command:
- Purpose:
- Expected type of output:
- Actual observation:
- Sensitive fields removed before sharing:
