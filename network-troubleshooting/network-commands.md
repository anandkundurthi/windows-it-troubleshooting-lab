# Basic Network Command Reference

Run these commands in Command Prompt. Use only on a device/network you are authorized to troubleshoot.

| Command | Purpose | Notes |
|---|---|---|
| `ipconfig` | Shows IP configuration | Start with the active adapter. |
| `ipconfig /all` | Shows detailed adapter configuration | Sanitize addresses and adapter identifiers before sharing. |
| `ping <host>` | Tests basic IP reachability and round-trip response | Firewalls or hosts may block ICMP; failure is not proof the host is down. |
| `nslookup <name>` | Queries DNS for a hostname | Useful for name-resolution checks. |
| `tracert <host>` | Displays the route path toward a destination | Some hops may not respond; interpret carefully. |
| `pathping <host>` | Combines route and packet-loss analysis | Can take time and may be blocked by policy. |

## Example commands

```cmd
ipconfig
ipconfig /all
ping example.com
nslookup example.com
tracert example.com
```

## Evidence to record
- Command executed:
- Date/time:
- Target (use a non-sensitive test target):
- Relevant output:
- What the result does and does not prove:
- Next step:

Do not run scans against systems without explicit authorization. Do not post internal network output publicly.
