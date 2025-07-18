# tc358743_capture
HDMI-in capturing via TC358743 chip
dts file show little example of overlay for orange pi 5. This overlay works for i2c bus 2
Minimal program for capturing is in example


Install:
- add rk3588-tc358743-cam2.dts to /boot/dtb/rockchip/overlay
- sudo orangepi-config
  switch on tc358743-cam2 in Hardware

Using:
./hdmi_capture
