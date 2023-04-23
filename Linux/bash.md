# **Linux Bash Notes**

## NTP
NTP (Network Time Protocol) is a protocol used for synchronizing the time on computer systems over a network.

```bash
# ntpd is a daemon or a background process that runs on a system and provides NTP functionality.
systemctl status ntpd

# start the ntpd servce if it does't activate
sudo systemctl start ntpd

# enable the NTP service to start automatically at boot
sudo systemctl enable ntpd

# check the status
sudo ntpstat

```




- [x] task 1
- [ ] task 2


