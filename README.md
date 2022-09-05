
# Home Server

## Hardware / Host OS
Low power, budget homelab. Linux Mint running in an Intel NUC acting as a Home Server / Home Theater PC.  
Future plans to migrate to Proxmox as a dedicated home server. Currently, most services run containerized in Docker.


## Docker
- **Home Assistant** -  Open source home automation solution to provide modular local smart home control.

    - **NodeRED** : Flow based modular IoT automation development tool (Presence detection, Telegram bots, Crypto bots, security camera alerts, etc.)
    
    - **Frigate** : Open source NVR with local real-time AI object detection
    - **UniFi** : Wireless access points controller, VLANs, client statistics, ~~VPN~~
    - **Mosquitto** : MQTT broker
    - **Zigbee2MQTT** : Brand agnostic control of Zigbee devices using MQTT protocol
    - ~~**DuckDNS** : Dynamic DNS service~~
    - **Tailscale** : Replaces VPN and dynamic DNS and consolidates remote access in one service without opening router ports
    - **Uptime Kuma** : Self hosted uptime monitor for critical services
    - **diyHue** : Retain Philips Hue bridge functionality by emulating proprietary physical hub through software. 


## Future plans
- Google Coral TPU : Hardware AI accelerator for Frigate
- Dedicated home server running Proxmox
- Ansible to automate server deployment
- DNS filtering for ad blocking
- FreeNAS / NextCloud instance
