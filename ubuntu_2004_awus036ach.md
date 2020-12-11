follow https://github.com/aircrack-ng/rtl8812au/

```sh
git clone https://github.com/aircrack-ng/rtl8812au/
cd rtl8812au
sudo make dkms_install

## reboot

sudo dkms autoinstall
sudo dkms status
sudo modprobe 88XXau

sudo ip link set wl<tab> up
```
