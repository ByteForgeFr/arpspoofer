<div align="center">

# arpspoofer

</div>

<img width="1539" height="755" alt="image" src="https://github.com/user-attachments/assets/d5fda07b-18b7-4b2c-9866-9e443760f9e5" />



## 🚀 Usage
This tool allows you to perform an ARP cache poisoning attacks between two targets (a `victim` and a `gateway`) on a local network. It manipulates the ARP tables of the victims to redirect network traffic through the attacker, enabling interception or modification of data.

> [!TIP]
> In the help menu, you can see `-g GATEWAY` and `-t TARGET`. However, if you want to capture traffic between two victims without one of them being the gateway, you can still use this tool with `-g TARGET1` and `-t TARGET2`.

<img width="1532" height="789" alt="image" src="https://github.com/user-attachments/assets/cd851c26-33e8-4e47-aaec-555a67c587e3" />


## ⚒️ Installation

```bash
git clone https://github.com/ByteForgeFr/arpspoofer
cd arpspoofer

# Install the needed requirements
pip install -r requirements.txt

# You must enable IPv4 forwarding
sudo sysctl -w net.ipv4.ip_forward=1
```
