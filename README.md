# Alexander

IT / cybersecurity practitioner. I run IT end to end for a small business: identity lifecycle, endpoint hardening, network segmentation, email security, and incident response. My projects apply the same discipline I use at work: security that is cheap to run, boring by design, and verified instead of assumed.

## Featured work

- **[Lock_Down](https://github.com/PaulinoTech1/Lock_Down)** - Hardware-tailored, security-hardened Linux workstation build. Custom kernel configs, userspace hardening, and procedures verified against the actual hardware. The repo documents the learning arc, mistakes included.
- **[Identity lifecycle automation](https://github.com/PaulinoTech1/JML-)** - PowerShell + Microsoft Graph joiner/mover/leaver automation. Dry-run by default, a single mutation choke point, and a JSONL audit trail.
- **[stegdetect](https://github.com/PaulinoTech1/Steganography)** - Pre-filter that catches steganographic prompt injection (zero-width characters, bidi overrides, homoglyph substitution) before untrusted text reaches a language model. No GPU, no weights, works in front of any model.
- **[VLAN segmentation](https://github.com/PaulinoTech1/Vlan-segementation)** - Reproducible Cisco IOS XE templates, Ansible drift management, and an Entra ID / RADIUS reference integration, with a deployment acceptance runbook.
- **[Flock-Off](https://github.com/PaulinoTech1/Flock-Off)** - Public tracker of ALPR (license plate reader) contracts with forensic source archiving. Privacy advocacy through transparency.
- **[state-gaurd](https://github.com/PaulinoTech1/state-gaurd)** - Lightweight Windows/Linux endpoint audit with JSON drift detection and guarded remediation. Stdlib Python, CLI plus GUI.

## Home lab

Pieced together from vendor deals rather than a single-vendor stack. Built to test what I deploy at work before it touches production.

**Network core**

- Modem: ARRIS SURFboard SB8200 (DOCSIS 3.1)
- Firewall: SonicWall TZ270
- Switch: NETGEAR ProSAFE JGS524 (24-port Gigabit)
- Wireless: Ubiquiti UniFi U6 Pro (Wi-Fi 6)
- Host networking: PCIe Ethernet NIC

**Compute**

- Proxmox VE on Ryzen 9 5900X / RTX 3090 Ti / 64 GB RAM (doubles as the local-AI box)
- 2x Raspberry Pi 5

**Daily drivers**

- ThinkPad T14 Gen 3 (i5-1245U), Ubuntu, hardened kernel project build
- Pixel 10 Pro XL

## Experience

- **Sonia's Auto Sales** - IT admin, then sysadmin / IT admin (~3 years). Sole IT across two locations: identity and access, endpoints, network, email security, incident response. The title change mostly reflected the two-site scope.

## How I work

- Fail-closed defaults, least privilege, threat-model-driven controls
- Verify that controls actually function; distinguish verified controls from assumptions
- Prefer mature, boring tooling over novel dependencies
- Write down the reasoning, not just the result

## Stack

PowerShell, Python, Microsoft Entra ID / 365, Intune, Windows Server, Linux hardening, VLANs and firewall policy, DMARC and email security, Vercel, Cloudflare

## Links

- Portfolio: [paulinotech.com](https://paulinotech.com)
