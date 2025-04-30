# Networking5
Single Point Failure + Redundancy
--------------------------------------
# Lab 5: Redundancy & Single-Point Failure

### Overview
Examined network resilience by bringing routers down and observing failures, then introduced VRRP concepts as a remedy.

### Topology
- Multiple subnets (/29) interconnected by 3 routers with RIP.

### Tasks & Results
1. **RIP & DHCP**  
   - Configured RIP and DHCP on each router.

2. **Failure Test**  
   - Shut down R1; observed PC5→PC1 pings time out.

3. **High Availability Discussion**  
   - Noted need for VRRP to eliminate single-point failures.

### Lessons Learned
- Importance of redundant gateways.
- How VRRP provides seamless failover.
