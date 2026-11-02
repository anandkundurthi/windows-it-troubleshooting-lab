# IP Configuration Troubleshooting

## Objective
Gather basic network configuration details when a Windows device cannot connect to a network resource.

## Commands
Open Command Prompt and run:

```cmd
ipconfig
ipconfig /all
```

`ipconfig` displays IP configuration. `ipconfig /all` provides additional adapter details such as IPv4/IPv6 addresses, subnet mask, default gateway and DNS servers.

## Procedure
1. Confirm whether the user is on Wi-Fi or Ethernet.
2. Check whether other websites or internal resources work.
3. Run `ipconfig` and identify the active adapter.
4. Review whether the adapter has an IP address, default gateway and DNS server.
5. Compare results with approved network documentation or escalate to the network team.
6. Record only relevant network details; redact public IPs or internal addressing before publishing examples.

## Interpretation notes
- `Media disconnected` can mean the adapter is not currently connected.
- An IPv4 address beginning `169.254` commonly indicates Windows did not obtain an IPv4 address from DHCP; confirm network context before concluding.
- Missing gateway or DNS information may be relevant, but do not change settings without authorization.

## Caution
Do not publish internal IP addresses, Wi-Fi names, MAC addresses or network diagrams from an employer's environment. Do not run network resets or change static addressing without approval.

## Record
- Connection type:
- Active adapter:
- Address/gateway/DNS observation (sanitize before sharing):
- Other affected users/devices:
- Finding:
- Next action / escalation:
