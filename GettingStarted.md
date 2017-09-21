# Getting Started

## Quick Guide to Setup Wireless Gigabit Links

* Download and fetch our latest lede image for the Talon AD7200 from our [releases](https://github.com/seemoo-lab/lede-ad7200/releases).
* Follow the [instructions](https://github.com/seemoo-lab/lede-ad7200#device-flashing) to flash the image on one device.
* Connect to the device 'ssh 192.168.0.1' and change the IP address:
  ```bash
  ifconfig eth1 192.168.0.2
  ```
* Connect again using the new address ''ssh 192.168.0.2' and configure it as access point and start the iperf server
  ```bash
  ifconfig wlan2 192.168.100.2
  hostapd -B /etc/hostapd_wlan2.conf
  iperf3 -s
  ```
* Flash your second device
* Connect to the device 'ssh 192.168.0.1' and start iperf in client mode
  ```bash
  iperf3 -c 192.168.100.2
  ```
* You should see a performance similar to the following:
  ```bash
  [SUM]   0.00-10.00  sec  2.27 GBytes  1.95 Gbits/sec    0             sender
  [SUM]   0.00-10.00  sec  2.27 GBytes  1.95 Gbits/sec                  receiver
  ```