### How to run

If you also want to use Adguard as a DHCP server you'll need to uncomment the DHCP ports in `adguard.pod` and the `Network=host` line.

```bash
git clone https://github.com/JoeNorth/quadlets.git
cd quadlets/adguard-home
sudo cp -r . /etc/containers/systemd/
sudo systemctl start adguard
```