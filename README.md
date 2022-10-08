# bes-r Homelab
This github is dedicated to my homelab setup. It's build with a low energy build server and Unifi equipment. My homelab started because of security reasons, but extended with everything to comfort me and my family. Because I'm Dutch some parts of the configurations are in my own language.

<details>
  <summary> Server </summary>
  
  ## Server hardware
  The server is a selfbuild one. It's based on the [work of @mrmrmr](https://gathering.tweakers.net/forum/list_messages/1673583) to be a low energie build. It's original build as a cloudserver (Nextcloud) for two small companies.
  
  |Device              |Manufractor        |Model/type                |Amount  |Note                              |
  |--------------------|-------------------|--------------------------|:------:|----------------------------------|
  |Motherboard         |Fujitsu            |D3642-B                   |1       |                                  |
  |CPU                 |Intel              |i3-8100                   |1       |                                  |
  |Cooler              |Artic              |Alpine 12 Passive         |1       |                                  |
  |Memory              |Samsung            |M391A2K43BB1-CTD - 16GB   |2       |                                  |
  |Harddrive           |Intel              |660p - 1TB                |1       |M2 SSD; host drive                |
  |Harddrive           |Seagate            |Expansion Portable - 5TB  |3       |Disassembled; RaidZ1; data drives |
  |Hardrive            |Seagate            |Expansion Portable - 5TB  |1       |back-up drive                     |
  |Power               |Mini-Box           |PicoPSU 90                |1       |                                  |
  |AC-adapter          |Leicke             |ULL Power Suply 120W      |1       |                                  |
  |Case                |Be Quiet           |Pure Base 600             |1       |                                  |
  
  ## Server OS
  My first server was hosting [Ubuntu Server](https://ubuntu.com/download/server). Later when there came more needs it set-up the above server and installed [Proxmox](https://www.proxmox.com/) as an [hypervisor](https://nl.wikipedia.org/wiki/Hypervisor) with multiple VM's and LSC. My Proxmox configuration is added in a [repositorie](https://github.com/bes-r/Proxmox-config/).
  
</details>
  
<details>
  <summary> Ubiquiti Unifi </summary>
     
  ### Network hardware
  
  My network is build on Ubiquiti's Unifi. Unfortunately Ubiquiti isn't always that stable and there are some functions still missing on their controller. But I must admit, I love the all in one solution and UI.
  
  <b>[UDM Pro](https://eu.store.ui.com/products/udm-pro)</b><br />
  <i>The one in all controller for my Unifi Network and Unifi Protect (video surveillance).</i>
  
  <b>[Switch 24 PoE](https://eu.store.ui.com/collections/unifi-network-routing-switching/products/usw-24-poe)</b><br />
  <i>A 24-ports switch with PoE where al the RJ45 cables are attached to. Some devices receive Power over Ethernet (PoE) from this switch, so there's no additional cable needed.</i>
  
  <b>[Camera G3 Instant](https://eu.store.ui.com/collections/unifi-protect/products/unifi-protect-g3-instant-camera)</b><br />
  <i>This little camera is my portable camera. I'm not a fan of an indoor camara, but this one I've used as dog-cam :dog:.</i>
  
  <b>[Camera G3 Bullet](https://eu.store.ui.com/collections/unifi-protect/products/unifi-video-camera-g3)</b><br />
  <i>For outside/garden security I'm using this bullet.</i>

  ### Ubiquiti Unifi Configurations
  Below you can find my configurations and files I use with my UDM Pro/Unifi setup.
  
  1. [Unifi UDM Pro configuaration](https://github.com/bes-r/Unifi_UDM_Pro-config)
  2. [IPTV - KPN](https://github.com/bes-r/udm-iptv)
  3. [Unifi G4 doorbell - sounds](https://github.com/bes-r/Unifi-G4-Doorbel-sounds)
    
</details>

<details>
  
  <summary> Proxmox LXC's </summary>
  
  ### Proxmox LXC's
  Since I discoverd [TTeck's Git](https://github.com/tteck/Proxmox), I'm all over in using his scripts. And he is really on fire, recently he added a lot of new containers.
  
</details>

<details>
  
  <summary> Docker-compose configs </summary>
  
  ### Docker-compose files
  In the past I had a really hate-love story with Docker. So I used always LXC-containers within Proxmox. But some applications I run in Docker. Maybe, someday, I will turn. Check [my docker-compose files](https://github.com/bes-r/docker-compose/) to set up you're favourite programms.
  
  
  <details>
  <summary> Adguard Home </summary>
  
  [Adguard Home]([https://github.com/bes-r/docker-compose/tree/main/portainer](https://github.com/bes-r/docker-compose/tree/main/adguard-home)) can work as a dns-server with adblocker and has also an option to work as a dhcp-server.

  </details>
  
  <details>
  <summary> Portainer </summary>
  
  [Portainer](https://github.com/bes-r/docker-compose/tree/main/portainer) is a GUI to manage docker containers.

  </details>

  <details>
  <summary> Wishlist </summary>

  [Wishlist](https://github.com/bes-r/docker-compose/tree/main/wishlist) is created as a wishlist for Christmas. But it can also be used for other celebrations. I'm still looking for a better and cleaner solution.

  </details>
  
</details>

<details>
  
  <summary> Home Assistant </summary>
  
  ### 🏡 Home Assistant configuration
  [Home Assistant](https://github.com/home-assistant/core) is a Python based home automation software which can be hosted on you're own server. [The software](https://www.home-assistant.io/) is well supported by [the community](https://community.home-assistant.io/). [My Home Assistant](https://github.com/bes-r/Home-Assistant-config/) is constantly under construction.
  
 ### Devices
 
  
</details>

<details>
  
  <summary> Cheat sheets </summary>
  
  ### Codes to remember
  1. Zigbee2mqtt
  2. ZwaveJS
  3. Markdown
  
</details>
