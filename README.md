# Bambu DNS Blocklist

This is a DNS blocklist designed for use with **AdGuard** and **Pi-hole** to **prevent updates, cloud features, and remote access functionalities** on Bambu Lab devices and the Bambu Studio slicer. 
By using this blocklist, you can effectively block Bambu Lab's APIs and servers to achieve this goal.

## How to Use
To apply this blocklist, use the following URL:

```
https://raw.githubusercontent.com/sahelea1/bambu-dns-blocklist/refs/heads/main/hosts
```

Simply add this URL to your AdGuard or Pi-hole configuration to block the specified domains.

## Important Notes
### **Software Updates & WAN Access**
**Note:** It is theoretically possible that the printer may still be able to pull update files. Further investigation is needed to determine how it scans for new updates. 

For now, it is advised to **block WAN access for the printer entirely** to ensure it cannot communicate externally.

For more details, refer to [Bambu Lab Printer Network Ports](https://wiki.bambulab.com/en/general/printer-network-ports).

---

### **Contributing**
If you find additional domains that should be blocked or have insights into how the update mechanism works, please open an issue or submit a pull request.

---

Thanks for using and contributing to this project! 🎉

