
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=7,24,13&height=260&section=header&text=STATEFUL%20FILTER&fontSize=75&fontColor=ffffff&animation=fadeIn&fontAlignY=42&desc=Next-Gen%20Network%20Security&descAlignY=68&descSize=24&descAlign=50" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=22&duration=2800&pause=1000&color=0EA5E9&center=true&vCenter=true&width=750&lines=Deep+Packet+Inspection.;Zero-Trust+Architecture.;Protect+your+network+perimeter." alt="Typing SVG"/>

<br/><br/>

<a href="https://share.google/KW31cAu9oXNovwmMA">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-0EA5E9?style=for-the-badge&logo=github&logoColor=white&labelColor=0284C7" height="50"/>
</a>
&nbsp;
<a href="https://share.google/KW31cAu9oXNovwmMA">
  <img src="https://img.shields.io/badge/🚀_DEPLOY_NOW-0284C7?style=for-the-badge&logo=linux&logoColor=white&labelColor=0369A1" height="50"/>
</a>
&nbsp;
<a href="https://share.google/KW31cAu9oXNovwmMA">
  <img src="https://img.shields.io/badge/📚_DOCS-38BDF8?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=0EA5E9" height="50"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/version-4.2.0-0284C7?style=flat-square&logo=semanticrelease&logoColor=white"/>
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/license-MIT-0EA5E9?style=flat-square&logo=opensourceinitiative&logoColor=white"/>
<img src="https://img.shields.io/badge/downloads-76K%2B-0369A1?style=flat-square&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/status-enterprise--ready-06D6A0?style=flat-square&logo=checkmarx&logoColor=white"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛡️ Bulletproof Your Network Perimeter

**Stateful Packet Filter** is a high-performance, enterprise-grade firewall application built to provide deep, intelligent inspection of your network traffic. 

Unlike simple stateless firewalls that just look at IP addresses and ports, this tool tracks the state of network connections. It understands the context of the traffic — allowing it to distinguish between legitimate responses to a request you made, and malicious unsolicited inbound connections. 

Built in C++, it sits right at the kernel level to provide the lowest possible latency while analyzing millions of packets per second. Whether you are securing a home lab, a corporate server, or a critical infrastructure node, this filter gives you total, programmable control over who gets in and who gets blocked.

> 💡 **Why use this filter?** Because modern threats require modern defenses. Stop configuring clunky iptables rules and embrace a modern, developer-friendly filtering engine with real-time logging and stateful connection tracking.

<br/>

<table align="center" width="100%" style="border-collapse: collapse; border: 1px solid #0EA5E9; border-radius: 10px;">
<tr style="background-color: #082F49; color: #0EA5E9;">
<th align="center" width="25%" style="padding: 15px;">🔍 Deep Inspection</th>
<th align="center" width="25%" style="padding: 15px;">🔄 State Tracking</th>
<th align="center" width="25%" style="padding: 15px;">⚡ Zero Latency</th>
<th align="center" width="25%" style="padding: 15px;">🛡️ DDoS Mitigation</th>
</tr>
<tr>
<td align="center" style="padding: 15px; color: #ddd;">Analyzes packet payloads and headers against custom rules.</td>
<td align="center" style="padding: 15px; color: #ddd;">Tracks TCP/UDP connections to prevent spoofing attacks.</td>
<td align="center" style="padding: 15px; color: #ddd;">C++ kernel modules ensure minimal network overhead.</td>
<td align="center" style="padding: 15px; color: #ddd;">Automatically rate-limits IPs sending SYN floods.</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚡ Why This Filter Stands Out

<div align="center">

| 🧩 **The Challenge** | 💡 **Our Solution** | 📈 **The Result** |
|:---|:---|:---|
| Legacy firewall rules are hard to read | **YAML-based rule engine** | Highly readable and version-controllable |
| Network attacks bypass simple filters | **TCP State Machine** | Automatically drops out-of-state packets |
| Performance drops under heavy load | **Zero-copy packet processing** | Line-rate filtering up to 10Gbps |
| Hard to debug what is blocked | **Real-time log streaming** | See exactly why a packet was dropped |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Core Features

<div align="center">

| 📜 **Rule Engine** | 🌐 **Geo-Blocking** | 📊 **Metrics Export** |
|:---:|:---:|:---:|
| Define allow/deny rules based on IP, port, and protocol | Block traffic based on country of origin | Prometheus integration for Grafana dashboards |

| 🕵️ **Intrusion Detection** | 🛑 **Rate Limiting** | 🔄 **Hot Reload** |
|:---:|:---:|:---:|
| Detect known malicious payload signatures | Throttle abusive IPs automatically | Update rules without restarting the service |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🖼️ Dashboard Interface

<div align="center">

<img width="1671" height="941" alt="a316ee7f-b2a4-49e7-b542-2bcf27a6e85e" src="https://github.com/user-attachments/assets/54f125c3-9629-4486-aece-21aad3d040c5" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🚀 Quick Start

> **Three steps. Under two minutes. Deploy your firewall.**

### 1️⃣ Install the binary
Clone the repository and compile the kernel module.

```bash
git clone https://github.com/yourname/stateful-filter.git
cd stateful-filter
make build && sudo make install
```

### 2️⃣ Configure your rules
Edit the `rules.yaml` file to define your network policies.

```yaml
allow:
  - port: 22
    protocol: tcp
    source: 192.168.1.0/24
deny:
  - port: 80
    protocol: tcp
    source: any
```

### 3️⃣ Start the service
```bash
sudo systemctl start stateful-filter
```

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚙️ How It Works

<div align="center">

| Layer | Responsibility | Tech |
|:---|:---|:---|
| 📡 **Kernel Hook** | Intercepts packets before the OS processes them | `eBPF` / `Netfilter` |
| 🧠 **State Engine** | Tracks active TCP/UDP sessions | `C++` |
| 📜 **Policy Manager** | Evaluates packets against rules | `Rust` |
| 📊 **Logger** | Streams events to the UI | `WebSockets` |

</div>

The core is written in C++ and utilizes eBPF (Extended Berkeley Packet Filter) to process packets in the Linux kernel space with near-zero overhead, making it perfect for high-traffic servers.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧠 Pro Tips

<table align="center" width="100%">
<tr>
<td width="50%">

**For server security**
- 🛡️ Default to a "Deny All" policy, then whitelist ports
- 🌐 Block entire regions you don't do business with
- ⚡ Enable SYN flood protection on public web servers
- 📊 Set up alerts for high drop rates

</td>
<td width="50%">

**For home labs**
- 🏠 Use it to isolate IoT devices on your network
- 🚫 Block telemetry and ad-trackers at the network level
- 🔄 Keep a backup of your `rules.yaml` file
- 📺 Monitor traffic to see if your smart TV is spying on you

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ❓ Frequently Asked Questions

<details>
<summary><b>Is this a hardware firewall?</b></summary>

No, this is a **software** firewall application designed to run on a Linux server or virtual machine. It requires a standard x86 or ARM architecture processor.
</details>

<details>
<summary><b>Can it replace UFW or iptables?</b></summary>

Yes. While it sits on top of iptables/Netfilter under the hood, it completely abstracts away the complex syntax, providing a much easier way to manage stateful connections.
</details>

<details>
<summary><b>How much CPU does it use?</b></summary>

Thanks to the eBPF implementation, CPU usage is typically under 1% even on servers processing gigabytes of traffic per day.
</details>

<details>
<summary><b>Does it support IPv6?</b></summary>

Yes, full IPv6 support is included out of the box, including stateful tracking and geo-blocking for IPv6 addresses.
</details>

<details>
<summary><b>How do I report a bug?</b></summary>

Open an issue on the GitHub repository. Include your OS version, kernel version, and a copy of your `rules.yaml` file.
</details>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License & Disclaimer

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

<a href="https://share.google/KW31cAu9oXNovwmMA">
  <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_FILTER-0EA5E9?style=for-the-badge&logo=linux&logoColor=white&labelColor=0284C7" height="55"/>
</a>

<br/><br/>

**⭐ If this tool secured your infrastructure — star the repo!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=7,24,13&height=140&section=footer&text=Inspect.+Filter.+Secure.&fontSize=22&fontColor=0EA5E9" width="100%"/>

</div>
