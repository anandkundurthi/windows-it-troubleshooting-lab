# Wi-Fi Connectivity Troubleshooting

## Intake questions
- Is Wi-Fi unavailable, disconnected, or connected with no internet access?
- Is the issue limited to one device or affecting multiple users?
- Does the device see the expected network?
- Did the issue start after moving location, changing a password or updating the device?
- Is the user in an area with known coverage?

## First-line checks
1. Confirm Wi-Fi is enabled and Airplane mode is off.
2. Check whether the expected wireless network is visible.
3. Confirm the user is selecting the correct organization-approved network.
4. Check whether other authorized devices can connect.
5. If connected, run `ipconfig` and inspect the active wireless adapter.
6. Test a permitted known public destination with `ping` only if ICMP testing is allowed; some hosts block ping.
7. Record the exact status and any error message.

## Safe actions
- Toggle Wi-Fi off and on only if permitted.
- Reconnect only to a known, authorized network using the approved credentials process.
- Forgetting a network, resetting network settings or changing adapter properties can remove configuration; do these only with approval.

## Escalate when
- Multiple users or an entire site are affected.
- The device cannot see a normally available corporate SSID.
- Authentication or certificate errors appear.
- The issue may involve access points, DHCP, wireless controllers or security policy.

## Record
- Location (general area only):
- SSID (do not publish sensitive network names):
- Connection status:
- One device or multiple:
- Checks and results:
- Action and user verification:
- Escalation details:
