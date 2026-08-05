# -Pi-hole-Homelab-Netzwerkweiter-DNS-Werbeblocker
Ein containerisierter Pi-hole-Server auf einem Raspberry Pi 400, der Werbung und Tracker für alle Geräte im Heimnetzwerk automatisch blockiert – zentral auf DNS-Ebene, nicht pro Gerät.
## Warum
Praktische Anwendung von dem, was ich gerade in Networking Basics (Cisco
NetAcad, Richtung CCST/CCNA) lerne – DNS, DHCP, Linux-Kommandozeile, Docker.

## Tech Stack
- Raspberry Pi 400 (Raspberry Pi OS)
- Docker
- Pi-hole
- Router: TP-Link Archer AXE75 (DHCP-DNS-Redirect)

## Setup

Docker installieren:
```bash
curl -sSL https://get.docker.com | sh