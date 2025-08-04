# MAC Address Changer

This is a simple Python tool to change the MAC address of a network interface on Linux (Kali Linux).

## 📌 Features
- Change your MAC address quickly.
- Check your current MAC address.
- Easy to use with command-line options.

## ⚙️ Usage

```bash
sudo python3 mac_changer.py -i [interface] -m [new_mac]
```

**Example:**

```bash
sudo python3 mac_changer.py -i eth0 -m 00:11:22:33:44:55
```

## 🚩 Options

- `-i`, `--interface` : The network interface (e.g., eth0, wlan0)
- `-m`, `--mac` : The new MAC address you want to set.

## ✅ Requirements

- Python 3
- ifconfig (part of net-tools)

## ⚠️ Note

Changing your MAC address might disconnect you from the network temporarily. Use responsibly.

---

## ✨ Author

**Syed Fayaj Basha**

