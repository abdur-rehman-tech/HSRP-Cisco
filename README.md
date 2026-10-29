# 🔁 HSRP Lab (Cisco Packet Tracer)

![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)

A Cisco Packet Tracer lab implementing **HSRP (Hot Standby Router Protocol)** for first-hop gateway redundancy.

## 🧪 What it demonstrates

- Two routers sharing a **virtual IP** as the default gateway
- **Active / standby** roles based on priority
- **Preemption** and automatic failover when the active router goes down

## 🚀 Open the lab

Open `HSRP.pkt` in **Cisco Packet Tracer**.

## 🔧 Typical config

```
interface g0/0
 standby 1 ip <virtual-ip>
 standby 1 priority 110
 standby 1 preempt
```

Verify with `show standby brief`, then shut down the active router's interface to watch failover.

---

## 👤 Author

**Abdur Rehman** · DevSecOps Engineer · Founder of [ARTechOps](https://artechops.com)

[LinkedIn](https://www.linkedin.com/in/muhamad-abdur-rehman-81777b366/) · [GitHub](https://github.com/abdur-rehman-tech) · [artechops.com](https://artechops.com)
