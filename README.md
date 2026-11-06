<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=papercodeIN.NeuronEX" height="20" />

<h1 align="center">🌟 NeuronEX 🌟</h1>

<p align="center">
  <em>NeuronEX industrial edge data hub tutorials — install on Raspberry Pi and Docker, configure drivers and MQTT data flows</em>
</p>

<p align="center">
  <a href="https://www.youtube.com/@Fusion_Automate"><img src="https://img.shields.io/badge/YouTube-FusionAutomate-%23FF0000?style=for-the-badge&logo=youtube" alt="YouTube"></a>
  <a href="https://www.instagram.com/fusion_automate"><img src="https://img.shields.io/badge/Instagram-fusion__automate-%23E4405F?style=for-the-badge&logo=instagram" alt="Instagram"></a>
  <a href="https://x.com/fusion_automate"><img src="https://img.shields.io/badge/X-fusion__automate-000000?style=for-the-badge&logo=x" alt="X (Twitter)"></a>
  <a href="https://t.me/fusionautomate"><img src="https://img.shields.io/badge/Telegram-%40fusionautomate-%2326A5E4?style=for-the-badge&logo=telegram" alt="Telegram"></a>
  <a href="https://fusionautomate.in/"><img src="https://img.shields.io/badge/Website-fusionautomate.in-blueviolet?style=for-the-badge" alt="Website"></a>
</p>

---

$\color{Green}\Huge{\textbf{Basic}}$

1. 🆓️How to Install NeuronEX - Industrial Edge Data Hub in Raspberry Pi (Arm64) [[Watch]](https://youtu.be/NMHx8b6lYpc)
    - Code
        
        ```bash
        # Download the NeuronEX package for ARM64 architecture from the EMQX website.
        wget https://www.emqx.com/en/downloads/neuronex/v3.6.2/neuronex-3.6.2-linux-arm64.deb
        
        # Install the downloaded NeuronEX package using the Debian package manager.
        sudo dpkg -i neuronex-3.3.2-linux-arm64.deb
        
        # Start the NeuronEX service immediately.
        sudo systemctl start neuronex
        
        # Check the current status of the NeuronEX service to ensure it's running correctly.
        sudo systemctl status neuronex
        
        # Stop the NeuronEX service.
        sudo systemctl stop neuronex
        
        # Uninstall NeuronEX and remove all its associated files.
        sudo dpkg -P neuronex
        ```
        
2. 🆓️How to Run NeuronEX - Industrial Edge Data Hub in Docker using Virtuallabs.Online | [[Watch]](https://youtu.be/BXZvtEdxmGY)
3. 🆓️How to Download, Install and Run NeuronEX - Industrial Edge Data Hub in Linux using Virtuallabs.Online [[Watch]](https://youtu.be/f_hkAeRHVuc)
4. 🆓️Brief Understanding of the NeuronEX Edge Architecture, South Devices, North Apps, Etc [[Watch]](https://youtu.be/LfSE4qA8-1g)
5. 🆓️How to Import and Export Southbound Device Configuration in NeuronEX [[Watch]](https://youtu.be/Z2ttJgHXoEU)

##

$\color{Green}\Huge{\textbf{Data Collection [Southbound Device Communication]}}$

### OPC UA

1. 🆓️How to Configure Southbound Device in NeuronEX to Connect with OPC-UA Server [[Watch]](https://youtu.be/Is3qyxh2fN8)
    
    [Prosys_OPCUA_Southbound_Device_NeuronEX.json](https://github.com/papercodeIN/NeuronEX/blob/main/Files/Prosys_OPCUA_Southbound_Device_NeuronEX.json)
    
2. ⏳️How to Configure Southbound Device in NeuronEX to Connect with N3uron Free Public OPC UA Server [Watch]
    
    [N3uron-Object-Model-DemoPVSite.xlsx](https://github.com/papercodeIN/NeuronEX/blob/main/Files/N3uron-Object-Model-DemoPVSite.xlsx)
    
##
### Modbus TCP/IP

1. 🆓️How to Configure Southbound Device in NeuronEX to Connect with Modbus TCP/IP Device [[Watch]](https://youtu.be/XqCYdHgOyM4)
    
    [ModSim_Southbound_Device_NeuronEX.json](https://github.com/papercodeIN/NeuronEX/blob/main/Files/ModSim_Southbound_Device_NeuronEX.json)
    
##
### Modbus RTU

1. ⏳️How to Connect NeuronEX - Industrial Edge Data Hub with Modbus RTU/RS485/Serial Device [Watch]

##
### IEC60870-5-104

1. ⏳️How to Connect NeuronEX - Industrial Edge Data Hub with IEC60870-5-104 Device [Watch]

##
### BACnet/IP

1. ⏳️How to Connect NeuronEX - Industrial Edge Data Hub with BACnet IP Device [Watch]

##
### KNXnet/IP

1. ⏳️How to Connect NeuronEX - Industrial Edge Data Hub with KNXnet/IP Device [Watch]

##
$\color{Green}\Huge{\textbf{Data Delivery [North Apps]}}$

###
### MQTT

1. 🆓️How to Publish Data from Your Southbound Device (OPC-UA Server) to an MQTT Broker Using NeuronEX [[Watch]](https://youtu.be/PDsqWIF_MQ0)

##
### eKupier

##
### WebSocket

##
### SparkplugB

##
$\color{Green}\Huge{\textbf{Administration}}$

1. 🆓️User Management (Create/Delete/Edit) in NeuronEX - Industrial Edge Data Hub Platform [[Watch]](https://youtu.be/mR8SU8FyUcU)
---

---

## 📞 Contact

| 📞 Method | 🔗 Details |
|-----------|-----------|
| Call / WhatsApp | [+91-9974477759](https://wa.me/919974477759) |
| Telegram | [@fusionautomate](https://t.me/fusionautomate) |
| Email | [eng.innovativ@gmail.com](mailto:eng.innovativ@gmail.com) |

## 💖 Support My Work

<p align="center">
  <a href="https://buymeacoffee.com/pylin" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" style="height: 50px; width: 180px;">
  </a>
</p>

<p align="center">
  ⭐ Star this repo if it helped you · 🔔 <a href="https://github.com/papercodeIN">Follow Fusion Automate</a>
</p>
