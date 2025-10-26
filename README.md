# 🧊 OPERATION: L.O.W. (Lethal Output Workflow) 🧊

## 🚨 CLASSIFIED: PRIVATE ASSET PROTOCOL

**THIS REPOSITORY IS STRICTLY PRIVATE.** It is designed for singular, exclusive use. Any distribution, modification, or sharing outside of authorized channels is prohibited. This is not for public consumption.

### **MADE BY 65pd**

---

## ⚙️ CORE MODULE SPECIFICATIONS

This workflow provisions a transient, high-velocity access point for maximum operational efficiency. Forget the slow lane; this is the nexus of power and speed.

| Parameter | Specification | Vibe Status |
| :--- | :--- | :--- |
| **Platform** | Windows 11 Enterprise (Latest Stable Runner) | **L**egendary |
| **Connection Protocol** | RDP over Tailscale (Zero-Trust Fabric) | **C**hilly |
| **Network Output** | **~4 GB/s** (The minimum required velocity) | **I**nsane |
| **Access Duration** | Max 360 Minutes per cycle (via Handoff Logic) | **A**dvanced |
| **Interface** | Raw RDP for Unfiltered Control | **B**adass |

---

## ⚡ ACCESS PROTOCOL: INITIATE RDP SEQUENCE

Connection is routed through your private Tailnet. Authentication details are generated upon successful deployment of the GitHub Action.

1.  **Deploy Action:** Execute the `RDP + Tailscale Handoff (A)` workflow.
2.  **Inject Key:** Provide your exclusive Tailscale Auth Key.
3.  **Monitor Output:** After the **Install + Up Tailscale** step, the core connection details will be logged.

### 🔑 CRITICAL CONNECTION LOG

Locate these variables in the Action run log, specifically in the **🔔 RDP Connection Details 🔑** step:

| Credential | Value | Function |
| :--- | :--- | :--- |
| **RDP IP ADDRESS** | `[ip-address-from-log]` | Primary Connection Target (Tailscale IP) |
| **RDP USER** | `ghuser` | Access Identity |
| **RDP PASSWORD** | `GH@runner!123` | Secure Access Code |

> **ACTION:** Use the **RDP IP Address** and the provided credentials in your Remote Desktop client.

---

## ❄️ L-LEVEL EFFICIENCY LOGIC

The system employs a sophisticated A/B workflow handoff (`A.yml` -> `B.yml` -> `A.yml`) to maximize uptime and prevent runner expiration, ensuring your **L-level** session is maintained for as long as possible.

* `rdp-tailscale-A.yml` -> Dispatches `rdp-tailscale-B.yml`
* `rdp-tailscale-B.yml` -> Dispatches `rdp-tailscale-A.yml`

**This is a professional-grade, high-control environment. Operate accordingly.**
