# T1496.002 - Bandwidth Hijacking

| Field | Details |
|-------|---------|
| **Tactic** | [Impact](https://attack.mitre.org/tactics/TA0040/) |
| **Technique** | [Resource Hijacking — T1496](https://attack.mitre.org/techniques/T1496/) |
| **Sub-technique** | [Bandwidth Hijacking — T1496.002](https://attack.mitre.org/techniques/T1496/002/) |
| **Platforms** | Linux, Windows |
| **Tools used** | VirtualBox, Wireshark, Docker, pawns-cli [[1]](#references), squid [[2]](#references), Blacklists UT1 [[3]](#references) |

---

## 📖 Description

Adversaries may hijack the victim's network bandwidth to relay traffic through compromised systems, effectively turning them into proxy nodes. This sub-technique falls under Resource Hijacking, where the attacker monetizes or exploits the victim's resources without their consent.

In this test, `pawns-cli` is deployed on the target to simulate a proxyware agent that shares the host's bandwidth with a commercial proxy network, while `squid` acts as a forwarding proxy. Traffic is analyzed with Wireshark to identify detection opportunities.

---



## ⚔️ Execution





---

## 📚 References

- [1] [pawns-cli](URL)
- [2] [squid](URL)
- [3] [Blacklists UT1](URL)
- [MITRE ATT&CK — T1496.002](https://attack.mitre.org/techniques/T1496/002/)
