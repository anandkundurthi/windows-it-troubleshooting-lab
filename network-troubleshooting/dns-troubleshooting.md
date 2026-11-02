# DNS and Name-Resolution Troubleshooting

## Problem description
A user can connect to a network but cannot reach a site or service by its hostname.

## Basic checks
1. Confirm the exact hostname and whether it is an internal or public service.
2. Check whether the same service works by its approved URL from another authorized device.
3. Run `nslookup example.com` using a public test domain, or the approved hostname in an authorized environment.
4. Record the DNS server shown and the response (for example, resolved address, timeout or NXDOMAIN).
5. Compare with another known-good device only when permitted.

## Useful command

```cmd
nslookup example.com
```

`nslookup` queries DNS to obtain name-resolution information. Replace the example hostname only with a domain you are authorized to test.

## Interpretation
- A returned address indicates that the queried name resolved through the DNS server used.
- `NXDOMAIN` generally means the DNS server reports that the name does not exist.
- A timeout can indicate a DNS server or network reachability problem; it does not by itself identify the root cause.

## Optional cache action
`ipconfig /displaydns` displays the local DNS resolver cache. `ipconfig /flushdns` clears that cache. Use the flush command only when appropriate, permitted by policy, and after recording relevant evidence; it is not a universal fix.

## Record
- Hostname tested (non-sensitive):
- Command and time:
- DNS server / response:
- Scope (one user or multiple):
- Finding:
- Action / verification / escalation:
