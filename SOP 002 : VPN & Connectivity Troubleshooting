# SOP 002: VPN & Connectivity Troubleshooting 
Level: T1 Support
Target Resolution Time: 15 Minutes

1. Initial Triage
Connectivity Check: Ping `8.8.8.8`. If no response, the issue is the user's ISP, not the VPN.
DNS Flush: Run `ipconfig /flushdns` in Command Prompt to clear stale cache.

2. Technical Diagnostics
1. Service Check: Ensure the "Cisco AnyConnect" service is running in `services.msc`.
2. MFA Desync: Check if the user's system clock matches the current time. A drift of >2 minutes will cause MFA to fail.
3. MTU Tuning: If the user connects but cannot access internal apps, reduce MTU size to 1300 to account for packet fragmentation on home routers.

 3. Escalation Path
If the user cannot connect via multiple hotspots/networks, escalate to **Network Tier 2** to check for gateway outages.
